---
layout: base
title:  'Tamil UD'
udver: '2'
---

# UD for Tamil <span class="flagspan"><img class="flag" src="../../flags/svg/IN.svg" /></span> <span class="flagspan" style="padding-left:1em"><img class="flag" src="../../flags/svg/LK.svg" /></span>

## Data
1000 sentences taken from a book "A grammar of modern Tamil" by Thomas Lehmann have been used. These sentences cover most of the common syntactical constructions in Tamil. 

## Tokenization and Word Segmentation

* Following most tokenization patterns, words are delimited by whitespace or punctuation.
* Multiword tokens are relatively common in Tamil. The following type of constructions have been separated to their synactic units.
 * the coordinating clitic -உம் / _-um_,  e.g. வேலையும் -> வேலை + உம்
 * noun-verb constructions where verb becomes an aux, e.g. வேலைசெய்தாள் -> வேலை + செய்தாள்
 * verb-verb consturctions where second verb becomes as an aux (or light verb) e.g. வாங்கிக்கொடுத்தான் -> வாங்கி + கொடுத்தான்

## Part of Speech tagging

## Morphological tagging


## Dependency tagging

* Tamil uses 14 universal tags ([SCONJ](), [INTJ](), and [SYM]() do not occur in the corpus at present).
* 7 cases are annotated as morphological features of nouns: nominative, genitive, dative, accusative, instrumental, comitative and sociative, locative. 
* Tamil is an agglutinating language and other spatiotemporal and/or case-like morphemes may be analyzed as postpositions.
* Verbs occur as finite forms, participles, infinitives, and gerunds.
* Auxiliary verbs ([AUX]()) include:
  * போ / _po_ “go” for future tense, follows the infinitive of the main verb
  * மாட்டேன் / _māṭṭen_ “will not” (lemma மாட்டு _māṭṭu_) for negative future tense with human subject
  * படு / _paṭu_ “experience” for the passive voice
  * வை / _vai_ “put” for the causative voice
  * இல் / _il_ (இல்லை / _illai_) “not be” for negation
  * உள் / _uḷ_ “within”, இரு / _iru_ “be”, வரு / _varu_ “come”, கொள் / _kòḷ_ “take”, செய் / _cèy_ “do”, விடு / _viṭu_ “let”, வா / _vā_ “come”
  * வேண்டு / _veṇṭu_ “must”
  * முடியும் / _muṭiyum_ “can” (lemma முடி _muṭi_): modal auxiliary, follows the infinitive of the main verb

### Features

## Syntax

* Tamil is a verb-final language; both SOV and OSV orders are possible.
* Core arguments are marked by the morphological cases nominative (subject) and accusative (object).
  Core arguments are bare noun phrases without postpositions.
* Subjects have the following characteristics:
  * Case marking: Subjects occur in nominative case without adpositions.
  * Passivization: Subjects are suppressed when verbs are passivized.
* Objects have the following characteristics:
  * Case marking: Objects occur in accusative case without adpositions.
  * Passivization: Objects become (non-expletive) subjects when verbs are passivized.
* Bare nominal arguments (i.e., verb-licensed dependents) in the dative case are not considered core arguments. They are attached as `obl:arg`.
* Prepositional arguments (i.e., verb-licensed dependents) are not considered core arguments. They are attached as `obl:arg`.

Tamil uses 4 relation subtypes:
* `advmod:emph` for adverbials emphasizing noun phrases
* `compound:prt` to attach verbal particles to verbs
* `nsubj:pass` for nominal subjects in passive clauses
* `obl:arg` for oblique arguments (to distinguish them from other oblique dependents, i.e., adjuncts)

## References

* See also [http://www.southasia.sas.upenn.edu/tamil/grammar/tamilgrammar12.html]()
* [Tamil at the Language Gulper](http://www.languagesgulper.com/eng/Tamil.html)

---

## Treebanks

There is only one Tamil UD treebank at present:

  * [Tamil-TTB](../treebanks/ta_ttb/index.html)
