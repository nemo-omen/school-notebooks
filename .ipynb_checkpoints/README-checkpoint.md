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