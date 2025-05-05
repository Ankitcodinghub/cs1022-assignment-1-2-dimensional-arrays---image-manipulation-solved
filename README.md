# cs1022-assignment-1-2-dimensional-arrays---image-manipulation-solved
**TO GET THIS SOLUTION VISIT:** [CS1022 Assignment #1 2-Dimensional Arrays – Image Manipulation Solved](https://www.ankitcodinghub.com/product/cs1022-assignment-1-2-dimensional-arrays-image-manipulation-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95704&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;&nbsp;CS1022&nbsp;Assignment #1 2-Dimensional Arrays – Image Manipulation Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Introduction

In each of the template μVision projects accompanying this assignment, an image of the (old) TCD crest has been stored in memory using an RBG (Red Green Blue) colour model. The image is stored as a two-dimensional array of word-size values. Each word-size value corresponds to a single pixel in the image. The Blue, Green and Red components of a pixel are stored in bytes 0, 1 and 2 of the word-size value respectively (with byte 0 being the least-significant byte and byte 3 being the most significant byte). Byte 3 (the most significant byte) is not used and is always zero.

You are asked to design, write and test three subroutines to manipulate the image stored in memory. In each case, your solution must make use of further subroutines and must demonstrate problem decomposition.

A number of other subroutines are provided to assist you and the labels and interfaces for these subroutines are shown in Table 1.

Part 1 – Brightness and Contrast

The brightness of the pixels in an image can be increased (or decreased) in a simple manner by adding a positive (or negative) constant value to the red, green and blue components of each pixel of the image. Similarly, the contrast can be adjusted in a simple manner by multiplying the red, green and blue components of each pixel by a constant value.

The formulae below express how the Red (R), Green (G) and Blue (B) components of a pixel at coordinates i,j might be be modified to change brightness (β) and contrast (α). Note that the

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
subroutine label interface

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
getPicAddr

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<pre>; getPicAddr subroutine
; Returns the starting address of an image stored in memory
; Parameters    none
; Return values R0: starting address of image
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
getPicWidth

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<pre>; getPicWidth subroutine
; Returns the width in pixels of an image stored in memory
; Parameters    none
; Return values R0: width in pixels
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
getPicHeight

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<pre>; getPicHeight subroutine
; Returns the height in pixels of an image stored in memory
; Parameters    none
; Return values R0: height in pixels
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
putPic

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<pre>; putPic subroutine
; Displays the image stored in memory on the LCD
; Parameters    none
; Return values none
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Table 1: Subroutine interfaces

contrast is decreased if α &lt; 16, increased if α &gt; 16 and is unchanged if α = 16.

′ 􏰈Ri,j ×α􏰉

Ri,j = 16 +β

′ 􏰈Gi,j ×α􏰉

Gi,j = 16 +β

′ 􏰈Bi,j ×α􏰉

Bi,j = 16 +β

Design, write and test an ARM Assembly Language subroutine that will adjust the brightness and contrast of the TCD crest image stored in memory. Take care to handle cases where the adjustment causes the value of the red, green or blue components to exceed 255 (or fall below 0).

Part 2 – Blur Effect

A “motion blur” effect can be applied to an image in a simple way by replacing the Red, Green and Blue values of each pixel with the average of the corresponding colour channels from the pixels in a line through each pixel. For example, in Figure 1 below, the pixel marked 􏰊 is replaced with the average colour of the diagonal line of shaded pixels. (Note that the original pixel marked 􏰊 is also included in the average.)

The “blurriness” of the resulting image is determined by the radius of the effect, r, in pixels. In the example in Figure 1, the radius is 5 pixels. The image in Figure 2 illustrates the effect on the TCD crest.

Alternatively you can try any other type of blur that you want. The only stipulation is that the

</div>
</div>
<div class="layoutArea">
<div class="column">
Page 2 of 4

Figure 1: The shaded pixels are used to compute the new value of the pixel marked 􏰊.

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Figure 2: Motion blur effect applied to the TCD crest.

output value of a pixel must depend on the input of at least 1 pixel other than itself. Some possibilities are Gaussian blur, posterisation , pixelisation.

Design, write and test an ARM Assembly Language subroutine that will apply a motion blur effect parallel to a diagonal line from the top-left to the bottom-right of the image (or other blur effect). Test your effect using different radii.

Part 3 – Bonus Effect

Design, write and test a subroutine that will apply an effect of your choice to the TCD crest image stored in memory. Try to choose an effect that requires each pixel to be replaced with a value based on other pixels. (The blurring effect above replaces each pixel with a value based on other pixels but the brightness effect above does not.) Marks will be awarded for the quality of your solution and also its sophistication. (More complex effects will attract more marks.) Examples of more complex effects include: (i) sharpening, (ii) another type of blurring, (iii) edge detection, (iv) unsharp masking or (v) generic application of a convolution matrix (vi) lens effect.

Documentation

You are required to document your approach to the development of all three subroutines. Your documentation should be in the form of a typed document in PDF format. This document must be submitted with your assembly language .s source files.

Your report must contain a detailed description of your approach to developing your solution.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
◆

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Page 3 of 4

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Your description should make use of examples, diagrams and pseudo-code (properly formatted) where appropriate. You must provide a description of the interface for each subroutine that you write. Avoid writing a narrative that simply describes what each instruction in your program does. Instead, try to describe how your program works at a higher level. Concentrate on the approach that you have taken, not the minute details of the assembly language.

The nature of this assignment means that your subroutines cannot be tested with different input values (in most cases). You should instead simply insert a photograph of the output displayed on the LCD screen for each subroutine and explain whether the image was as expected and, if not, try to explain this.

Note that marks will be awarded for both the content and presentation of your document and will account for 25% of the overall marks available for the assignment.

</div>
</div>
</div>
