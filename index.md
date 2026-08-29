
* TOC
{:toc}

<image src="myExampleScenes/nested_sphere.png" style="width: 90%;"></image>
This image can be rendered by running `.\a.exe .\myExampleScenes\nested_sphere.txt` in the command line with the project folder as the working directory. This is a scene file I wrote which includes four spheres, the three in the center overlap and the one on the left does not. It is lit by three spot lights, two are white and point from the top and bottom left towards the scene, and one is purple pointing from the top right. This image is a great example of refraction. The large sphere in the middle has an index of refraction of 1, the same as the air, which is why the images of the two spheres inside of it are not distorted. The inner right sphere has an IOR of 1.3, which causes the image of the left sphere intersecting it to distort. We can also see the parameters of spot lights at work here, as the top left spotlight has a much smaller inner cone of light (5 degrees) with less of an angle of gradual falloff (10 degrees) than the other two, which have inner angles of 45 degrees and outer angles of 60 and 90 degrees.


# Project Files
You can view the files on github <a href="https://github.com/mandywyllie/CSCI5607Project3B/">here</a>, or download the project zip <a href="https://github.com/mandywyllie/CSCI5607Project5/blob/main/project5graphics.zip">here</a>.

