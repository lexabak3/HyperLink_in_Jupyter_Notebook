# HyperLink_in_Jupyter_Notebook
[This notebook](https://github.com/lexabak3/HyperLink_in_Jupyter_Notebook/blob/main/HyperLink_in_Jupyter.ipynb) is an instruction on how to use hyperlinks to build a table of contents in a Jupyter notebook.



add <a class="anchor" id="line_1"></a> 
to your title (Markdown Cell) like:
````
# Example of title N1 <a class="anchor" id="line_1"></a>
## Example of title N2 <a class="anchor" id="line_3"></a>
...
````

Then add your Content Table in formst of hyprtlink [text](link): 
````
* [Title N1](#line_1)
* [Title N2](#line_2)
* [Title N3](#line_3)
*  ...
````

Done (This works when opened locally on your computer)
