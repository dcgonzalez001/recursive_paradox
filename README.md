recursive_paradox
=================

About
-----

This website skeleton is intended for use with GRID CSS and HTML5 Semantic Tags. It maintains responsiveness by being built mobile-first with media queries being added to enhance and reorder the 2-dimensional layout with GRID. The goal is have a lightweight responsive page with very minimal javascript and have support across most browsers.


Layout
------

The ordering of semantic tags in the HTML Doc is as follows:

head
body
	-header
	-nav
	-main
	-footer

All tags in the body are to be divided into sections, labelled with a class and further subdivided as necessary. All subdivided items are to be responsive as well as play nice with the GRID layout.

Ideal section structure that contains content is as follows:

section
	-header
	-article
	-aside
	-footer

### Mobile Layout
| Column 1 |
|:--------:|
| header |
| nav |
| +main |
| +section |
| -header |
| -article |
| -aside |
| -footer |
| footer |

### Tablet Layout

| Column 1 | Column 2 |
|:--------:|:--------:|
| header | header |
| nav | nav |
| main | main |
| section | section |
| header | header |
| article | aside |
| footer | footer |
| footer | footer |


### Desktop Layout

| Column 1 | Column 2 | Column 3 |
|:--------:|:--------:|:--------:|
| header | header | nav |
| main | main | main |
| section | section | section |
| header | header | header |
| article | article | aside |
| footer | footer | footer |
| footer | footer | footer |

Todo: add CMS hooks, standardize layouts, extend functionality, reduce amount of CSS used, consider CSS pre- and post-processing
