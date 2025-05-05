# en-601-682-homework-3-solved
**TO GET THIS SOLUTION VISIT:** [EN.601.682 Homework 3 Solved](https://www.ankitcodinghub.com/product/en-601-682-homework-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94968&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EN.601.682 Homework 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
<ol>
<li>We have talked about backpropagation in class. And here is a supplementary material for calculating the gradient for backpropagation (https://piazza.com/class_profile/get_ resource/jxcftju833c25t/k0labsf3cny4qw). Please study this material carefully before you start this exercise. Suppose P = W X and L = f (P ) which is a loss function.
<ol>
<li>(a) &nbsp;Please show that ∂ L = ∂ L X T . Show each step of your derivation. ∂W ∂P</li>
<li>(b) &nbsp;Suppose the loss function is L2 loss. L2 loss is de􏰅ned as L(y, yˆ) = ∥y − yˆ∥2 where y is the groundtruth; yˆ is the prediction. Given the following initialization of W and X, please calculate the updated W after one iteration. (step size = 0.1)
􏰁 0.3 0.5􏰂 􏰆 􏰇 􏰁0 2􏰂 􏰆 􏰇 􏰁0.5 1 􏰂 W= −0.2 0.4 ,X=x1,x2 = 3 1 ,Y=y1,y2 = 1 −1.5
</li>
</ol>
</li>
<li>In this exercise, we will explore how vanishing and exploding gradients a􏰄ect the learning process. Consider a simple, 1-dimensional, 3 layer network with data x ∈ R, prediction yˆ ∈ [0,1], true label y ∈ {0,1}, and weights w1,w2,w3 ∈ R, where weights are initialized randomly via ∼ N(0,1). We will use the sigmoid activation function σ between all layers, and the cross entropy loss function L(y, yˆ) = −(y log(yˆ) + (1 − y) log(1 − yˆ)). This network can be represented as: yˆ = σ(w3 · σ(w2 · σ(w1 · x))). Note that for this problem, we are not including a bias term.
<ol>
<li>(a) &nbsp;Compute the derivative for a sigmoid. What are the values of the extrema of this derivative, and when are they reached?</li>
<li>(b) &nbsp;Consider a random initialization of w1 = 0.25,w2 = −0.11,w3 = 0.78, and a sample from the data set (x = 0.63, y = 1). Using backpropagation, compute the gradients for each weight. What have you noticed about the magnitude of the gradient?

Now consider that we want to switch to a regression task and use a similar network structure as we did above: we remove the 􏰅nal sigmoid activation, so our new network is de􏰅ned as yˆ = w3 · σ(w2 · σ(w1 · x)), where predictions yˆ ∈ R and targets y ∈ R; we use the L2 loss function instead of cross entropy: L(y,yˆ) = (y−yˆ)2. Derive the gradient of the loss function with respect to each of the weights w1,w2,w3.</li>
<li>(c) &nbsp;Consider again the random initialization of w1 = 0.25, w2 = −0.11, w3 = 0.78, and a sample from the data set (x = 0.63,y = 128). Using backpropagation, compute the gradients for each weight. What have you noticed about the magnitude of the gradient?</li>
</ol>
</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
