# UNER_Romanian-LegalNERo
UNER annotations for Romanian texts from the legal domain, based on the LegalNERo corpus. The complete corpus, with different annotation formats, is available from Zenodo: https://doi.org/10.5281/zenodo.4772094 .

This UNER version provides only commonly used UNER named entity classes (namely organizations, persons, locations). However, the complete LegalNERo corpus provides gold annotations for organizations, locations, persons, time and legal resources mentioned in legal documents (legal references). Starting with version 4, the legal references were annotated using fine-grained legal document types: Law. Ordinance, Publication, Decree, Decision, Treaty, Report, Order, Regulation, Directive, EmergencyOrdinance, Norm, Convention, Code, and Other. Additionally it offers GEONAMES codes for the named entities annotated as location (where a link could be established). 

### Publications

If you use this dataset, please cite the corresponding [paper](https://doi.org/10.3233/SW-233351):
```
@article{Pais2024legalnero,
title = {LegalNERo: A linked corpus for named entity recognition in the Romanian legal domain},
author = {Păiș,Vasile and Mitrofan, Maria and Gasan, Carol Luca and Ianov, Alexandru and Ghiță, Corvin and Coneschi, Vlad Silviu and Onuț, Andrei},
year = 2024,
journal = {Semantic Web},
publisher = {IOS Press},
volume = 15,
pages = {831--844},
doi = {10.3233/SW-233351},
issn = {2210-4968},
url = {https://doi.org/10.3233/SW-233351},
}
```

Additional papers using the dataset were published and may of interest:
[Named Entity Recognition in the {R}omanian Legal Domain](https://aclanthology.org/2021.nllp-1.2)
```
@inproceedings{pais-etal-2021-named,
title = {Named Entity Recognition in the {R}omanian Legal Domain},
author = {Pais, Vasile and Mitrofan, Maria and Gasan, Carol Luca and Coneschi, Vlad and Ianov, Alexandru},
year = 2021,
month = nov,
booktitle = {Proceedings of the Natural Legal Language Processing Workshop 2021},
publisher = {Association for Computational Linguistics},
address = {Punta Cana, Dominican Republic},
pages = {9--18},
url = {https://aclanthology.org/2021.nllp-1.2},
}
```

[Towards a named entity recognition system in the Romanian legal domain using a linked open data corpus](https://www.juls.savba.sk/attachments/workshop_20210930_en/workshop_20210930_book_of_abstracts.pdf#page=16)
```
@inproceedings{pais-mitrofan-2021-towards-legalner,
title = {Towards a named entity recognition system in the Romanian legal domain using a linked open data corpus},
author = {Păiș, Vasile and Mitrofan, Maria},
year = 2021,
month = sep,
booktitle = {Workshop on Deep Learning and Neural Approaches for Linguistic Data},
address = {Skopje, North Macedonia},
pages = {16--17},
url = {https://www.juls.savba.sk/attachments/workshop_20210930_en/workshop_20210930_book_of_abstracts.pdf#page=16},
}
```

### Licensing

Initially, the LegalNERo dataset was made available under the license CC BY-NC-ND 4.0 (Attribution-NonCommercial-NoDerivatives 4.0 International). The Zenodo version remains under that license.

This UNER version of the work is provided under the license CC BY-SA 4.0 (Attribution-ShareAlike 4.0 International).
The license can be viewed online here: [https://creativecommons.org/licenses/by-nc-nd/4.0/](https://creativecommons.org/licenses/by-sa/4.0/deed.en) 
and the full text here: [https://creativecommons.org/licenses/by-nc-nd/4.0/legalcode](https://creativecommons.org/licenses/by-sa/4.0/legalcode.en) . 
