*Compress a Image using K-means clustering Algorithm(implemented from scratch).*

![image](https://user-images.githubusercontent.com/52378401/156026087-3b3843ae-05d2-467a-9290-9a728629b847.png)

In this example I used 16 clusters and ran the algo for 10 iterations.<br>
Originally in a image there are many colours and a pixel is represented by 3 8-bit integers that specify RGB intensity values also known as RGB encoding. Using this algorithm the number of colours are reduced to 16(no. of clusters) so that we only need to store the RGB values of this 16 colours only and for each pixel we only need to store the index of nearest cluster at that location(4 bits for 16 colours) which reduces the size of image.
