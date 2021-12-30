# UD for Even

##  Tokenisation and Word Segmentation

Tokens in the corpus are defined as sequences of non-whitespace or punctuation characters separated by whitespace.

Underneath tokens are syntactic words. These are words which take part in dependency relations.

A single token may be split into more than one word based on the following criteria:

* Emphatic and other clitics are split (for instance =da, =si, =tkan)
* Some appositive modifiers which are hyphenated

## Morphology

### Tags

* [ADJ](https://universaldependencies.org/u/pos/ADJ.html), [ADP](https://universaldependencies.org/u/pos/ADP.html), [ADV](https://universaldependencies.org/u/pos/ADV.html), [AUX](https://universaldependencies.org/u/pos/AUX.html), [CCONJ](https://universaldependencies.org/u/pos/CCONJ.html), [DET](https://universaldependencies.org/u/pos/DET.html), [INTJ](https://universaldependencies.org/u/pos/INTJ.html), [NOUN](https://universaldependencies.org/u/pos/NOUN.html), [NUM](https://universaldependencies.org/u/pos/NUM.html), [PART](https://universaldependencies.org/u/pos/PART.html), [POS](https://universaldependencies.org/u/pos/POS.html), [PRON](https://universaldependencies.org/u/pos/PRON.html), [PROPN](https://universaldependencies.org/u/pos/PROPN.html), [PUNCT](https://universaldependencies.org/u/pos/PUNCT.html), [SCONJ](https://universaldependencies.org/u/pos/SCONJ.html), [VERB](https://universaldependencies.org/u/pos/VERB.html), [X](https://universaldependencies.org/u/pos/X.html)

### Glosses and their mapping onto UD features

<details>
  <summary>Mapping table</summary>


| Gloss            | UD                                              |
|------------------|-------------------------------------------------|
|                3 | Person=3                                        |
| 1pl              | Number=Plur\|Person=1                           |
| 1pl.exc          | Number=Plur\|Person=1\|Clusivity=Ex             |
| 1pl.inc          | Number=Plur\|Person=1\|Clusivity=In             |
| 1sg              | Number=Sing\|Person=1                           |
| 2pl              | Number=Plur\|Person=2                           |
| 2sg              | Number=Sing\|Person=2                           |
| 3pl              | Number=Plur\|Person=3                           |
| 3sg              | Number=Sing\|Person=3                           |
| abl              | Case=Abl                                        |
| abl.adv          | -                                               |
| acc              | Case=Acc                                        |
| act              | -                                               |
| ad               | Voice=Pass                                      |
| ad.stage         | -                                               |
| add              | -                                               |
| adj.aug          | -                                               |
| adj.bad          | -                                               |
| adj.df           | -                                               |
| adj.extr         | -                                               |
| adj.hq           | -                                               |
| adj.negposs      | -                                               |
| adj.new          | -                                               |
| adj.num          | -                                               |
| adj.ql           | -                                               |
| adj.rel          | -                                               |
| adj.stage        | -                                               |
| adj.time         | -                                               |
| adj.vis          | -                                               |
| adj3             | -                                               |
| adv              | -                                               |
| adv.dir          | -                                               |
| adv.num          | -                                               |
| ag.once          | -                                               |
| ag.prof          | -                                               |
| al               | -                                               |
| al.poss          | -                                               |
| ant              | VerbForm=Conv                                   |
| ant.sg           | VerbForm=Conv\|Number=Sing                      |
| appr             | -                                               |
| assum            | Mood=Pot                                        |
| attn             | -                                               |
| aug              | -                                               |
| aug.amlr         | -                                               |
| aug.spr          | -                                               |
| caus             | Voice=Cau                                       |
| clr              | -                                               |
| coll             | -                                               |
| com              | Case=Com                                        |
| com.anim         | Case=Com                                        |
| com.vit          | Case=Com                                        |
| con              | -                                               |
| cond.ds          | VerbForm=Conv                                   |
| cond.ss          | VerbForm=Conv                                   |
| conseq           | -                                               |
| conseq2          | -                                               |
| cover            | -                                               |
| cvb              | VerbForm=Conv                                   |
| cvb.neg          | Polarity=Neg\|VerbForm=Conv                     |
| cvb.neg.mod      | Polarity=Neg\|VerbForm=Conv                     |
| dat              | Case=Dat                                        |
| dat.poss.refl.pl | Case=Dat\|Number[psor]=Sing                     |
| deb              | Mood=Nec\|VerbForm=Part                         |
| dem.dist         | PronType=Dem                                    |
| dem.prox         | PronType=Dem                                    |
| dem.q            | PronType=Int                                    |
| dem.q.attr       | PronType=Int                                    |
| desid            | Mood=Des                                        |
| dim              | -                                               |
| dim.pej          | -                                               |
| dim1             | -                                               |
| dim2             | -                                               |
| dim3             | -                                               |
| dir              | Case=Lat                                        |
| dir.adv          | -                                               |
| dloc             | Case=Ter                                        |
| dst              | Case=Ben                                        |
| dur              | Aspect=Hab                                      |
| elat             | Case=Ela                                        |
| emph             | -                                               |
| equ              | Case=Equ                                        |
| freq             | Aspect=Hab                                      |
| fut              | Tense=Fut\|VerbForm=Fin                         |
| gather           | -                                               |
| get              | -                                               |
| have             | -                                               |
| hor              | Mood=Imp\|Person=1\|Clusivity=In                |
| idk              | -                                               |
| imp              | Mood=Imp\|Person=2                              |
| imp.2pl          | Mood=Imp\|Person=2\|Number=Plur                 |
| imp.dist         | Mood=Imp                                        |
| inch             | -                                               |
| incmp            | -                                               |
| indef            | PronType=Ind                                    |
| ins              | Case=Ins                                        |
| ins.poss.refl.pl | Case=Ins\|Number[psor]=Plur                     |
| ins.poss.refl.sg | Case=Ins\|Number[psor]=Sing                     |
| instr            | -                                               |
| intj             | -                                               |
| intr             | -                                               |
| ints             | -                                               |
| iter             | Aspect=Iter                                     |
| loc              | Case=Loc                                        |
| lvr              | -                                               |
| mcp              | -                                               |
| med              | Voice=Mid                                       |
| mir              | -                                               |
| mom              | -                                               |
| mult             | Aspect=Iter                                     |
| neg              | Polarity=Neg                                    |
| neg.aux          | Polarity=Neg                                    |
| neg.pred         | Polarity=Neg                                    |
| neg.term         | VerbForm=Conv                                   |
| nfut             | Tense=Pres\|VerbForm=Fin                        |
| nmz.abst         | -                                               |
| nmz.hab          | -                                               |
| nmz.inst         | -                                               |
| nmz.lft          | -                                               |
| nmz.loc          | -                                               |
| nmz.place        | -                                               |
| nmz.prc          | -                                               |
| nmz.tool         | -                                               |
| nmz2             | -                                               |
| nom              | Case=Nom                                        |
| ord              | -                                               |
| pej              | -                                               |
| pejor            | -                                               |
| pl               | Number=Plur                                     |
| plac             | Aspect=Iter                                     |
| plur             | Aspect=Iter                                     |
| poss.1pl         | Number[psor]=Plur\|Person[psor]=1               |
| poss.1pl.exc     | Clusivity=Ex\|Number[psor]=Plur\|Person[psor]=1 |
| poss.1pl.inc     | Clusivity=In\|Number[psor]=Plur\|Person[psor]=1 |
| poss.1sg         | Number[psor]=Sing\|Person[psor]=1               |
| poss.2sg         | Number[psor]=Sing\|Person[psor]=2               |
| poss.3pl         | Number[psor]=Plur\|Person[psor]=3               |
| poss.3sg         | Number[psor]=Sing\|Person[psor]=3               |
| poss.neg         | -                                               |
| poss.pred        | -                                               |
| poss.refl.pl     | Number[psor]=Plur                               |
| poss.refl.sg     | Number[psor]=Sing                               |
| prev             | -                                               |
| prior            | VerbForm=Conv                                   |
| prog             | Aspect=Prog                                     |
| proh             | Polarity=Neg\|Mood=Imp\|VerbForm=Conv           |
| prol             | Case=Ess                                        |
| pst              | Tense=Past\|VerbForm=Fin                        |
| ptc              | Tense=Pres\|VerbForm=Part                       |
| ptc.fut          | Tense=Fut\|VerbForm=Part                        |
| ptc.nfut         | Tense=Pres\|VerbForm=Part                       |
| ptc.pst          | Tense=Past\|VerbForm=Part                       |
| ptcl             | -                                               |
| ptcl.cond        | -                                               |
| purp             | Mood=Prp                                        |
| q                | -                                               |
| quant            | PronType=Tot                                    |
| rcp              | Voice=Rcp                                       |
| refl             | PronType=Prs\|Reflex=Yes                        |
| res              | -                                               |
| restr            | -                                               |
| restr2           | -                                               |
| rev1             | -                                               |
| rev2             | -                                               |
| side             | -                                               |
| sim              | VerbForm=Conv                                   |
| sim.sg           | VerbForm=Conv\|Number=Sing                      |
| skin             | -                                               |
| soc              | Voice=Rcp                                       |
| subj             | Mood=Sub                                        |
| suff             | -                                               |
| term             | VerbForm=Conv                                   |
| tr               | -                                               |
| use              | -                                               |
| vbz              | -                                               |
| voc              | Case=Voc                                        |

</details>
  
## Syntax

* WIP

Relations from the official [UD tagset](https://universaldependencies.org/u/dep/) are used.

## Results so far

* ~3.5k glossed tokens
* ~2k lemmatized tokens
* ~700 morphological annotated sentences
* a little bit of syntax

## Repository structure

- code 
- tables
- conllu

