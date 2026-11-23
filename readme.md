# Person Marking in South-Central Trans-Himalayan: Hyow

This PARALEX set contains person markers in Hyow, including inflected verbal forms and pronouns. It constitutes part of the PMST (Person Marking in South-Central Trans-Himalayan) database.
The PMST database is a collection of person forms from a broad sample of South-Central Trans-Himalayan languages collected with a common methodology and published as PARALEX sets. PMST sets can be used both for describing and analyzing language-internal distributions and for comparison of person forms.

The general design principles of PMST are described in Auderset et al. 2026. Files and columns are described here only where they deviate from the PARALEX standard.
For more details about the data, please consult the data_sheet.md in the docs folder.

* PMST diverges most from the PARALEX standard and design principles in that the verb forms are abstract and do not contain a lexical verb stem. In its place, we use Σ as a placeholder (as is common in Trans-Himalayan linguistics). This means that there is no lexeme table and the data set cannot be used to study variation in verb stems.
* The source_form column in the forms file contains the data exactly as it appears within the source. This may include a lexical verb stem (listed in lexemes). In the orthographic and phonological representation, the lexical verb is replaced by a Σ (as there are no inflectional classes). This placeholder also appears in the graphemes and sounds files for validation purposes.
* The lexemes file is kept relatively minimal and only lists each lexical stem in orthographic form and its meaning. This is because we do not always have access to forms with stems. For pronouns, "no_stem" is indicated in the lexeme column in the forms file and verb forms without a stem are labeled "abstract_entry". These are also listed in the lexemes file (for validation purposes).
* To facilitate comparison across PMST data sets, each file has an additional column with a language identifier. This means that files can be combined from different PMST sets without losing information.
* The morphs file contains a list of all morphs that appear in the data set (apart from the stem) in tokenized IPA. For each morph there is a list of all the forms and cells it appears in. 
* The docs folder contains the data sheet with more extensive description of how the data was gathered. It also contains csv tables with matrix layouts of the paradigms (similar to what we usually find in published sources) and a plot showing the distribution of each morph across most relevant grammatical categories.

## Additional information specific to Hyow

* Tone: Hyow has contrastive tone. In the orthography, low tone is marked with a grave accent, high tone with an acute accent, and falling tone with a circumflex. In the IPA representation, tones are represented with numbers (1 = low, 5 = high). The tone letters used in the grammar of Hyow, the source of the data, are different from the ones used here. The letters are normalized to 51 for falling, 5 for high-level, and 1 for low-level tones regardless of the syllable types. All the tones in the Hyow data represent underlying tones.
* Copy vowels: Some morphemes have underspecified vowels and 'copy' the vowel of the stem. We chose the form with an /a/ vowel as the default form, since cognate morphemes in other SC languages predominantly exhibit /a/. The other forms are tagged as copy_v.
* Future: Hyow does not have tense marking. However, it differentiates between realis and irrealis. In addition, there is a distinct irrealis marker, which is termed as 'delayed negative' in the grammar of Hyow, in negative clauses. Both the irrealis markers in affirmative and negative are used as future for this data set.



## References

Auderset, Sandra, Hunter L. Brown, Jonathan Reich, Pascal Gerber, Muhammad Zakaria, and Linda Konnerth. 2026. “A Database of Person Marking in South-Central Trans-Himalayan”. *Journal of Open Humanities Data* 12 (1): 58. https://doi.org/10.5334/johd.505.

Zakaria, Muhammad. 2018. A grammar of Hyow. PhD thesis. Singapore: Nanyang University.
