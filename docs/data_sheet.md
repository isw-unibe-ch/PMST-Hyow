Data set name: PMST Hyow

Data set developer(s): Muhammad Zakaria, Sandra Auderset

Data sheet author(s): Muhammad Zakaria, Sandra Auderset


# Motivation

**For what purpose was the dataset created?**

This data set was created to investigate the dynamics of person forms in Hyow and other South-Central Trans-Himalayan languages.
Further background and motivation can be found in Auderset et al. (in prep).

**Who created the data set (for example, which team, research group) and on behalf of which entity (for example, company, institution, organization)?**

The data set was created by a team of researchers at the Department of Linguistics at the University of Bern in collaboration with local linguists and language experts in the Chittagong Hill Tracts of Bangladesh.

**Who funded the creation of the data set?**

This work is funded by SNSF (Swiss National Science Foundation) Grant 10000946 to Linda Konnerth at the University of Bern. The original data was collected during fieldworks funded by the Nanyang Tecgnological University (NTU) Research Scholarship 2013 and NSF grant #BCS-0349021.


# Composition

This Paralex dataset documents paradigms of inflected verb forms as well as pronouns.

**Are forms given as orthographic, phonetic, and or phonemic sequences ?** 

Forms are provided as orthographic and phonemic sequences.
The orthography is either the practical one used by the community or a version of the IPA used by linguists and language experts.
For Hyow, it is a version of the simplified IPA used by linguists.

**How many instances are there in total?**

-   Number of inflected forms: 917

-   Number of unique inflected forms: 272

-   Number of unique scenarios (person, number, TAM, polarity combinations): 352

-   Number of inflected forms per paradigm and subparadigm:

| **Paradigm** | **n** | **Tags**        | **n** |
|--------------|------:|-----------------|------:|
| Pronouns     |    13 | default         |    11 |
|              |       | unspec.var      |     2 |
| NFUT.AFF     |   238 | default         |    82 |
|              |       | copy.v          |   123 |
|              |       | pragm.m         |     9 |
|              |       | pragm.m, copy.v |    24 |
| NFUT.NEG     |   215 | default         |    83 |
|              |       | copy.v          |    99 |
|              |       | pragm.m         |     9 |
|              |       | pragm.m, copy.v |    24 |
| FUT.AFF      |   238 | default         |    83 |
|              |       | copy.v          |   122 |
|              |       | pragm.m         |     9 |
|              |       | pragm.m, copy.v |    24 |
| FUT.NEG      |   213 | default         |    83 |
|              |       | copy.v          |    99 |
|              |       | pragm.m         |     9 |
|              |       | pragm.m, copy.v |    24 |

**Language varieties**

-   BCP-47 language tag: NA
-   Glottocode: NA
-   Language variety description: Glottolog and Enthnologue consider Hyow as a variety of Asho Chin (asho1236; csh). Hyow is a Southeastern South Central Tibeto-Burman language as much as Asho is. There are phonological, morphological and morphosyntactic differences between Asho and Hyow, and they are not mutually intelligible. As other South Central languages, Asho and Hyow have lexical similarities. Recently, an initiave has been taken to get an ISO code for Hyow. The data for this work comes from the Laitu variety of Hyow spoken in the Eastern Gungrupara, a village a few kilometers away from Bandarban town, one of the three administrative districts in the Chittagong Hill Tracts.

**Does the data pertain to specific dialects, geographical locations, genre, etc ?**

There are two varieties of Hyow spoken in the plains and highlands. There is no difference in person marking in the two varieties of Hyow, Laitu and Kongtu. The data set is therefore representative of both known Hyow varieties.

**Does the dataset contain all possible instances or is it a sample (not necessarily random) of instances from a larger set?** 

The dataset contains all person forms found in the language, both verbal indexes and pronouns. Hortative forms were not included in the dataset (see below for explanation).

**Is any information missing from individual instances?** 

NA

**Are there any errors, sources of noise, or redundancies in the dataset?** 

No.

