# computational-linguistics-ub
computational linguistics (LIN/CSE 467/567) at UB (Spring 2019), based on [*Introductory Computational Linguistics 
-- A Practical Aspect*](https://buffalo.box.com/s/1t6hbq77c1yjabp1yo4qu1ovx4tiy2a6). 



* See [[Schedule](https://sites.google.com/site/lrecoursefall2018/schedule-and-syllabus)] from Fall 2018. 
* See [[CSE/LIN467/567 Slack, Spring 2019](https://join.slack.com/t/lincse467567/shared_invite/enQtNTYzMzA1MDgyNzQxLTJhY2I2ZDNjNzI5ZjIxMjY1MGY5ZjBlNWUxMDI5Y2QyOWUzNjMzNTU0Yzg4YWFmZGNkZGQ5ODkzYWM0YTY1NmQ)]


1. preprocessing
1. morphology
1. morphosyntax
1. syntax
1. cross-language
1. language model



## Schedule and Syllabus 
|Event	| Date |	Description	 |Course Materials |
| ------ | ------ | ------ | ------  |
| |  |  | [[syllabus](https://www.overleaf.com/read/bkpszpcndwrf)] |
|lecture | Jan 28 | **introduction** | [[slides](https://www.overleaf.com/read/kzsdqspjvpzk)]|
| |Feb 1 | **preprocessing** |  |
|lecture |  | *tokenization* | Suggested Readings:  <ul><li>[[Moses - Baseline system, corpus preparation](http://www.statmt.org/moses/?n=Moses.Baseline)]</li><li>[[Tokenization: Returning to a Long Solved Problem](http://aclweb.org/anthology/P/P12/P12-2074.pdf)]</li></ul> [[slides](https://www.overleaf.com/read/qcmtrrzqrqfn)]|
|lecture|  | *sentence boundary detection* | Suggested Readings:  <ul><li>[[Sentence Boundary Detection and the Problem with the U.S.](http://aclweb.org/anthology/N/N09/N09-2061.pdf)]</li><li>[[Sentence Boundary Detection: A Long Solved Problem?](http://aclweb.org/anthology/C/C12/C12-2096.pdf)]</li></ul> [[slides](https://www.overleaf.com/read/qwsszsvhncgc)]|
||Feb 8  | lab session | [[notes](https://www.overleaf.com/read/qtrdnthdmpdw)] [[input-tokenization.txt](https://buffalo.box.com/s/wtpbmqqag1p12qv2516agfdgph529giv)][[input-sbd.txt](https://buffalo.box.com/s/xly0wc26bmtmx692qi895ld227ye1ksr)] |
|| Feb 11  | assignment #1 released	 | [[assignment #1](https://www.overleaf.com/read/vfcddpxrtpmg)] (due Feb 18) |
| | Feb 11 | **morphology** |   |
|lecture |  | *morphological segmentation* | Suggested Readings:  <ul><li>[[Empirical Methods for Compound Splitting](http://www.aclweb.org/anthology/E03-1076)]</li>  <li>[[A Joint Model of Orthography and Morphological Segmentation](http://www.aclweb.org/anthology/N16-1080)]</li>  <li>[[Unsupervised Discovery of Morphemes](http://aclweb.org/anthology/W02-0603)]</li></ul> [[slides](https://www.overleaf.com/read/sjjtdtdxrjhn)] |
|lecture |  | *morphological paradigms* | Suggested Readings:  <ul><li>[[Supervised Learning of Complete Morphological Paradigms](https://www.aclweb.org/anthology/N13-1138)]</li></ul> [[slides](https://www.overleaf.com/read/drsgzvdswckp)] |
||  | lab session | [[notes](https://www.overleaf.com/read/qtrdnthdmpdw)] [[ptb.train.txt](https://buffalo.box.com/s/zz6vbqfglrcv29oojmf3kf9e5llv06va)] [[ptb.test.txt](https://buffalo.box.com/s/niyncwhx3i8zel6yuluocglossbda0i9)]|
|| Mar 4 | assignment #2 released	 | [[assignment #2](https://www.overleaf.com/read/zkfynjpnwphk)] (due March 11) |
|| Feb 27 | **morphosyntax** |  |
|lecture |  | *pos tagging* | Suggested Readings:  <ul><li>[[Part-of-Speech Tagging](https://web.stanford.edu/~jurafsky/slp3/8.pdf), Chap.8 in SLP (3rd ed.)]</li> <li>[[A Tutorial on HMMs](https://www.ece.ucsb.edu/Faculty/Rabiner/ece259/Reprints/tutorial%20on%20hmm%20and%20applications.pdf)]</li><li>[[TnT - Statistical Part-of-Speech Tagging](http://www.coli.uni-saarland.de/~thorsten/tnt/)]</li></ul> [[slides](https://www.overleaf.com/read/wdwxhszppdgx)]  |
|| Mar 8  | recitation	 | [[slides](https://www.overleaf.com/read/ygmgyrcqfzzz)]  |
||  | mid-term	 | on March 11-15:<ul><li>on 13: morphology</li><li>on 15: morphosyntax</li><li>on 25: preprocessing (redo)</li> </ul> **ONLY one page cheat sheet is allowed** [[notes](https://www.overleaf.com/read/xccfyqtzrpkq)]  |
|lecture |  | *chunking,ner,srl* | Suggested Readings:  <ul><li>[[Chunking](https://www.clips.uantwerpen.be/conll2000/chunking/), CoNLL-2000 Shared Task]</li> <li>[[Language-Independent Named Entity Recognition](https://www.clips.uantwerpen.be/conll2003/ner/), CoNLL-2003 Shared Task]</li><li>[[Semantic Role Labeling](http://www.lsi.upc.edu/~srlconll/), CoNLL-2004 and CoNLL-2005 Shared Tasks]</li></ul> [[slides](https://www.overleaf.com/read/tzqhytkmsvtw)] |
||  | lab session | [[notes](https://www.overleaf.com/read/qtrdnthdmpdw)] [[ner data](https://buffalo.box.com/s/w3crjkoao09rk5f6hi46y5fpdk1bji8t)] [[crf template](https://buffalo.box.com/s/qggxvcbwjnwvj0f9z2l99qmsadkhiwg1)] |
|| Apr 1 | assignment #3 released	 | [[assignment #3](https://www.overleaf.com/read/wdfrxwmchfnv)]  (due by April 12, extended)|
|| Apr 3 | **syntax** | from *Speech and Language Processing* (3rd ed. draft) by Dan Jurafsky and James H. Martin |
|lecture|  | *syntactic parsing*  | [[Chap. 11](https://web.stanford.edu/~jurafsky/slp3/11.pdf)], [[slides](https://www.overleaf.com/read/vmczhbsgxrys)] |
|lecture|  | *statistical parsing*  | [[Chap. 12](https://web.stanford.edu/~jurafsky/slp3/12.pdf)], [[slides](https://www.overleaf.com/read/htxfvpqqbsdg)] |
|lecture|  | *dependency parsing*  | [[Chap. 13](https://web.stanford.edu/~jurafsky/slp3/13.pdf)], [[slides](https://www.overleaf.com/read/hvxxmrgqrhmp)] |
||  | lab session | [[notes](https://www.overleaf.com/read/qtrdnthdmpdw)] |
|| Apr 10 | assignment #4 released	 | [[assignment #4](https://www.overleaf.com/read/mbwfnkqtympc)] (due by Apr 22) |
|| Apr 15 | assignment #extra released	 | [[assignment #extra](https://www.overleaf.com/read/ncpdgwbykjmk)] for extra points (due by May 3) |
|| Apr 19 | assignment #5 released	 | [[assignment #5](https://www.overleaf.com/read/zjftsygpqnps)] (due by May 1, extended) |
| | Apr 23  | **cross-language** |  |
|lecture|  | *document/word alignment, mt*  | Suggested Readings:  <li> [<a href="http://www.aclweb.org/anthology/J93-1004">Sentence aligment</a>,] Gale and Church</li><li> [<a href="http://www.aclweb.org/anthology/J93-2003">Word alignment</a>, Brown et la., IBM models] </li><li> [<a href="http://www.statmt.org/book/">SMT book</a>, Koehn] </li> [[slides](https://www.overleaf.com/read/njtthzffdwnt)]  |
||  | lab session | [[notes](https://www.overleaf.com/read/qtrdnthdmpdw)] |
|| Apr 29 | assignment #6 released	 | [[assignment #6](https://www.overleaf.com/read/cxgptbvfbmyf)] (due by May 10) |
|| May 3 | recitation	 | [slides] |
||  | 2nd exams	 | on May 6-10:<ul><li>on 6: Syntax 1</li><li>on 8: Syntax 2</li> </ul> **ONLY one page cheat sheet is allowed** [[notes](https://www.overleaf.com/read/xccfyqtzrpkq)]   |




**introduction-to-computer-science-and-programming-in-python (MIT Open Courseware)** [[lecture videos](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-0001-introduction-to-computer-science-and-programming-in-python-fall-2016/lecture-videos/index.htm)]


**[Cross-Framework Meaning Representation Parsing at CoNLL 2019](http://mrp.nlpl.eu)**
July 29, 2019, Official End-to-End Evaluation Results
* DELPH-IN MRS Bi-Lexical Dependencies (Ivanova et al., 2012)
* Prague Semantic Dependencies (Hajič et al., 2012)
* Elementary Dependency Structures (Oepen & Lønning, 2006)
* Universal Conceptual Cognitive Annotation (Abend & Rappoport, 2013)
* Abstract Meaning Representation (Banarescu et al., 2013)


## office-hours
Fridays 9:00-10:00AM

## TA
Ali Mohammad A Alshehri (alimoham _at_ buffalo.edu)

## Student Volunteers for the extra assignment
* Meha Rajeev Raote (meharaje _at_ buffalo.edu)
* Pranjal Ashok Jain (pjain5 _at_ buffalo.edu)
* Alexander Pena (apena4 _at_ buffalo.edu)
