# Resources

### Problem set solutions
* [Problem set 1 solution](https://github.com/varnerlab/CHEME-7770-Cornell-S19/tree/master/src/PS1)
* [Problem set 2 solution](https://github.com/varnerlab/CHEME-7770-Cornell-S19/tree/master/src/PS2)
* [Problem set 3 solution](https://github.com/varnerlab/CHEME-7770-Cornell-S19/tree/master/src/PS3)

### Prelim 1 solutions
* [Prelim 1 solutions](https://github.com/varnerlab/CHEME-7770-Prelim-1-Solution-S19)

### How do we do basic Flux Balance Analysis (FBA) calculations?
The [COBRA toolbox](https://opencobra.github.io/cobratoolbox/stable/) is a great resource for doing these calculations (and much much more) in [MATLAB](https://www.mathworks.com/products/matlab.html). We have also created a [Julia](https://julialang.org) wrapper called [Flux.jl](https://github.com/varnerlab/CHEME-7770-Cornell-S19/tree/master/src/PS3/Flux.jl), which uses [GLPK](https://github.com/JuliaOpt/GLPK.jl), to do basic FBA calculations.

### Ordinary Differential Equations (ODEs) example
* [Mike Vilkhovoy's guest lecture example](https://github.com/mvilkhov/ODE-Example) code (in Julia and Matlab).


### Custom packages:
* [Gene regulatory network simulation kit (GRNSimKit)](https://github.com/varnerlab/GRNSimKit.git) is a
[Julia package](https://docs.julialang.org/en/v1/stdlib/Pkg/index.html) for simulating simple gene regulatory networks.
GRNSimKit uses a [JSON](https://github.com/JuliaIO/JSON.jl.git) model specification. Check out the [GRNSimKit docs](https://varnerlab.github.io/GRNSimKit/).
* [Core Ecoli Model Kit (CoreEcoliModel)](https://github.com/varnerlab/CoreEcoliModelKit.git) is a [Julia package](https://docs.julialang.org/en/v1/stdlib/Pkg/index.html) for doing flux balance analysis (and other constraint based modeling) calculations. Check out the [CoreEcoliModelKit docs](https://varnerlab.github.io/CoreEcoliModelKit/)

### Julia resources:
Are you new to [Julia](https://julialang.org)? [Download the latest version](https://julialang.org/downloads/) and checkout the Julia [documentation](https://docs.julialang.org/en/v1/) and [tutorials](https://julialang.org/learning/) to get started. If you don't want to run Julia locally, then checkout [JuliaBox, it's a hosted alternative in the cloud](https://juliabox.com).

### GitHub resources:
Never used [GitHub](https://github.com) before? Checkout out the [GitHub help pages](https://help.github.com), the [GitHub tutorials](https://www.youtube.com/githubguides) or the [GitHub Learning Lab](https://lab.github.com) for help getting started.

### Text editors:
* [Atom](https://atom.io) is a cross-platform text editor that can be configured as a Julia editor/Integrated Development Environment (IDE) by
downloading the appropriate package. [Atom](https://atom.io) can also be used with many other common technical and general computing languages e.g., [Python](https://www.python.org), MATLAB or [Octave](https://www.gnu.org/software/octave/), C/C++, PHP, [Javascript/Typescript](https://www.typescriptlang.org), etc.
* [Juno](http://junolab.org) is a dedicated [Julia](https://julialang.org) editor that is built on top of [Atom](https://atom.io). [Juno](http://junolab.org) allows you to run the Julia REPL inside Atom (instead of a separate window), and gives access to the debugger and other tools.  
* [Visual Studio Code](https://code.visualstudio.com) is a free cross-platform text editor from [Microsoft](https://www.microsoft.com/en-us/)
that can be used for [Julia](https://julialang.org) development, and for many other technical or general computing languages e.g., [Python](https://www.python.org), MATLAB or [Octave](https://www.gnu.org/software/octave/), C/C++, PHP, [Javascript/Typescript](https://www.typescriptlang.org), etc.


### Biological databases and other resources:
* [PubMed](https://www.ncbi.nlm.nih.gov/pubmed/) is an online literature database holding research articles and books.
PubMed holds more than 29 million citations for biomedical literature from [MEDLINE](https://www.nlm.nih.gov/bsd/medline.html),
life science journals, and [online books](https://www.ncbi.nlm.nih.gov/books/).
* [Bionumbers](https://bionumbers.hms.harvard.edu/search.aspx) is a literature database which can be searched for useful quantitative numbers, e.g., [how many Ribosomes are there in an _Escherichia coli_ cell ?](https://bionumbers.hms.harvard.edu/search.aspx?trm=ribosomes+in+E.+coli)
* [KEGG](https://www.kegg.jp) is a metabolic reaction database with reaction information for several important organisms.
* [BRENDA](https://www.brenda-enzymes.org) is an enzyme kinetics database that holds a collection of experimentally measured kinetic parameter values.
* [eQuilibrator](http://equilibrator.weizmann.ac.il) is a thermodynamics database that can be used to calculate the [Gibbs energy of formation](https://en.wikipedia.org/wiki/Standard_Gibbs_free_energy_of_formation), and the [Gibbs energy of reaction](https://en.wikipedia.org/wiki/Gibbs_free_energy#Gibbs_free_energy_of_reactions) for metabolic reactions.  
* [RegulonDB](http://regulondb.ccg.unam.mx) is a [transcription factor](https://en.wikipedia.org/wiki/Transcription_factor) database that holds both experimentally and computationally derived regulatory networks primarily in [_Escherichia  coli_ K-12](https://en.wikipedia.org/wiki/Escherichia_coli_in_molecular_biology#K-12).
* [The Palsson group](http://systemsbiology.ucsd.edu/Researchers/Palsson) at [UCSD](https://ucsd.edu) is a great resource that we'll use throughout the course. Checkout the on-line [SYSTEMS BIOLOGY: Constraint-based Reconstruction and Analysis lectures](http://systemsbiology.ucsd.edu/Publications/Books/SB1-2LectureSlides).
