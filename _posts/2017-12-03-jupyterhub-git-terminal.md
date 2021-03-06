---
layout: post
title: Liking JupyterHub but missing git 
---

Firstly I am a bit torn about Jupyter / JupyterHub. On one side, jupyter notebooks are great for 
turning out beautiful tutorials and across two of [our](http://paradigm4.com) key interface languages e.g. I used it for creating R tutorials 
during the [HMS hackathon](https://hms-dbmi.github.io/hackathon-Sept2017); other folks at our company have made great python 
tutorials for customers. 

However when I try to use it for collaboration with another data-scientist, I find the code sharing mechanism very inefficient, and to be me in-my-way rather than enabling collaboration. Mainly, I miss the fact that jupyter notebooks have no meaningful diff feature. 
Git version tracking is almost useless (versions can be maintained -- but without the diff, 
it is near impossible to track changes). 
Other companies ([link](https://kyso.io/)) seem to be thinking about the version tracking issue. 

To summarize, it feels like jupyterhub is great for writing solo code, but you better rely on 
something with more native git integration if you want to collaborate. 

Today I found that jupyterhub does [allow terminal access](https://stackoverflow.com/questions/34941546/is-there-a-way-to-integrate-git-with-jupyter-and-have-a-version-control-over-the) (which is a great relief):

Either way, these notebooks appear to be a standard thing these days. Many folks are getting into the business of 
creating notebooks that embed code and results
- [Azure](https://notebooks.azure.com/)
- [Google](https://cloud.google.com/datalab/)
- [Spark notebooks](https://zeppelin.apache.org/) (a data-scientist at Amazon says this is the new hot thing there -- mainly because of the native spark connection)
...

Speaking of competition in this space, there was recently some [interesting twitter chatter](https://twitter.com/jakevdp/status/923936168521097216) 
comparing different options on a thread started by our scidbpy 1.0 creator Jake Van der Plas . Azure is criticized. Many other players are mentioned. 

Seems to be an interesting space to watch out for. 
