---
layout: base
title:  'Tamil UD'
udver: '2'
---

# UD for Tamil <span class="flagspan"><img class="flag" src="../../flags/svg/IN.svg" /></span> <span class="flagspan" style="padding-left:1em"><img class="flag" src="../../flags/svg/LK.svg" /></span>

## Data
1000 sentences taken from a book "A grammar of modern Tamil" by Thomas Lehmann (1999) are used to construct this treebank. These sentences cover most of the common syntactical constructions in Tamil.

## Sentence ids
### Tamil Nadu / Sri Lanka Tamil
Although most of thses sentences are in form of high variety, some have vocabularies which are specifically used in Tamil Nadu. Therefore, those sentences are marked additionally with #sent_tn.

### Different syntactical structures
There are instances where the same syntactical constructions can be analysed differently. Such constructions are marked as #sent_syn, in addition to usualy #sent_id, where the constructions will have the same sent_id followed by an English letter.

For instance, 

#sent_syn = 15A

#sent_id = 15

and

#sent_syn = 15B

#sent_id = 16

## Tokenisation and Word Segmentation

* Words are delimited by whitespace or punctuation.
* Multiword tokens are common in Tamil; some are multiword syntactical constructions. Further, it is also common that people write words together, without spaces. In this treebank, the following such multiwords are identified, and tokenised to their syntactical units. 
 * the coordinating clitic -உம் / _-um_,  e.g. வேலையும் -> வேலை + உம்
 * noun-verb constructions where verb becomes an aux, e.g. வேலைசெய்தாள் -> வேலை + செய்தாள்
 * verb-verb consturctions where second verb becomes as an aux (or light verb) e.g. வாங்கிக்கொடுத்தான் -> வாங்கி + கொடுத்தான்

## Part of Speech tagging



## Morphological tagging



## Dependency tagging

* Tamil uses 14 universal tags ([SCONJ](), [INTJ](), and [SYM]() do not occur in the corpus at present).
* Tamil has 9 cases, namely nominative, genitive, dative, accusative, instrumental, comitative/sociative, ablative, locative, and vocative. Except nominative, other cases are marked morphologically. Except NSUBJ, OBJ, and IOBJ, others are marked as obl along with sub labels, according to the EUD, as shown below.

obl:abl: 

obl:soc:

obl:com: marked with animate nouns

obl:agent: marked in passive construction for the doer of the action

obl:inst:  marked for nouns that act as instrument of the action 

obl:loc: marked for nouns of place with locative marker

obl:ben: marked for nouns that get benifited from the action

obl:cmpr: marked for nouns of comparison 

obl:arg: marked for Wh-words in argument position

* Spatiotemporal are also analysed as postpositions, and marked with sub labels, as shown below:
obl:tmod: NST (time) is marked 
obl:pmod: NST (place) is marked 

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

* Passivisation: Subjects are suppressed when verbs are passivized.

Tamil uses the following relation subtypes:
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
