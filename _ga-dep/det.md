---
layout: relation
title: 'det'
shortdef: 'determiner'
---

The `det`label marks the relationship between a noun and its determiner.

In Irish there is no indefinite article, only a definite article. The definite article can be singular (_an_) or plural (_na_).

_<b>an</b> clár_ '<b>the</b> programme'

~~~ sdparse
an clár \n the programme
det(clár, an)
~~~

_<b>an</b> cláranna_ '<b>the</b> programmes'
~~~ sdparse
na cláranna \n the programmes
det(cláranna, na)
~~~


 Two pre-determiners can occur before a noun:

_<b>gach uile</b> ábhar \n <b>every single</b> subject

~~~ sdparse
gach uile ábhar \n every single subject 
det(ábhar, gach)
det(ábhar, uile)
~~~

Two determiners can be used each side of a noun: pre-determiners and post-determiners:

_<b>an</b> tuairim <b>sin</b> '<b>that</b> opinion'  (_an+sin_ = 'that')

~~~ sdparse
an tuairim sin \n the opinion DEM
det(tuairim, an)
det(tuairim, sin)
~~~

<b>an</b> leabhar <b>úd</b> '<b>that</b> book

~~~ sdparse
an leabhar úd \n the book DEM
det(leabhar, an)
det(leabhar, úd)
~~~

<b>an</b> alt <b>seo</b> '<b>this</b> paragraph'

~~~ sdparse
an alt seo \n the paragraph DEM
det(alt, an)
det(alt, seo)
~~~

<b>an chéad</b> cheannaire <b>eile</b> '</b>the next</b> leader'

~~~ sdparse
an chéad cheannaire eile \n the first leader other
det(cheannaire, an)
det(cheannaire, eile)
quant(cheannaire, chéad)
~~~

