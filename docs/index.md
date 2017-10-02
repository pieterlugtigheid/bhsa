---
title: Home
type: pages
---

![etcbc](images/etcbc.png)

## Biblia Hebraica Stuttgartensia (Amstelodamensis)

This is the
[text-fabric](https://github.com/ETCBC/text-fabric/wiki)
version of the Hebrew Bible Database,
containing the text of the Hebrew Bible augmented with linguistic annotations compiled by the
[Eep Talstra Centre for Bible and Computer](http://www.godgeleerdheid.vu.nl/en/research/institutes-and-centres/eep-talstra-centre-for-bible-and-computer/index.aspx), VU University Amsterdam.

The text is based on the
[Bibila Hebraica Stuttgartensia](https://www.academic-bible.com/en/online-bibles/biblia-hebraica-stuttgartensia-bhs/read-the-bible-text/)
edited by Karl Elliger and Wilhelm Rudolph,
Fifth Revised Edition, edited by Adrian Schenker,
© 1977 and 1997 Deutsche Bibelgesellschaft, Stuttgart.

The [text-fabric](https://github.com/ETCBC/text-fabric/wiki) version has been prepared
by Dirk Roorda [Data Archiving and Networked Services](https://dans.knaw.nl/en/front-page?set_language=en),
with thanks to
Martijn Naaijer,
[Cody Kingham](http://www.codykingham.com)
and Constantijn Sikkel.

## Provenance
The source data resides on a server of the ETCBC, managed by Constantijn Sikkel.
He makes that data available as an [MQL](https://emdros.org/mql.html) database dump, `bhs4.mql`,
together with supplementary data files.
From there it is transported to this Github repo by means of a [pipeline](https://github.com/ETCBC/pipeline).

This dataset contains versions of the BHSA.
When you navigate to a version, you'll see more information about that version and its provenance.


For versions **c** and **2016** the
[pipeline](https://github.com/ETCBC/pipeline)
has been followed.
These versions have not be enriched with data coming from research repos.
Instead, additional data from research repos can easily downloaded
from github and be processed alongside the core data.

## Workflow
The pipeline above is complicated and not free of
[cruft](https://en.wikipedia.org/wiki/Cruft).
It would be better if the ETCBC could deliver its core data directly in text-fabric format,
with inclusion of the lexical features, the ketiv-qere data and the paragraph numbers.

## Reproducible science
We intend to follow a practice that allows for data updates on the one hand, and reproduction of old
results on the other.

Besides the continously changing version `c`, we have the fixed, year-bound versions.
In SHEBANQ, 
it will not be possible to publish queries and annotations executed against the `c` version.
It is likely that they will break, when version `c` is modified, week after week.
So, saved queries against this version are not guaranteed to show their original results.

For reliable query saving, every one or two years a new fixed version, called `2017`, `2019`, ... will be added
to SHEBANQ.

Fixed versions in SHEBANQ will remain there forever, and publishing queries and annotations against fixed
versions will remain supported.

In particular, versions `4` and `4b` are here to stay, since they have published queries based on them.
These versions are also firmly entrenched in the academic record, by virtue of being archived.

## License

This work is licensed under a
[Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/).
That means:

* You may download the data and use it: process, copy, modify;
* You may use the data to create new software applications;
* You may use the data for research and publish any amount of results;
* When you publish this data or results you obtained from them, you have to comply with the following:
  * give proper attribution to the data when you use it in new applications,
    by citing this persistent identifier:
    [10.17026/dans-z6y-skyh](http://dx.doi.org/10.17026%2Fdans-z6y-skyh).
  * do not use the data for commercial applications without consent;
    for any commercial use, please contact the
    [German Bible Society](zentrale@dbg.de).

# How to use

This data can be processed by 
[Text-Fabric](https://github.com/ETCBC/text-fabric/wiki).

See also 
[tutorial (Hebrew)](https://github.com/etcbc/text-fabric/blob/master/docs/tutorial.ipynb)
and
[tutorial (search)](https://github.com/etcbc/text-fabric/blob/master/docs/searchTutorial.ipynb).
