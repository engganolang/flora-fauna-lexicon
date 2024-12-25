Enggano Flora and Fauna Lexicon
================
Dendi Wijaya
<a itemprop="sameAs" content="https://orcid.org/0000-0002-8767-9364" href="https://orcid.org/0000-0002-8767-9364" target="orcid.widget" rel="noopener noreferrer" style="vertical-align:top;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" style="width:1em;margin-right:.5em;" alt="ORCID iD icon"></a>,
[Gede Primahadi Wijaya
Rajeg](https://www.ling-phil.ox.ac.uk/people/gede-rajeg)
<a itemprop="sameAs" content="https://orcid.org/0000-0002-2047-8621" href="https://orcid.org/0000-0002-2047-8621" target="orcid.widget" rel="noopener noreferrer" style="vertical-align:top;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" style="width:1em;margin-right:.5em;" alt="ORCID iD icon"></a>,
Engga Zakaria Sangian
<a itemprop="sameAs" content="https://orcid.org/0009-0000-8802-6819" href="https://orcid.org/0009-0000-8802-6819" target="orcid.widget" rel="noopener noreferrer" style="vertical-align:top;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" style="width:1em;margin-right:.5em;" alt="ORCID iD icon"></a>

<!-- README.md is generated from README.Rmd. Please edit that file -->
<!-- badges: start -->

[<img
src="https://raw.githubusercontent.com/engganolang/digitised-holle-list/main/file-oxweb-logo.gif"
width="84" alt="The University of Oxford" />](https://www.ox.ac.uk/)
[<img
src="https://raw.githubusercontent.com/engganolang/digitised-holle-list/main/file-lingphil.png"
width="83"
alt="Faculty of Linguistics, Philology and Phonetics, the University of Oxford" />](https://www.ling-phil.ox.ac.uk/)
[<img
src="https://raw.githubusercontent.com/engganolang/digitised-holle-list/main/file-ahrc.png"
width="325" alt="Arts and Humanities Research Council (AHRC)" />](https://www.ukri.org/councils/ahrc/)
</br>*This work is part of the [AHRC-funded
project](https://gtr.ukri.org/projects?ref=AH%2FW007290%2F1) on the
lexical resources for Enggano, led by the Faculty of Linguistics,
Philology and Phonetics at the University of Oxford, UK. Visit the
[central webpage of the Enggano
project](https://enggano.ling-phil.ox.ac.uk/)*.

<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/">

<span property="dct:title">Enggano Flora and Fauna Lexicon</span> by
<span property="cc:attributionName">Dendi Wijaya, Gede Primahadi W.
Rajeg, and Engga Zakaria Sangian</span> is licensed under
<a href="https://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Creative
Commons Attribution-NonCommercial-ShareAlike 4.0
International<img src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" style="height:22px!important;margin-left:3px;vertical-align:text-bottom;"/><img src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" style="height:22px!important;margin-left:3px;vertical-align:text-bottom;"/><img src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1" style="height:22px!important;margin-left:3px;vertical-align:text-bottom;"/><img src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1" style="height:22px!important;margin-left:3px;vertical-align:text-bottom;"/></a>

</p>
<!-- badges: end -->

# Overview

If you use the data from this repository ([Wijaya et al.,
2024](#ref-Wijaya_Enggano_Flora_and_2024)), please cite as follows:

> Wijaya, D., Rajeg, G. P. W., & Sangian, E. Z. (2024). Enggano Flora
> and Fauna Lexicon (Version 1.0.0) \[Data set\].
> <https://github.com/engganolang/flora-fauna-lexicon>

This repository holds the annotated databases for the Enggano Flora and
Fauna Lexicon. The databases, originally stored as Google Spreadsheets
for collaboration, are then accessed and processed using R codes in
[this repository](https://github.com/engganolang/enggano-flora-fauna)
using several R packages ([Bryan, 2023](#ref-gsheet); [Cysouw,
2018](#ref-cysouw_qlcdata_2024); [D’Agostino McGowan & Bryan,
2023](#ref-gdrive); [Moran & Cysouw, 2018](#ref-moran_unicode_2018);
[Ooms, 2023](#ref-ooms_writexl); [Wickham et al.,
2019](#ref-wickham_welcome_2019); [Wickham & Bryan, 2023](#ref-readxl)).

The processing includes creating orthography profile and
tokenisation/segmentation of the phonemic transcription, and, most
importantly, creating links between the Enggano forms and their
corresponding pictures (ID) to be used in the Contemporary Enggano
Dictionary, which is processed using R
[here](https://github.com/engganolang/eno-flex).

The databases consist of four different file types: .rds (R data file),
.csv, .tsv, and .xlsx.

------------------------------------------------------------------------

Dendi Wijaya gathered the primary data in October 2023 and November
2024; transcribed the forms; translated them into Indonesian and
English; provided the IPA transcription; and rename the photos according
to the ID of the forms.

Gede Primahadi W. Rajeg (GPWR) checked which items have been in the
contemporary Enggano FLEx databases and which one to exclude from the
main dictionary databases (e.g., due to duplication, etc.), in
consultation with Engga Zakaria Sangian. GPWR also manually annotated
the main entry variable of the forms so that complex forms can be
subsumed under/linked to their main/root entry in the dictionary;
annotated the crossref. column; performed the segmentation of the IPA
transcription (and fixed errors); linked the forms ID with the photo by
filename; manage this GitHub repository for archiving.

Engga Zakaria Sangian was consulted in a number of meetings for the
verification of orthography and inclusion of the forms.

# References

<div id="refs" class="references csl-bib-body hanging-indent">

<div id="ref-gsheet" class="csl-entry">

Bryan, J. (2023). *googlesheets4: Access google sheets using the sheets
API V4* (Version 1.1.1) \[Computer software\].
<https://CRAN.R-project.org/package=googlesheets4>

</div>

<div id="ref-cysouw_qlcdata_2024" class="csl-entry">

Cysouw, M. (2018). *<span class="nocase">qlcData</span>: Processing data
for quantitative language comparison* (Version 0.2.1) \[Computer
software\]. <https://cran.r-project.org/web/packages/qlcData/index.html>

</div>

<div id="ref-gdrive" class="csl-entry">

D’Agostino McGowan, L., & Bryan, J. (2023). *Googledrive: An interface
to google drive* (Version 2.1.1) \[Computer software\].
<https://CRAN.R-project.org/package=googledrive>

</div>

<div id="ref-moran_unicode_2018" class="csl-entry">

Moran, S., & Cysouw, M. (2018). *The unicode cookbook for linguists:
Managing writing systems using orthography profiles*. Language Science
Press. <https://doi.org/10.5281/zenodo.1296780>

</div>

<div id="ref-ooms_writexl" class="csl-entry">

Ooms, J. (2023). *Writexl: Export data frames to excel ’xlsx’ format*
(Version 1.4.2) \[Computer software\].
<https://CRAN.R-project.org/package=writexl>

</div>

<div id="ref-wickham_welcome_2019" class="csl-entry">

Wickham, H., Averick, M., Bryan, J., Chang, W., McGowan, L., François,
R., Grolemund, G., Hayes, A., Henry, L., Hester, J., Kuhn, M., Pedersen,
T., Miller, E., Bache, S., Müller, K., Ooms, J., Robinson, D., Seidel,
D., Spinu, V., … Yutani, H. (2019). Welcome to the tidyverse. *Journal
of Open Source Software*, *4*(43), 1686.
<https://doi.org/10.21105/joss.01686>

</div>

<div id="ref-readxl" class="csl-entry">

Wickham, H., & Bryan, J. (2023). *Readxl: Read excel files* (Version
1.4.3) \[Computer software\].
<https://CRAN.R-project.org/package=readxl>

</div>

<div id="ref-Wijaya_Enggano_Flora_and_2024" class="csl-entry">

Wijaya, D., Rajeg, G. P. W., & Sangian, E. Z. (2024).
*<span class="nocase">Enggano Flora and Fauna Lexicon</span>* (Version
1.0.0) \[Dataset\]. <https://github.com/engganolang/flora-fauna-lexicon>

</div>

</div>
