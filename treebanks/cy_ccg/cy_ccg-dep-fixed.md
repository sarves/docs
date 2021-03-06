---
layout: base
title:  'Statistics of fixed in UD_Welsh-CCG'
udver: '2'
---

## Treebank Statistics: UD_Welsh-CCG: Relations: `fixed`

This relation is universal.

172 nodes (1%) are attached to their parents as `fixed`.

172 instances of `fixed` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.09883720930233.

The following 12 pairs of parts of speech are connected with `fixed`: <tt><a href="cy_ccg-pos-ADP.html">ADP</a></tt>-<tt><a href="cy_ccg-pos-ADP.html">ADP</a></tt> (78; 45% instances), <tt><a href="cy_ccg-pos-ADP.html">ADP</a></tt>-<tt><a href="cy_ccg-pos-NOUN.html">NOUN</a></tt> (29; 17% instances), <tt><a href="cy_ccg-pos-ADP.html">ADP</a></tt>-<tt><a href="cy_ccg-pos-ADJ.html">ADJ</a></tt> (12; 7% instances), <tt><a href="cy_ccg-pos-NOUN.html">NOUN</a></tt>-<tt><a href="cy_ccg-pos-ADP.html">ADP</a></tt> (12; 7% instances), <tt><a href="cy_ccg-pos-NOUN.html">NOUN</a></tt>-<tt><a href="cy_ccg-pos-NOUN.html">NOUN</a></tt> (12; 7% instances), <tt><a href="cy_ccg-pos-ADV.html">ADV</a></tt>-<tt><a href="cy_ccg-pos-CCONJ.html">CCONJ</a></tt> (8; 5% instances), <tt><a href="cy_ccg-pos-ADP.html">ADP</a></tt>-<tt><a href="cy_ccg-pos-ADV.html">ADV</a></tt> (7; 4% instances), <tt><a href="cy_ccg-pos-ADV.html">ADV</a></tt>-<tt><a href="cy_ccg-pos-ADP.html">ADP</a></tt> (5; 3% instances), <tt><a href="cy_ccg-pos-NOUN.html">NOUN</a></tt>-<tt><a href="cy_ccg-pos-ADV.html">ADV</a></tt> (5; 3% instances), <tt><a href="cy_ccg-pos-ADP.html">ADP</a></tt>-<tt><a href="cy_ccg-pos-SCONJ.html">SCONJ</a></tt> (2; 1% instances), <tt><a href="cy_ccg-pos-ADP.html">ADP</a></tt>-<tt><a href="cy_ccg-pos-CCONJ.html">CCONJ</a></tt> (1; 1% instances), <tt><a href="cy_ccg-pos-PART.html">PART</a></tt>-<tt><a href="cy_ccg-pos-CCONJ.html">CCONJ</a></tt> (1; 1% instances).


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 7 fixed	color:blue
1	Hi	hi	PRON	indep	Gender=Fem|Number=Sing|Person=3|PronType=Prs	5	nsubj	_	_
2	yw	bod	AUX	aux	Mood=Ind|Number=Sing|Person=3|Tense=Pres	5	cop	_	SpaceAfter=No
3	'r	y	DET	art	_	5	det	_	_
4	drydedd	trydydd	ADJ	ord	Degree=Pos|Gender=Fem|Mutation=SM	5	amod	_	_
5	blaned	blaned	NOUN	noun	Gender=Fem|Number=Sing	0	root	_	_
6	oddi	oddi	ADP	prep	_	9	case	_	_
7	wrth	wrth	ADP	prep	_	6	fixed	_	_
8	yr	y	DET	art	_	9	det	_	_
9	haul	haul	NOUN	noun	Gender=Masc|Number=Sing	5	nmod	_	SpaceAfter=No
10	.	.	PUNCT	punct	_	5	punct	_	SpacesAfter=\n

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 4 fixed	color:blue
1	Cilwenu	cilwenu	NOUN	verbnoun	Number=Sing|VerbForm=Vnoun	0	root	_	_
2	hyd	hyd	ADP	prep	_	1	obl	_	_
3	yn	yn	ADP	prep	_	2	fixed	_	_
4	oed	oed	NOUN	noun	Gender=Masc|Number=Sing	2	fixed	_	SpaceAfter=No
5	,	,	PUNCT	punct	_	7	punct	_	_
6	mewn	mewn	ADP	prep	_	7	case	_	_
7	ffordd	ffordd	NOUN	noun	Gender=Fem|Number=Sing	1	obl	_	_
8	eironig	geironig	ADJ	pos	Degree=Pos|Mutation=SM	7	amod	_	SpaceAfter=No
9	.	.	PUNCT	punct	_	1	punct	_	SpacesAfter=\s\n

~~~


~~~ conllu
# visual-style 13	bgColor:blue
# visual-style 13	fgColor:white
# visual-style 12	bgColor:blue
# visual-style 12	fgColor:white
# visual-style 12 13 fixed	color:blue
1	yr	y	PART	aff	_	2	advmod	_	_
2	wy	bod	VERB	verb	Mood=Ind|Number=Sing|Person=1|Tense=Pres	0	root	_	_
3	'n	yn	AUX	impf	_	4	aux	_	_
4	hoffi	hoffi	NOUN	verbnoun	Number=Sing|VerbForm=Vnoun	2	xcomp	_	SpaceAfter=No
5	'r	y	DET	art	_	6	det	_	_
6	syniad	syniad	NOUN	noun	Gender=Masc|Number=Sing	4	obj	_	_
7	ein	ein	PRON	dep	Number=Plur|Person=1|Poss=Yes|PronType=Prs	8	nsubj	_	_
8	bod	bod	NOUN	verbnoun	Number=Sing|VerbForm=Vnoun	6	acl	_	_
9	yn	yn	AUX	impf	_	10	aux	_	_
10	trafod	trafod	NOUN	verbnoun	Number=Sing|VerbForm=Vnoun	8	xcomp	_	SpaceAfter=No
11	,	,	PUNCT	punct	_	12	punct	_	_
12	yn	yn	ADP	prep	_	10	advmod	_	_
13	hytrach	hytrach	ADJ	pos	Degree=Pos	12	fixed	_	_
14	nac	nac	CCONJ	cconj	_	15	cc	_	_
15	ymladd	ymladd	NOUN	verbnoun	Number=Sing|VerbForm=Vnoun	10	advcl	_	SpaceAfter=No
16	.	.	PUNCT	punct	_	2	punct	_	SpacesAfter=\n

~~~


