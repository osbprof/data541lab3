# Embedding Images in GitHub Markdown #
---
GitHub Markdown has several options for embedding images. One of the most straight foward is using Markdown version of the image embed:

![UBC Okanagan](https://brand3.sites.olt.ubc.ca/files/2018/09/5NarrowLogo_ex_768.png)
Logo link: https://brand3.sites.olt.ubc.ca/files/2018/09/5NarrowLogo_ex_768.png

# Adding YouTube Videos #
---
They can't be added directly but you can add an image with a link to the video like this:
```
<a href="http://www.youtube.com/watch?feature=player_embedded&v=Efw6CUY5lbE " target="_blank"><img src="http://img.youtube.com/vi/Efw6CUY5lbE/0.jpg" alt="President's Community Update" width="240" height="180" borders="10" /></a>
```
Or, in pure Markdown, but losing the image sizing and border:

`[![President's Community Update](http://img.youtube.com/vi/Efw6CUY5lbE/0.jpg)](http://www.youtube.com/watch? v=Efw6CUY5lbE)`

Click on the image to play the video:
![President's Community Update](http://img.youtube.com/vi/Efw6CUY5lbE/0.jpg)









