# Morphology Matters: A Multilingual Language Modeling Analysis

This repository provides supplementary information for **[Morphology Matters: A Multilingual Language Modeling Analysis](arxivlink)** (to appear in TACL 2020).

## Bible corpus

Fill out **[this form](https://docs.google.com/forms/d/e/1FAIpQLScs6fG2WxmAcMwbmS5fywzgaC9BQ09UPaJ1SBLuO3ae9cf3Jw/viewform?usp=sf_link)** if you are interested in accessing the Bible corpus used in our paper. DO NOT distribute the corpus and use it for research purposes only.

Our corpus contains 145 Bibles in 92 languages, aligned at the verse level. We provide tokenized train, development and test datasets per Bible as used in our paper. If you are interested in accessing the raw data, please refer to the appropriate sources listed below.

If you use our corpus in your research, please cite as appropriate:

```
@article{park2020MorphologyMatters,
    title = {Morphology Matters: A Multilingual Language Modeling Analysis},
    author = "Park, Hyunji Hayley and
      Zhang, Katherine J. and
      Haley, Coleman and
      Steimel, Kenneth and
      Liu, Han and
      Schwartz, Lane",
    journal={CoRR},
    volume={cs.CL/}, to be updated
    year={2020},
    eprint={}, to be updated
    archivePrefix={arXiv},
    primaryClass={cs.CL}
}

@inproceedings{mielke-etal-2019-kind,
    title = {What Kind of Language Is Hard to Language-Model?},
    author = "Mielke, Sabrina J.  and
      Cotterell, Ryan  and
      Gorman, Kyle  and
      Roark, Brian  and
      Eisner, Jason",
    booktitle = "Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics",
    month = jul,
    year = "2019",
    address = "Florence, Italy",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/P19-1491",
    doi = "10.18653/v1/P19-1491",
    pages = "4975--4989",
}

@inproceedings{mayer-cysouw-2014-creating,
    title = {Creating a Massively Parallel {B}ible Corpus},
    author = "Mayer, Thomas  and
      Cysouw, Michael",
    booktitle = "Proceedings of the Ninth International Conference on Language Resources and Evaluation ({LREC}'14)",
    month = may,
    year = "2014",
    address = "Reykjavik, Iceland",
    publisher = "European Language Resources Association (ELRA)",
    url = "http://www.lrec-conf.org/proceedings/lrec2014/pdf/220_Paper.pdf",
    pages = "3158--3163",
}

@article{bible-Christo-2014,
    author = {Christodoulopoulos, Christos and
      Steedman, Mark},
    year = {2014},
    month = {06},
    pages = {1-21},
    title = {A Massively Parallel Corpus: {T}he {Bible} in 100 Languages},
    volume = {49},
    journal = {Language Resources and Evaluation},
    doi = {10.1007/s10579-014-9287-y}
}
```

| Source | ISO 639-3* | 
|--------|------------|
| Used in [Mielke et al. (2019)](https://www.aclweb.org/anthology/P19-1491), originally from [Mayer and Cysouw (2014)](http://www.lrec-conf.org/proceedings/lrec2014/pdf/220_Paper.pdf) | afr, aln, arb, arz, ayr, bba, ben, bqc, bul, cac, cak, ceb,ces, cmn, cnh, cym, dan, deu, ell, eng, fin, fra, guj, gur, hat,hrv, hun, ind, ita, kek, kjb, lat, lit, mah, mam, mri, mya, nld,nor, plt, poh, por, qub, quh, quy, quz, ron, rus, som, tbz, tel,tgl, tpi, tpm, ukr, vie, wal, wbm, xho, zom|
| [Christodoulopoulos and Steedman (2014)](https://doi.org/10.1007/s10579-014-9287-y)| als, amh, dje, heb, isl, jpn, kor, pck, slk, slv, spa, swe, tha |
| http://bible.com | crk, gug, gui, hin, ike, ikt, kan, mal, mar, nch, nep, nhe,pes, pol, sna, spa, tel, tob, tur |
| https://bibles.org | esu , eng |
| http://old.bibelselskabet.dk | kal|

## WALS features

We augmented the existing WALS database by consulting reference grammars for each language with missing feature values. The WALS feature values are found in `[wals_language.csv](/wals_language.csv)`. The reference grammars that we consulted are listed below.

| ISO 639-3* | Language | Reference |
| ---------- | -------- | --------- |
| arb | Arabic (Modern Standard) | [Ryding (2005)](https://doi.org/10.1017/CBO9780511486975) |
| wbm | Wa | [Mai (2012)](https://inter.payap.ac.th/wp-content/uploads/linguistics_students/Seng_Mai_Thesis.pdf) |
| mri | Māori | [Bauer (1993)](https://doi.org/10.4324/9780203403723) |
| ess | Yupik (St. Lawrence Island) | [Jacobson (2001)](https://www.google.com/books/edition/A_Practical_Grammar_of_the_St_Lawrence_I/Z40JAAAACAAJ?hl=en) |
| esu | Yup'ik | [Miyaoka (2012)](https://doi.org/10.1515/9783110278576) |
| lit | Lithuanian | []() |
| cym | Welsh | []() |
| afr | Afrikaans | []() |
| dan | Danish | []() |
| nld | Dutch | []() |
| ben | Bengali | []() |
| hat | Haitian Creole | [DeGraff (2007)](http://lingphil.mit.edu/papers/degraff/degraff2007hc-ccs.pdf) |
| tpi | Tok Pisin | [Verhaar (1995)](https://www.jstor.org/stable/20006762), [Woolford (1979)](https://doi.org/10.15144/PL-B66) |
| cnh | Lai | [Peterson (2003)](https://doi.org/10.4324/9781315399508) |
| gug | Guaraní | [Gregores and Suárez (1967)](https://doi.org/10.1515/9783111349633) |


* Code table available at https://iso639-3.sil.org.
