# MLA'18 Twitter analysis and wordcloud generation
In this repository is the code I have been using to generate the graphs and wordclouds associated with the 2018 Medical Library Association annual conference in Atlanta, GA

I have been hacking this together over a number of conferences, and over a period of time. By request, I am sharing it here for the enlightenment and curiosity of others. I have attempted to clean it up a little bit, and add some cursory comments to help people understand which parts are doing what. However, this is not intended to be a tutorial, nor do I claim a deep understanding of every element of what I utilize here. I am only beginning my journey with Natural Language Processing. 

So to anyone who ventures below: Thanks for having a look! I always welcome advice and suggestions from peers and veterans, so feel free to contribute, or shoot me an email. 

Cheers and regards!

Peter

```
Peter Oxley, PhD
Associate Director of Research Services

Weill Cornell Medicine
Information Technologies and Services
Samuel J. Wood Library & C.V. Starr Biomedical Information Center
1300 York Avenue Room D-120
New York, NY 10065-4896
(P) 646-962-2576
 
pro2004@med.cornell.edu
```

## Getting started
This was originally run in a Jupyterlab notebook. For those interested in giving it a go:

1. Download this notebook from https://github.com/oxpeter/mlanet18_twitter/archive/master.zip

2. Unzip the folder that downloads

1. Download Anaconda from https://www.anaconda.com/download/ (select your operating system, then click 'Download'

2. Run the Anaconda installer you just downloaded. When it asks which version of Python to install, select 3.6 (or higher)

3. Open Anaconda

4. Open Jupyterlab (click 'Launch')

5. In Jupyterlab, on the left-hand "Files" panel, navigate to where you downloaded this notebook folder

6. The notebook should now load!

7. You will need to install a number of extra modules for this notebook to run. You can do so in Anaconda by: 
    1. clicking on the Environments panel on the left
    2. selecting "all" instead of "installed" modules
    3. searching for the modules in the right panel 
    4. selecting the check box next to each module name
    5. clicking "apply" in the bottom right
    6. it will tell you all the modules (and their dependencies) it wants to install. Click 'OK'
    
8. An alternative means of installing is to use the terminal, with the command:
    ```conda install module1 module2 module3```
    
You will need to install the following modules (Anaconda will already have installed some of these by default):

* pandas
* numpy
* matplotlib
* seaborn
* pillow
* nltk
* 

### Using Python in Jupyterlab
This Jupyter notebook has been built to run on a python 3 'kernel'. That means you can enter python code into the code cells, and it will be able to execute as python.

To execute code, select the cell(s) by clicking inside, then either:

* Choose "Run Selected Cells" from the Command tab on the left
* Click the run button (triangle) at the top of the notebook
* Press "Shift + Enter"
