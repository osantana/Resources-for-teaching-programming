----

# Resources for teaching programming
# for artists, designers and architects ([repository](https://github.com/villares/Resources-for-teaching-programming/))

### Extended table of Hosts, Platforms & Languages
> - Drawing or 3D modeling software that embeds a scripting language on the user interface or allows automation with a very limited number of steps between programming and code execution.
> - Tools aimed at teaching programming in a visual or graphic context.
> - [Ad hoc: tools that have shown potential for teaching in a visual or graphic context.]

| | | | 
| --- | --- | --- |
| [**SORTABLE VIEW OF THE TABLE**](http://villares.github.io/csv-to-html-table/host-platforms-and-languages)| [CSV on GitHub](https://github.com/villares/Resources-for-teaching-programming/blob/master/I%20-%20Host%20platforms%20%26%20languages.csv) | [raw CSV](https://raw.githubusercontent.com/villares/Resources-for-teaching-programming/master/I%20-%20Host%20platforms%20%26%20languages.csv) |

An earlier version of this table was published as: *VILLARES, A. B. A., & MOREIRA, D. (2017). [**Python on the Landscape of Programming Tools for Design and Architectural Education**](https://villares.github.io/mestrado/VILLARES_MOREIRA_SIGRADI_2017). Presented at the SIGRADI 2017, Concepcíon, Chile.*

### Processing + Python tools table

| Name | Processing features | based on (& Python version) | Python standard library | libraries ecosystem | main features | main limitations |
| --- | --- | --- | --- | --- | --- | --- |
[Processing Python Mode](https://py.processing.org) | [Processing Java](https://processing.org) | [Jython](https://www.jython.org/) (Python 2) | complete | Java & Processing Java | available inside Processing IDE, very Processing compatible | no web deployment, no modern Python libs |
[p5py](https://github.com/p5py/p5) | a new inplementation (incomplete) |  Python 3 | complete | Python only | truly Python compatible | no web deployment, still incomplete, new names (for those used to Processing) |
[pyp5js](https://github.com/berinhard/pyp5js) (transcrypt mode) | [p5.js](https://p5js.org/) | [Transcrypt](https://transcrypt.org/documentation) (Python 3) | incomplete | JavaScript & p5.js |  web ready sketches, very p5js compatible and nice browser editor| JS libraries only, p5.js features only (compared to Processing Java/Python modes) |
pyp5js (pyodide mode)| [p5.js](https://p5js.org/) | [Pyodide](https://luxapodular.github.io/Py5.js/) (Python 3) | complete | Python, JavaScript & p5.js |  web ready sketches! very p5.js compatible & very Python compatible | [Experimental](https://berinhard.github.io/pyp5js/pyodide/), p5.js features only (compared to Processing Java/Python modes) |
[SkulptIDE](http://esperanc.github.io/skulptIde/pages.html) and [trinket.io](https://trinket.io/processing) | [ProcessingJS](http://processingjs.org/) | [Skulpt](http://skulpt.org/) (Python 2, going to 3 now) | partial | unknown, possibly JavaScript |  very nice web IDE, browser based sketches | ProcessingJS is defunct; not extensible
[BrythonIDE](https://esperanc.github.io/brythonide/) and [p5py.com](http://p5py.com/)  | [p5.js](https://p5js.org/) | [Brython](https://brython.info/) (Python 3) | [fairly complete](https://brython.info/static_doc/en/stdlib.html) | JavaScript & p5.js |  browser IDE, browser based sketches & very p5.js compatible | p5.js features only (compared to Processing Java/Python modes)  |
[py5](http://py5.ixora.io/) | based on Processing 4 + JPype |  Python 3 | complete | Python & Java | truly Python compatible, can be used on Jupyter notebooks, compatible with Processing Java | still experimental, new names (for those used to Processing) |


### Other FLOSS + Python options to explore

##### 3D 

- [FreeCAD](https://freecadweb.org) (also 2D if you want)
- [CADQuery](https://github.com/CadQuery/cadquery) & [CQ-Editor](https://github.com/CadQuery/CQ-editor)
- [Blender](https://blender.org)
- [OpenPySCAD](https://github.com/taxpon/openpyscad), [SolidPython](https://github.com/SolidCode/SolidPython) and [PythonOpensCAD](https://www.bvcw.org/)
- [PyPlasm](http://www.plasm.net/download/)

##### 2D

- [ShoeBot](https://shoebot.github.io/) - related to the DrawBot/NodeBox1/PlotDevice family of tools
- [PageBot](https://github.com/PageBot/PageBot) 
- Flat + Allison Parrish's [Bezmerizing](https://github.com/aparrish/bezmerizing/blob/master/demo.ipynb)
- [Pero](https://github.com/xxao/pero) - unified API for multiple drawing backends 
- [generativepy](https://www.pythoninformer.com/generative-art/generativepy/) - Based on PyCairo


### Books and references

- [Think Python 2e]() EN / [Pense em Python 2e]() PT
- [Processing.py in Ten Lessons – Resources](https://tabreturn.github.io/code/processing/python/2021/04/16/processing.py_in_ten_lessons-resources.html) EN
- [Introdução à programação
com Python em um contexto visual](https://abav.lugaralgum.com/material-aulas/) PT

----

**Please consider feedback, colaboration by means of pull requests, and/or a small [donation](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=HCGAKACDMVNV2)!**

----

Copyright (c) 2014-2017 [Alexandre B A Villares](https://abav.lugaralgum.com). This work is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License. [CC-BY-NC-SA-4.0 License](https://creativecommons.org/licenses/by-nc-sa/4.0/)
