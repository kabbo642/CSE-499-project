# Model_Pruning
![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)

We got to know about pruning from " Proving the lottery ticket hypothesis: Pruning is all you need " authord by Eran Malach, Gilad Yehudai, Shai Shalev-Schwartz, Ohad Shamir. Pruning techniques can reduce the parameters counts of trained network by 90%. With this technique storage requirements can be decressed as well as the computational performance can be improved along with having the same accuracy as a fully trained model. But this has some downsides as well. For example produced sparse architecture are different to train from start and these networks can not be trained from scratch. There is an package called neuralmagic can help us apply the pruning on our model. If this technique is implemented appropriately then we believe that we can reach our goals.

## Our goals:
* Network with reduced parameters.
* Has application in multiple fields.
* Certain algorithm for different type of datasets.



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
