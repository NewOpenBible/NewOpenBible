 the NewOpenBible
==================

our aim is to empower the people of the World to create a modern translation of the Bible that everyone can use in their own language, free from all copyright encumbrances, and as faithful to the original languages of the text as modern scholarship can enable us

to help us in this endeavor, we are re-using existing texts in the public domain as our starting point and build upon these with modern emendation guided by state-of-the-art advancement in Bible scholarship

we also want to make inline references to Strong's concordance possible for advanced readers, which will also serve us with internal consistency and self-verifiability of the translated texts with their corresponding original languages, we will do this as version 1.0 approaches release

technical notes
---------------
our efforts are inspired specifically by the hard work, scholarship and eloquence of previous translations:
* New Revised Standard Version of 1989 (especially *the Common Bible* edition for all Christians);
* New American Standard Bible of 1995; and
* New English Translation of 2005

our guiding original text references are:
* Westminster [Codex Leningradensis](http://en.wikipedia.org/wiki/Leningrad_Codex)
* [Dead Sea Scrolls Digital Library](http://dss.collections.imj.org.il/), the [Leon Levy](http://www.deadseascrolls.org.il/?locale=en_US) online archives
* Novum Testamentum Graece, [Nestle-Aland](http://en.wikipedia.org/wiki/Novum_Testamentum_Graece) 28th edition

the NewOpenBible will draw upon available texts in the public domain from two independent traditions:
 1. the [American Standard Version](http://en.wikipedia.org/wiki/American_Standard_Version) (**ASV**) released 1901, whose former copyright has now expired so it is in the public domain and free to be published without payment of royalty---
   * a free updated revision is the [World English Bible](http://WorldEnglishBible.org) (**WEB**), one of the two most popular public domain, modern-English translations of the entire Bible and freely distributed to the public using electronic formats; and,
 2. the [Open English Bible](http://OpenEnglishBible.org) (**OEB**) derived from the public domain Twentieth Century New Testament (TCNT) based on "The New Testament in the Original Greek" by [Westcott and Hort](http://en.wikipedia.org/wiki/Westcott-Hort) in 1881, and the public domain translations of the Hebrew Bible done by John E McFadyen and Charles F Kent based on the Westminster online digital copy of the [Codex Leningradensis](http://en.wikipedia.org/wiki/Leningrad_Codex) maintained by the J. Alan Groves Center for Advanced Biblical Research at the Westminster Theological Seminary

guidelines
----------
* we will avoid unnecessary interpretation: ambiguous cultural, linguistic or technical references in the original will be preserved for the readers consideration with appropriate notes;
* most of all, we shall not diminish the divine glory and supreme authority of God as witnessed by the original scriptures; and,
* we will proclaim how God is fulfilling His promises in the good news of our Lord Jesus Christ


This site
---------
This source tree contains:

final-usfm/
The final generated usfm. This is probably what you want if you want to use the NewOpenBible usfm files.

source/
These are the OpenEnglishBible.org source files we are working from. They are USFM files with a layer of markup to handle variations.

src-usfm/
These are the other source files we are working from (NOT from the OEB, but all in the public domain /CC0) originating from the ASV to modern emendations contributed by the WEB

scratch/
These are various support documents such as books not yet fit for the development version.

build.py
The python 2.x script which creates a set of USFM files from the usfm.db files

build-standard.sh
Shell script which builds the two main sets of USFM files in final-usfm/us and final-usfm/cth


## license / copyright status
[![creative commons Attribution-ShareAlike License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png "creative commons Attribution-ShareAlike License")](http://creativecommons.org/licenses/by-sa/4.0/)

all content and text source files used are in the public domain in the original, they are modified and released here under the [creative commons Attribution-ShareAlike License 4.0](http://creativecommons.org/licenses/by-sa/4.0/), [3.0 international](http://creativecommons.org/licenses/by-sa/3.0/) and [PH-adapted local license](http://creativecommons.org/licenses/by-sa/3.0/ph/) and all further changes here are made available in the same free license (Attribution-ShareAlike License) for the sole purpose of availability and preserving freedom to use and share content, including transclusion in other relevant media under the same or any compatible license, the license used should never be construed to restrict or diminish any natural or legal right to use these sources as presented here, when in doubt, the essential freedom granted to use these sources shall be interpreted to mean:
 * as defined by Attribution-ShareAlike License [3.0 PH](http://creativecommons.org/licenses/by-sa/3.0/ph/) under Philippine jurisdiction; or,
 * as defined by Attribution-ShareAlike License [4.0 (international)](http://creativecommons.org/licenses/by-sa/4.0/) anywhere else in the World..
copies of which are also hereby attached as [LICENSE](https://github.com/NewOpenBible/NewOpenBible/blob/master/LICENSE.markdown) files for easy reference

the Word of God spans millennia of Human History and we believe the message that frees all of us should as well be free from all arbitrary and artificial restriction in its translation and distribution

the GitHub repository contains backend source code (primarily Python scripts and associated documentation) used in transforming the source files to formatted content, which is copyright (c) 2010-2013 Russell Allen and available under the BSD licence, a copy of which is available at http://creativecommons.org/licenses/BSD/


## contributing
changes and improvements are more than welcome! Feel free to fork and open a pull request

you can open issues for meta-changes, feedback or additional perspective regarding this project

all contribution and communication on GitHub will be released in the same **creative commons Attribution-ShareAlike License** stated above ([4.0](http://creativecommons.org/licenses/by-sa/4.0/), [3.0 international](http://creativecommons.org/licenses/by-sa/3.0/) +[PH-adapted local license](http://creativecommons.org/licenses/by-sa/3.0/ph/)) for the Bible texts, and [BSD-license](http://creativecommons.org/licenses/BSD/) for the scripts and source code, unless otherwise indicated
