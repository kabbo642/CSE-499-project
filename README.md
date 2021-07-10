# Image Captioning
![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)


We went through the paper Pyramid Scene Parsing Network and learned about the PSP network and how it works.
The main goal of our project model is to assign each pixel of an image in a category label. This network provides a complete understanding of the scene. It predicts the label, location as well as shape of each element in the image.
Difficulty of this network's computational work depends on the scene and label variety.

This kind of semantic segmentation network works by having two parts: an encoder and a decoder. The encoder is responsible for extracting features from the scene and the decoder predicts the labels of the different segments of the scene. 
Some key characteristic of the PSPNet, which we discovered so far is:
# CNN backbone
# Dilated convolutions
# pyramid pooling.
For implementing this kind of network we need an API called arcgis.learn.
https://developers.arcgis.com/python/api-reference/arcgis.learn.toc.html
A another API is Deeplab.
https://chainercv.readthedocs.io/en/stable/reference/links/deeplab.html


[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
