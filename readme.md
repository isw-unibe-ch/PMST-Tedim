# Person Marking in South-Central Trans-Himalayan: Tedim

This PARALEX set contains person markers in Tedim, including inflected verbal forms and pronouns. It constitutes part of the PMST (Person Marking in South-Central Trans-Himalayan) database.
The PMST database is a collection of person forms from a broad sample of South-Central Trans-Himalayan languages collected with a common methodology and published as PARALEX sets. PMST sets can be used both for describing and analyzing language-internal distributions and for comparison of person forms.

The general design principles of PMST are described in Auderset et al. 2026. Files and columns are described here only where they deviate from the PARALEX standard.
For more details about the data, please consult the data_sheet.md in the docs folder.

* PMST diverges most from the PARALEX standard and design principles in that the verb forms are abstract and do not contain a lexical verb stem. In its place, we use Σ as a placeholder (as is common in Trans-Himalayan linguistics). This means that the data set cannot be used to study variation in verb stems or inflectional classes.
* The source_form column in the forms file contains the data exactly as it appears in the source. This may include a lexical verb stem (listed in lexemes). In the orthgoraphic and phonological representation, the lexical verb is replaced by a Σ. This placeholder also appears in the graphemes and sounds files for validation purposes.
* The lexemes file is kept relatively minimal and only lists each lexical stem in orthographic form and its meaning. This is because we do not always have access to forms with stems. For pronouns, "no_stem" is indicated in the lexeme column in the forms file and verb forms without a stem are labeled "abstract_entry". These are also listed in the lexemes file (for validation purposes).
* To facilitate comparison across PMST data sets, each file has an additional column with a language identifier. This means that files can be combined from different PMST sets without losing information.
* The morphs file contains a list of all morphs that appear in the data set (apart from the stem) in tokenized IPA. For each morph there is a list of all the forms and cells it appears in. 
* The docs folder contains the data sheet with more extensive description of how the data was gathered.

## Additional information specific to Tedim

* Language designation: Tedim is also known as Tiddim, a designation that seems to go back to Henderson (1965). The people themselves prefer the designation Zopau /zou²paːu³/ for the language and Zomi /zou²miː¹/ for the people. However, since the term "Tedim" is also employed by native speakers publishing on the language and the language is better known under this designation in general, it is used here instead of Zopau /zou²paːu³/.
* Mapping between database paradigm labels (future and nonfuture) and Tedim descriptive labels: Otsuka (2014) uses the terms "realis" (= nonfuture) and "irrealis" (= future). Mroueh (2019) uses the labels "present" (= nonfuture) and "future" (= future).  
* Hortative: The forms tagged as hortative are formally relatable to the future informal ("colloquial 1") paradigm in taking the future marker ni. However, they diverge from other person/number categories in that paradigm that are explicitly marked in both future and non-future in not taking the marker haŋ³ that is used for the inclusive in non-future tense.
* 1SG/1PLE formal forms: According to our consultant, the future and non-future forms for 1SG and 1PLE of the formal paradigm negated with lou³ might be somewhat unnatural. This needs to be investigated further in future research, as it may reveal a semantic difference between the two attested negative markers.
* Tone: The three tones identified for Tedim by Otsuka (2014: 112) are 1) rising/high, 2) level and 3) falling/low. Tones 1 and 3 are realized as high and low with short vowels followed by stop finals (-p, -t, -k), and as rising/falling in other cases.
* Terminology: The tags "formal" vs. "informal" mark a basic register difference that was coined "narrative" vs. "colloquial" by Henderson (1965) and conventionally used in later literature on Tedim (e.g. Otsuka 2014: 110, Mroueh 2019). The terms "formal" and "informal" are preferred here to enhance crosslinguistic comparability with similar oppositions in other South-Central languages in the database. For more details on the usage of the two registers, cf. Henderson (1965), Mroueh (2019: 120).



## References

Auderset, Sandra, Hunter L. Brown, Jonathan Reich, Pascal Gerber, Muhammad Zakaria, and Linda Konnerth. 2026. “A Database of Person Marking in South-Central Trans-Himalayan”. *Journal of Open Humanities Data* 12 (1): 58. https://doi.org/10.5334/johd.505.

Henderson, Eugénie J. A. 1965. _Tiddim Chin. A Descriptive Analysis of two texts_. London: Oxford University Press.

Mroueh, Jade. 2019. "A preliminary documentation of variation in Tedim verbal person marking." *Himalayan Linguistics* 18 (1): 119-133. https://doi.org/10.5070/h918142867.

Otsuka, Kosei. 2014. "Tiddim Chin". Nakayama, Toshihide, Noboru Yoshioka and Kosei Otsuka (eds.). _Grammatical Sketches from the Field_. Volume 2. Tokyo: Research Institute for Languages and Cultures of Asia and Africa (ILCAA), Tokyo University of Foreign Studies: 109-141.
