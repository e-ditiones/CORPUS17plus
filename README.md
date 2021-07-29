# CORPUS17+ - Corpus of TEI encoded 17th French prints

This repository contains layout analysis and OCR from 17<sup>th</sup> books in TEI files and their ODD.


## Pipeline

Thoses files were created thanks to a pipeline :

1. [OCR17+](https://github.com/e-ditiones/OCR17plus) for HTR/OCR
2. [extractor](https://github.com/e-ditiones/extractor) for transformation ALTO->TEI

## TEI documentation
An [ODD is  available](https://github.com/e-ditiones/CORPUS17plus/tree/main/ODD). It is based on [ODD17](github.com/e-ditiones/ODD17). The main modifications are :

1. `teiHeader` now contains
  * metadata obtained in the manifest IIIF and with SPARQL request
  * Additional information about the printer
  * Additional information about the use of the [SegmOnto vocabulary](http://github.com/SegmOnto).

2. `facsimile` now contains all layout informations about different zones, lines, and baselines, with pixels coordinates and links to 
IIIF images.

3. `text` in which is all transcription, linked to the relevant line/zone

## Credits

Documents have been created by Claire Jahan with the help of Simon Gabay, as part of the [_E-ditiones_](https://github.com/e-ditiones) project.

## Contact
Claire Jahan : claire.jahan[at]chartes.psl.eu

Simon Gabay : Simon.Gabay[at]unige.ch

## Licence

This repository is CC-BY.
<br/>
<a rel="license" href="https://creativecommons.org/licenses/by/2.0"><img alt="Creative Commons License" src="https://i.creativecommons.org/l/by/2.0/88x31.png" /></a>

## Cite this repository

Claire Jahan, Simon Gabay. 2020. _CORPUS17+ - Corpus of TEI encoded 17th French prints._, Paris/Geneva: ENS Paris/UniGE, 2021, https://github.com/e-ditiones/CORPUS17plus. 
