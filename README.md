# aed-tei
Corpus of Egyptian Texts for the AED - Ancient Egyptian Dictionary

## content
- more than 11000 Egyptian texts
  - encoding via [TEI](https://tei-c.org/)
  - each text is encoded in 4 files: the base text, the sentence translations, the cotextual word translation, and the hieroglyphic encoding.
  - The base text is referenced by the other files via stand off annotation.
  - format of the file names: `[ID_of_the_text].xml` for the base text, `[ID_of_the_text]_st.xml` for the sentence translations, `[ID_of_the_text]_wt.xml` for the cotextual word translation, and `[ID_of_the_text]_hiero.xml` for the hieroglyphic encoding.
- the schema for encoding Egyptian texts in TEI: `aed_schema.xsd`
- the list of Egyptian words `dictionary.xml` containing more than 30000 entries with transcription, German translation, part of speech, and bibliographical information.
- the thesaurus `thesaurus.xml` used for enriching the metadata with controlled vocabulary, e.g. present location, find spot, date, or object types.
- the file `morphologicalFeatures.xml` with the used morphological encoding
- the concordance `concordance_name_text_id.csv` matching the names of Egyptian texts with their IDs, e.g. the pWestcar with the full naming `sawlit:〈pWestcar = 〉pBerlin P 3033//Die Erzählungen des pWestcar` has the ID J4EXGHLCL5DR7JHSPDWTVEKMDY, the shipwrecked sailor, full naming `sawlit:pPetersburg 1115//Die Geschichte des Schiffbrüchigen`, has the ID QUFWZTEPLRE4NHKCPAJXGSAOSQ.

## source
[Teilauszug der Datenbank des Vorhabens "Strukturen und Transformationen des Wortschatzes der ägyptischen Sprache" vom Januar 2018](https://nbn-resolving.org/urn:nbn:de:kobv:b4-opus4-29190) with contributions of Burkhard Backes, Susanne Beck, Anke Blöbaum, Angela Böhme, Marc Brose, Adelheid Burkhardt, Roberto A. Díaz Hernández, Peter Dils, Roland Enmarch, Frank Feder, Heinz Felber, Silke Grallert, Stefan Grunert, Ingelore Hafemann, Anne Herzberg, John M. Iskander, Ines Köhler, Maxim Kupreyev, Renata Landgrafova, Verena Lepper, Lutz Popko, Alexander Schütze, Simon Schweitzer, Stephan Seidlmayer, Gunnar Sperveslage, Susanne Töpfer, Doris Topmann, Anja Weber

## licence
All files: [CC-BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/)

## data transformation, structure of the TEI encoding, schema
by Simon D. Schweitzer, 2019

## transformation code
to be published (soon)
