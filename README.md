# Markdown to PDF command line converter

## Pre-requisites

### Pandoc 

Download link : [https://github.com/jgm/pandoc/releases/tag/2.4](https://github.com/jgm/pandoc/releases/tag/2.4)

### wkhtmltopdf

Link to website: [https://wkhtmltopdf.org/](https://wkhtmltopdf.org/)

#### Linux 
Install through terminal : `sudo apt-get install wkhtmltopdf` 

#### Windows
Download and install the .msi : [https://wkhtmltopdf.org/downloads.html](https://wkhtmltopdf.org/downloads.html)

Then add install location `C:\Program Files\wkhtmltopdf\bin` to system **Path**.

## Installation

Download zip or clone this project: `git clone git@github.com:RoxaneKM/markdown-to-pdf.git`

### Linux 
For ease of use, open your .bashrc file :
`sudo gedit ~/.bashrc`

And create an alias : 
`alias='~/path-to-script-folder-location/mdtopdf/'`

### Windows
For ease of use, add path to executable (example: `D:\Scripts\markdown-to-pdf\`) in system **Path**.

## How to use

Run in terminal: 
`mdtopdf my_markdown.md result.pdf`  

**Note:** First and second parameters are mandatory (in the example above, default css used will be gitlab style).

To use you own css file, add your stylesheet to the *styles* folder. 

And run this command in the terminal :
`mdtopdf my_markdown.md result.pdf my_awesome_stylesheet.css` 

## Stylesheets

The current default stylesheet is gitlab.css that I did to be as close as possible to the gitlab styling. However, the stylesheet is not yet complete and will be completed soon.

If you want to add a stylesheet of your own add it to the styles folder.

## Author

* [RKM](https://github.com/RoxaneKM) - Initial work







