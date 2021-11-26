# DCT-IDCT-on-bmp-image
Compressing a bmp image using discrete cosine transform and uniform quantization

# Steps
<ol>
  <li>The bmp image was converted to ycbcr format and then the y was taken to perform compression</li>
  <li>the image was partitioned into uniform blocks of 8*8 matrices</li>
  <li>Each matrix was transformed using Discrete cosine transform</li>
  <li>Each DCT matrix was quantised using coefficient quantisation</li>
  <li>Inverse DCT was applied on the quantised matrices to obtain the compressed image</li>
 </ol>
 
# Final Output

![image](https://user-images.githubusercontent.com/84259402/143593569-ea48105d-49cd-41bc-9994-5a0be5e33ec6.png)


