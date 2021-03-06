# School Notebooks

## Setup

1. Clone the _tslab-notebook_ repository
```bash
git clone https://github.com/nemo-omen/tslab-notebook.git my_notebook_dir
```
2. cd into the directory and start the build (this part might take awhile)
```bash
cd my_notebook_dir && docker-compose up
```
When the above is finished the cli will present you with a URL. Open the URL in your browser and _voila_, you will be in your new JupyterLab environment.

This environment includes the Github plugin. That's where you need to handle saving individual notebook directories to github or wherever you want to keep repos.

In my case, of course, it's this repo!

[TSLab - Getting started for JS users](https://nbviewer.jupyter.org/github/yunabe/tslab-examples/blob/master/notebooks/getting_started_javascript.ipynb)


When inside the notebook environment, you should be able to install npm packages, pip packages, etc with the included terminal.

Personally, I like to install pnpm first:

```bash
npm install -g pnpm
```

Then, whatever charting libraries I might use or need

```bash
pnpm install d3 echarts
```
