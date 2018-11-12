# techbridge_datascience

Run me in the browser! [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/wesleybeckner/techbridge_datascience/master)

Interactive datascience lessons for the Techbridge Girls program

You can learn more about the underlying algorithms at Google AI's [Teaching Machines to Draw](https://ai.googleblog.com/2017/04/teaching-machines-to-draw.html) and Dan Macnish's [Draw This](https://danmacnish.com/2018/07/01/draw-this/)

## Install

You can setup the environment to run these lessons locally using [conda](https://conda.io/docs/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file) and the envrionment.yml file:

```
conda env create -f environment.yml
```

[magenta](https://github.com/tensorflow/magenta#installation) depends on a `rtimidi` package that may require manual install of headers for some sound libraries on your local system. On Linux:

```
sudo apt-get install build-essential libasound2-dev libjack-dev
```


