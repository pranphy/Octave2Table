Octave2Table
============
> Convert Octave and Matlab arrays to Latex table.

This package generates Latex table codes to be used in Latex document from the
arrays in matlab. We often generate plot from sample values and generate plots.
There are packages to generate `tikz` images from matlab plots but there   are
no similar packages to generate table.

This package does exactly the same

Usage
=====
Generate latex table from  Octave/Matlab arrays which can be used in documents.

Installation
============
Clone this repo  `https://github.com/pranphy/Octave2Table.git/`

```
    cd /installation/directory/
    git clone https://github.com/pranphy/Octave2Table.git
```
Simply put this in your `~/.octaverc`

```
    path.set([path.get() 'installation/directory/')
```

Examples
========
It can be used in the following in the matlab or octave code.

```
    t = 1:10
    x = t .^ 2
    Octave2Table(t,x,'Time','intensity')
```