**Is the dataset self-contained, or does it link to or otherwise rely on external resources (for example, websites, tweets, other datasets)?** 

The dataset is self-contained.

**If linking to vocabularies from other databases (such as databases of features, cells, sounds, languages, or online dictionnaries), were there any complex decisions in the matching of entries from this dataset to those of the vocabularies (eg. inexact language code) ?**

NA

**Does the dataset contain data that might be considered confidential (for example, data that is protected by legal privilege or by doctor-patient confidentiality, data that includes the content of individuals' non-public communications)?**

The dataset pertains to small or indigenous language communities, namely those of the Hyow people in the Chittagong Hill Tracts.
The data are published here with the consent of the community.


# Collection process.

**What is provenance for each table (lexemes, cells, forms, frequencies, sounds, features), as well as for segmentation marks if any ? Are any information derived from other datasets ?** 

The data comes from fieldwork conducted by Muhammad Zakaria. Specific forms were taken from a combination of a text corpus of 10 hours, elicitation based on textual examples, and field notes. This work also forms the basis for the segmentation. 

**How were paradigms separated (eg. in the case of homonyms or variants)? What theoretical or practical choices were made?**

Design principles and theoretical choices implemented for this data set are explained in "Paper in JOHD".

**How was the paradigm structure (set and labels of paradigm cells) decided? What theoretical or practical choices were made?**

Design principles and theoretical choices implemented for this data set are explained in "Paper in JOHD".

**What is the expertise of the contributors with the documented language ?** 

Muhammad Zakaria: linguist specializing in South-Central Trans-Himalayan morphosyntax

Hla Kray Prue Kheyang, New Jai Kheyang, Hlaaung Kheyang, Mong Hla Prue Kheyang: native speakers

**Who was involved in the data collection process (for example, students, crowdworkers, contractors) and how were they compensated (for example, how much were crowdworkers paid)?**

Only the contributors listed at the beginning of this file.

**Over what timeframe was the data collected?** 

The data was collected over a period of 10 years from 2006 to 2016.


# Preprocessing/cleaning/labeling.

**How were the inflected forms obtained ?**

All forms were collected from native speakers. See above.

**How were the phonological or phonemic transcriptions obtained?** 

The phonological transcriptions were generated with the qlcData package in R using an orthography profile that maps graphemes to IPA.
The mappings are based on the phonological analysis of the language.

**If relevant, how were the forms segmented?**

Manually based on expert knowledge.

**Was any preprocessing/cleaning/labeling of the data done (for example, discretization or bucketing, tokenization, part-of-speech tagging, SIFT feature extraction, removal of instances, processing of missing values, cleaning of labels, mapping between vocabularies, etc)?** 

No.

**Was the "raw" data saved in addition to the preprocessed/cleaned/labeled data (for example, to support unanticipated future uses)?**

Yes. Some of the data is deposited in PARADISEC, https://catalog.paradisec.org.au/repository/ZM1/ARGS04. 

**Is the software that was used to preprocess/clean/label the data available?** 

The data was prepared for Paralex with the open source software R using RStudio.


# Uses

**Has the dataset been used for any published work already?** 

The dataset in its current structure has not been published.

**What (other) tasks could the dataset be used for?**

It can be used for descriptive and comparative analyses.

**Are there tasks for which the dataset should not be used?**

No.


# Distribution.

**Will the dataset be distributed to third parties outside of the entity (for example, company, institution, organization) on behalf of which the dataset was created?**

No.

**How will the dataset be distributed (for example, tarball on website, API, GitHub)?** 

The dataset is available on GitHub at X and on Zenodo as part of the Paralex collection at X.

**Will the dataset be distributed under a copyright or other intellectual property (IP) license, and/or under applicable terms of use (ToU)?** 

The dataset is distributed under a CC-BY-SA 4.0 license.


# Maintenance

**If others want to extend/augment/build on/contribute to the dataset, is there a mechanism for them to do so?** 

For suggestions or error reports please open an issue on GitHub.
