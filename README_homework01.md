README_homework01.md
# Homework 01 README.md file
#### Tools for Computational Biology
#### Morgan Raimondo

This file explains the contents of the `tfcb-homework01` respository while demonstrating examples for headers, lists, links, embedded images, and tables using Markdown formatting. The following sections include how to format a document using markdown language. The repository can be found here: [link](https://github.com/MorganRaimondo/tfcb-homework01.git). All files submitted for homework are within the `tfcb-homework01` folder on GitHub.

## Folders

This directory contains a `messy-project-directory` master folder with all the contents except the "README.md" files. There are 3 folders: 
- code
- data
- images

### Code Folder
 
This folder includes all the python scripts needed related to this project.

### Data Folder

This folder contains both raw and cleaned data related to this project. The original raw data is in the document `Survey_data.xlsx` while the cleaned, tidydata is in the document `Survey_data_tidydata.tsv`. There is an Excel version of this file in this folder, titled `Survery_data_tidydata.xlsx`.

### Images Folder

This folder contains all the images related to the project.

| Organism            | Image Link |
----------------------|------------|
|*Acanthomyrmex ferox*| ![Acanthomyrmex ferox](messy-project-directory/images/Acanthomyrmex_ferox.jpg) |
|*Camponotus darwinii* | ![Camponotus darwinii](messy-project-directory/images/Camponotus_darwinii.jpg) |
|*Cataglyphis fortis* | ![Cataglyphis fortis](messy-project-directory/images/Cataglyphis_fortis.jpg)|
|*Rhytidoponera metallica* | ![Rhytidoponera metallica](messy-project-directory/images/Rhytidoponera_metallica.jpg)|

## Headers

Headers are populated when a "#" symbol is at the front of a line of code. Then, after a space, the text following will display header formatting until the "Enter" button is pushed.

There are several layers of headers; the more "#" symbols in front, the smaller the header

# Header 1
## Header 2
### Header 3
#### Header 4
...etc.

## Lists

You can make lists by putting the "-" symbol in front of your list item followed by a space.

- Item 1
- Item 2
- Item 3

## Links

A link can be included in a Markdown file by putting the link within "()" parentheses. If you want to use text to be a link, you put "[]" brackets before the parentheses with no spaces in between.

This is how you embed a link alone: (https://github.com/MorganRaimondo/tfcb-homework01.git)

This is how you embed a link with text: [Morgan's tfcb-homeowork01 repository](https://github.com/MorganRaimondo/tfcb-homework01.git)

## Images

The syntax for including images in Markdown includes a "![]" symbol in the front of the image link, followed by the title of the image in parentheses.

*Note*: The pathway needs to be included to open this image. Be sure to be in the messy-project-directory directory of this tfcb-homework01 repository.

Below is the image "Acanthomyrmex_ferox.jpg"

![Acanthomyrmex ferox](messy-project-directory/images/Acanthomyrmex_ferox.jpg) 

## Tables

To create a table, you have to create the table headers first, followed by the "|" after each. Then, the header row is finished with "-" symbols creating the lines of the table.

| column 1 | column 2 | column 3 | column 4|
|----------|----------|----------|---------|
| row 1    | row 1    | row 1    | row 1   |
| row 2    | row 2    | row 3    | row 4   |