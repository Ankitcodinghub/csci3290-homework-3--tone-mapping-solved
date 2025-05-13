# csci3290-homework-3--tone-mapping-solved
**TO GET THIS SOLUTION VISIT:** [CSCI3290 Homework 3 -Tone Mapping Solved](https://www.ankitcodinghub.com/product/csci3290-homework-3-tone-mapping-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92234&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI3290 Homework 3 -Tone Mapping Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Tone Mapping

1 Assignment description

Tone mapping is a technique used in image processing to map one set of colors to another to approximate the appearance of high-dynamic-range (HDR) images in a medium that has a more limited dynamic range. Tone mapping operators can be divided into two main types:

<ul>
<li>global operators: non-linear functions based on the luminance and other global variables of the image.</li>
<li>local operators: the parameters of the non-linear function change in each pixel, according to features extracted from the surrounding parameters.
In this assignment, you’ll need to implement these two types of tone mapping with 2 operators respectively: global logarithmic operator and Durand’s local operator.
</li>
</ul>
2 Assignment details 2.1 Overview

Given the path of an HDR image, the tone mapping procedure can be described as follows:

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
procedure 𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇(𝐻𝐻𝐻𝐻𝐻𝐻_𝐼𝐼𝐼𝐼𝑇𝑇𝑇𝑇𝑇𝑇_𝑃𝑃𝑇𝑇𝑇𝑇h, 𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇)

1. Load 𝐻𝐻𝐻𝐻𝐻𝐻_𝐼𝐼𝐼𝐼𝑇𝑇𝑇𝑇𝑇𝑇 from 𝐻𝐻𝐻𝐻𝐻𝐻_𝐼𝐼𝐼𝐼𝑇𝑇𝑇𝑇𝑇𝑇_𝑃𝑃𝑇𝑇𝑇𝑇h. [provided]

2. Apply 𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇 to 𝐻𝐻𝐻𝐻𝐻𝐻_𝐼𝐼𝐼𝐼𝑇𝑇𝑇𝑇𝑇𝑇, get tone mapped 𝐿𝐿𝐻𝐻𝐻𝐻_𝐼𝐼𝐼𝐼𝑇𝑇𝑇𝑇𝑇𝑇. 3. Apply gamma correction to the result 𝐿𝐿𝐻𝐻𝐻𝐻_𝐼𝐼𝐼𝐼𝑇𝑇𝑇𝑇𝑇𝑇. [provided]

4. Convert the 𝐿𝐿𝐻𝐻𝐻𝐻_𝐼𝐼𝐼𝐼𝑇𝑇𝑇𝑇𝑇𝑇 to 8-bit. [provided]

5. Save the 𝐿𝐿𝐻𝐻𝐻𝐻_𝐼𝐼𝐼𝐼𝑇𝑇𝑇𝑇𝑇𝑇. [provided]

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
2.2 ToneMapfunctions

</div>
</div>
<div class="layoutArea">
<div class="column">
The algorithm of a generic 𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇 can be described as follows:

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
procedure 𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇(𝐻𝐻𝐻𝐻𝐻𝐻_𝐼𝐼𝐼𝐼𝑇𝑇𝑇𝑇𝑇𝑇)

1. Compute the Luminance 𝐿𝐿 of each pixel in the 𝐻𝐻𝐻𝐻𝐻𝐻_𝐼𝐼𝐼𝐼𝑇𝑇𝑇𝑇𝑇𝑇.

</div>
</div>
<div class="layoutArea">
<div class="column">
[compute_luminance()]

2. Apply 𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇 to 𝐿𝐿, compute the Display Luminance 𝐻𝐻 =

</div>
</div>
<div class="layoutArea">
<div class="column">
𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇(𝐿𝐿). [tone mapping operators]

3. Map Display Luminace 𝐻𝐻 on the 𝐻𝐻𝐻𝐻𝐻𝐻_𝐼𝐼𝐼𝐼𝑇𝑇𝑇𝑇𝑇𝑇 to compose the 𝐿𝐿𝐻𝐻𝐻𝐻_𝐼𝐼𝐼𝐼𝑇𝑇𝑇𝑇𝑇𝑇.

</div>
</div>
<div class="layoutArea">
<div class="column">
[map_luminance()] 4. Return .

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
𝐿𝐿𝐻𝐻𝐻𝐻_𝐼𝐼𝐼𝐼𝑇𝑇𝑇𝑇𝑇𝑇

We will discuss the implementation details in next several subsections.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
2.3 Operators

2.3.1 Logarithmic operator

</div>
</div>
<div class="layoutArea">
<div class="column">
We can use the following function to map the luminance 𝑳𝑳 of the 𝐻𝐻𝐻𝐻𝐻𝐻_𝐼𝐼𝐼𝐼𝑇𝑇𝑇𝑇𝑇𝑇 to display luminance 𝑫𝑫:

where 𝐿𝐿𝑚𝑚𝑚𝑚𝑚𝑚 and 𝐿𝐿𝑚𝑚𝑚𝑚𝑚𝑚 are the minimum and maximum luminance of the scene, 𝜏𝜏 = 𝛼𝛼(𝐿𝐿𝑚𝑚𝑚𝑚𝑚𝑚 − 𝐿𝐿𝑚𝑚𝑚𝑚𝑚𝑚 ), 𝛼𝛼 ≥ 0. This equation ensures that the maximum and minimum luminance values of the scene are respectively mapped to the maximum and minimum luminance of the display device. Here the range of display luminance is [0,1]. Adjusting 𝛼𝛼 will appropriately tune the overall brightness of the reproduced image. In this assignment, we set 𝛼𝛼 = 0.05.

</div>
</div>
<div class="layoutArea">
<div class="column">
𝐻𝐻=

</div>
<div class="column">
log(𝐿𝐿 + 𝜏𝜏) − log (𝐿𝐿𝑚𝑚𝑚𝑚𝑚𝑚 + 𝜏𝜏) log(𝐿𝐿𝑚𝑚𝑚𝑚𝑚𝑚 + 𝜏𝜏) − log (𝐿𝐿𝑚𝑚𝑚𝑚𝑚𝑚 + 𝜏𝜏)

</div>
</div>
<div class="layoutArea">
<div class="column">
This part is related to the function log_tonemap().

2.3.2 Durand’s operator

Beside the above two global tone mapping operators, you’ll need to implement a local tone mapping operator in this assignment. You’ll be implementing a simplified version of Durand’s operator. The steps are roughly as follows:

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
procedure 𝐻𝐻𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑤𝑤𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇(Luminace 𝐿𝐿)

1. Compute the log intensity log10(𝐿𝐿)

2. Filter that with a bilateral filter get the base layer: 𝐵𝐵𝑇𝑇𝑐𝑐𝑇𝑇𝐿𝐿𝑇𝑇𝐵𝐵𝑇𝑇𝑇𝑇 =

</div>
</div>
<div class="layoutArea">
<div class="column">
𝑏𝑏𝑇𝑇𝑏𝑏𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑏𝑏_𝑓𝑓𝑇𝑇𝑏𝑏𝑇𝑇𝑇𝑇𝑇𝑇(log (𝐿𝐿))

3. Decompose the detail layer: 𝐻𝐻𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑏𝑏𝐿𝐿𝐵𝐵𝑇𝑇𝑇𝑇𝑇𝑇 = log

</div>
</div>
<div class="layoutArea">
<div class="column">
(𝐿𝐿) − 𝐵𝐵𝑇𝑇𝑐𝑐𝑇𝑇𝐿𝐿𝑇𝑇𝐵𝐵𝑇𝑇𝑇𝑇 5. Reconstruct the luminance: 𝐻𝐻′ = 10(𝛾𝛾×𝐵𝐵𝑚𝑚𝑠𝑠𝑓𝑓𝐵𝐵𝑚𝑚𝐵𝐵𝑓𝑓𝑟𝑟+𝐷𝐷𝑓𝑓𝑓𝑓𝑚𝑚𝑚𝑚𝑓𝑓𝐵𝐵𝑚𝑚𝐵𝐵𝑓𝑓𝑟𝑟)

</div>
</div>
<div class="layoutArea">
<div class="column">
4. Compute 𝛾𝛾 =

</div>
<div class="column">
10log10 𝑐𝑐𝑐𝑐𝑚𝑚𝑠𝑠𝑓𝑓𝑟𝑟𝑚𝑚𝑠𝑠𝑓𝑓 max(𝐵𝐵𝑚𝑚𝑠𝑠𝑓𝑓𝐵𝐵𝑚𝑚𝐵𝐵𝑓𝑓𝑟𝑟)−min(𝐵𝐵𝑚𝑚𝑠𝑠𝑓𝑓𝐵𝐵𝑚𝑚𝐵𝐵𝑓𝑓𝑟𝑟)

</div>
<div class="column">
10

</div>
</div>
<div class="layoutArea">
<div class="column">
6. Compute the display luminance: 𝐻𝐻 = 𝐻𝐻′ × 10 1 max(𝛾𝛾×𝐵𝐵𝐵𝐵𝐵𝐵𝐵𝐵𝐵𝐵𝐵𝐵𝐵𝐵𝐵𝐵𝐵𝐵)

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
where 𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑐𝑐𝑇𝑇 is a user-controllable parameter. We set 𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑐𝑐𝑇𝑇 = 50.

The above part is related to the function durand_tonemap().

Since the base layer is computed by the bilateral filter, you may need to implement the filter:

</div>
</div>
<div class="layoutArea">
<div class="column">
1

𝐼𝐼 f i l t e r e d ( 𝑥𝑥 ) = 𝑘𝑘 ( 𝑥𝑥 ) � 𝑓𝑓𝑠𝑠 ( 𝑥𝑥 , 𝑥𝑥 𝑚𝑚 ; 𝜎𝜎 𝑠𝑠 ) 𝑇𝑇 𝑟𝑟 ( 𝐼𝐼 ( 𝑥𝑥 𝑚𝑚 ) − 𝐼𝐼 ( 𝑥𝑥 ) ; 𝜎𝜎 𝑟𝑟 ) 𝐼𝐼 ( 𝑥𝑥 𝑚𝑚 )

</div>
</div>
<div class="layoutArea">
<div class="column">
𝑚𝑚𝑖𝑖∈Ω

</div>
</div>
<div class="layoutArea">
<div class="column">
𝑘𝑘 ( 𝑥𝑥 ) = � 𝑓𝑓𝑠𝑠 ( 𝑥𝑥 , 𝑥𝑥 𝑚𝑚 ; 𝜎𝜎 𝑠𝑠 ) 𝑇𝑇 𝑟𝑟 ( 𝐼𝐼 ( 𝑥𝑥 𝑚𝑚 ) − 𝐼𝐼 ( 𝑥𝑥 ) ; 𝜎𝜎 𝑟𝑟 ) 𝑚𝑚𝑖𝑖∈Ω

</div>
</div>
<div class="layoutArea">
<div class="column">
where 𝐼𝐼𝑓𝑓𝑚𝑚𝑓𝑓𝑓𝑓𝑓𝑓𝑟𝑟𝑓𝑓𝑓𝑓 is the filtered image; 𝐼𝐼 is the original input image; 𝑥𝑥 are the coordinates of the current pixel to be filtered; Ω is the window centered in 𝑥𝑥, so 𝑥𝑥𝑚𝑚 ∈ Ω is another pixel; 𝑓𝑓𝑠𝑠 is the 2D Gaussian kernel (spatial kernel) for smoothing differences in coordinates, here we choose 𝜎𝜎𝑠𝑠 = 0.02 ×

min(𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇_𝑤𝑤𝑇𝑇𝑤𝑤𝑇𝑇h, 𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇_h𝑇𝑇𝑇𝑇𝑇𝑇h𝑇𝑇); 𝑇𝑇𝑟𝑟 is the 1D Gaussian kernel (range kernel) for smoothing differences in intensities, here we choose 𝜎𝜎𝑟𝑟 = 0.4. The spatial kernel size (or the window size) can be computedas𝑐𝑐𝑇𝑇𝑠𝑠𝑇𝑇=2×max(𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑤𝑤(1.5𝜎𝜎𝑠𝑠),1) +1.

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
The above part is relate to bilateral_filter(). You are allowed to use a bilateral filter from some third- party libraries. In that case, you can just put your function invocation inside the function body of bilateral_filter(). If you choose to implement the bilateral filter by yourself, you will get some extra bonus points.

</div>
</div>
<div class="layoutArea">
<div class="column">
2.4 MappingLuminance

</div>
</div>
<div class="layoutArea">
<div class="column">
Since the desired result is an RGB image, we need to map the display l𝐻𝐻𝐿𝐿uminance 𝑫𝑫 to the color space. Conventionally, we can scale the RGB values of 𝐻𝐻𝐻𝐻𝐻𝐻_𝐼𝐼𝐼𝐼𝑇𝑇𝑇𝑇𝑇𝑇 by 𝐷𝐷𝐵𝐵 to get the 𝐿𝐿𝐻𝐻𝐻𝐻_𝐼𝐼𝐼𝐼𝑇𝑇𝑇𝑇𝑇𝑇:

</div>
</div>
<div class="layoutArea">
<div class="column">
𝐶𝐶h𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑏𝑏𝑚𝑚𝑚𝑚𝑖𝑖𝑖𝑖𝑓𝑓 = 𝐶𝐶h𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑇𝑏𝑏𝑐𝑐𝑖𝑖𝑓𝑓𝑖𝑖𝑖𝑖𝑓𝑓 ×

where 𝑳𝑳 is the luminance of the 𝐻𝐻𝐻𝐻𝐻𝐻_𝐼𝐼𝐼𝐼𝑇𝑇𝑇𝑇𝑇𝑇. This part is related to the function map_luminance().

</div>
</div>
<div class="layoutArea">
<div class="column">
2.5 Summary

In this assignment, you are required to implement tone mapping in Python 3.4+. In order to make the skeleton code functional, you need to complete these four functions in the skeleton code: map_luminance(), bilateral_filter(), log_tonemap(),durand_tonemap().

The skeleton code depends on OpenCV and Numpy. You are allowed to import third-party libraries into the code. However, you are not allowed to directly use tone mapping operator from these libraries.

Moreover, you can find some HDR images in the test_images directory. Tone mapped images will be generated in the output directory.

3 Submission guidelines

You need to submit the completed tone_mapping.py to the Blackboard. 3.1 Marks

</div>
</div>
<div class="layoutArea">
<div class="column">
<ul>
<li>map_luminance():</li>
<li>log_tonemap():</li>
<li>durand_tonemap():</li>
<li>bilateral_filter():</li>
</ul>
</div>
<div class="column">
10 points

30 points

60 points

extra 20 bonus points if you implement this filter by yourself

</div>
</div>
<div class="layoutArea">
<div class="column">
(with pure Python and Numpy)

3.2 Putpersonalinformationinyoursourcecode

In your source code file, type your full name and student ID, just like:

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
#

# CSCI3290 Computational Imaging and Vision *

# — Declaration — *

# I declare that the assignment here submitted is original except for source # material explicitly acknowledged. I also acknowledge that I am aware of

# University policy and regulations on honesty in academic work, and of the

# disciplinary guidelines and procedures applicable to breaches of such policy # and regulations, as contained in the website

# http://www.cuhk.edu.hk/policy/academichonesty/ *

# Assignment 3

# Name:

# Student ID:

# Email Addr:

#

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
</div>
