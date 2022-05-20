\<English follows Marathi\>

पायथन प्रोग्रामिंग भाषेच्या कागदपत्रांचे मराठीत स्थानिकीकरण (भाषांतर)
============================================

पायथन प्रोग्रामिंग भाषेची मदतपत्रे मराठीत उपलबध करून देण्यासाठी एक जनयोगदान उपक्रम.

का?
---

पायथन ही सॉफ्टवेर क्षेत्रातील अतिशय महत्वपूर्ण व उपयुक्त प्रोग्रामिंग भाषा आहे.

पायथन प्रोग्रामिंग शिकण्यासाठी इंटरनेटवरील साहित्य हे जास्तकरून इंग्रजी भाषेत उपलब्ध आहे. ह्यामुळे इंग्रजी येत नसणाऱ्यांना ते समजणे कठीण जाते. ह्याचा परिणाम म्हणजे प्रोग्रामिंग शिकण्याच्या व पुढे जाऊन त्यात काम करण्याच्या संधी पासून ते दुरावतात. अशा वेळी जर ही माहिती आपल्याला सहजपणे समजणाऱ्या मातृभाषेत उपलब्ध असेल तर शिकणे सोपे होऊन जाते. परदेशात, प्रथम भाषा ही इंग्रजी नसणाऱ्या (उदा. जपान, चीन, फ्रान्स, जर्मनी इ.) देशांत, असे उपक्रम तिथल्या स्थानिक लोकांनी राबवून बऱ्याच सॉफ्टवेरची माहिती त्यांच्या मातृभाषेत उपलब्ध करून ठेवली आहे. त्यामुळे तिथले विद्यार्थी/अभियंते इंग्रजीत सक्षम नसूनही सॉफ्टवेर क्षेत्रात सक्षम होतात. परंतु भारतात, दुर्दैवाने, सॉफ्टवेर क्षेत्रात प्रवेश करायलाच प्रथम इंग्रजीचा बांध ओलांडावा लागतो.

थोडक्यात, इंग्रजी येत नसणाऱ्या लोकांना प्रोग्रामिंग शिकायला मदत व्हावी ह्यासाठी हा उपक्रम राबवला आहे.

काय?
-----

**सध्याचे ध्येय** : खाली दिलेल्या ३ गोष्टींचे अनुवाद पूर्ण करणे.

- ``tutorial/`` - ह्या फोल्डर मध्ये अभ्यास-सत्र संबंधित १७ फायलीत एकूण ८७२ सूत्र आहेत.
- ``library/functions.po`` - ह्या फायलीत एकूण ३७८ सूत्र आहेत.
- ``bugs.po`` - ह्या फायलीत एकूण २८ सूत्र आहेत.

हे पूर्ण झाले की मराठी मदतपत्रे https://docs.python.org/ ह्या अधिकृत संकेतस्थळावर उपलब्ध होतील.

कसे?
-------

ह्यात ३ पाऊले आहेत -

1. हा *रेपो* (स्त्रोत फाईलींचा साठा) मिळवणे
2. अनुवाद करणे
3. अनुवादित फाईली *रेपो* मध्ये विलीन करणे

ही ३ पाऊले खाली थोडक्यात समजावली आहेत. (तपशीलवार सूचना/मार्गदर्शन नंतर जोडले जाईल.)
तसेच, ह्या प्रत्येक पावलात, वेगवेगळे मार्ग आहेत जे तुम्ही सोयीनुसार निवडू शकता.

१. रेपो मिळवणे
  पर्याय १ - GitHub वर खाते उघडून हा *रेपो* *फोर्क* करणे. (`कसे करायचे? <https://github.com/firstcontributions/first-contributions/blob/master/translations/README.mr.md>`_)
  
  पर्याय २ - GitHub वरून ह्या *रेपो* ची ``.zip`` `फाईल <https://github.com/sanketgarade/python-doc-mr/archive/refs/heads/main.zip>`_ तुमच्या संगणकावर डाउनलोड करून ती उघडणे.
  
  पर्याय ३ - GitHub वरून मी तुम्हाला अनुवादासाठी आवश्यक फाईली (``.po``) ई-मेल द्वारे पाठवणे.

२. अनुवाद करणे
  अनुवाद करण्यासाठी आपल्याला ``.po`` फाईली संपादित (एडिट) करायचा आहेत.

  पर्याय १ - ऑनलाईन संपादन
    तुम्ही जर GitHub वर खाते तयार केले असेल तर तुम्ही थेट ब्राउझर मधून फाईल संपादित करू शकता.

  पर्याय २ - ऑफलाईन संपादन
    ``.po`` फाईलींचे विशेष संपादक `poedit <https://poedit.net/>`_ हे वापरणे सोपे जाईल.
    तसेच, ``.po`` फाईल ही एक साधी मजकूर फाईल असल्यामुळे कोणत्याही मजकूर संपादकात (उदा. विंडोजवरील वरील ``notepad.exe`` मध्ये) ती उघडून तिच्यात बदल करता येतो. अश्यावेळी ``.po`` फाईलीची संरचना समजणे आवश्यक आहे. "इतर" विभागात थोडक्यात समजावली आहे.

३. अनुवादन विलीन करणे
  पर्याय १ - GitHub वरून काम करत असाल तर "खेच विनंती" (*पूल रिक्वेस्ट*) मार्गे विलीन करणे

  पर्याय २ - GitHub च्या बाहेर संपादित केलेल्या फाईली ई-मेल द्वारे मला पाठवणे. मग, मी ते github मध्ये चढवून विलीन करणे.

तर असे हे ३ पावलांमध्ये आपले काम करणे सोपे आहे. आता वाट पाहू नका, लवकर योगदान करून आपण ही माहिती मराठीत उपलब्ध करूया! काही प्रश्न असल्यास मला (इथे `नवीन मुद्दा नोंदवून <https://github.com/sanketgarade/python-doc-mr/issues>`_ किंवा `ई-मेल <mailto:garade@pm.me>`_ द्वारे) विचारा. तुम्हाला मदत करायला मला आनंद होईल. 

इतर
----

``.po`` फाईलीत एका सूत्राची रचना साधारणपणे अशी असते -

::  

  #: tutorial/introduction.rst:224
  msgid ""
  "This feature is particularly useful when you want to break long strings::"
  msgstr ""
  "लांब सूत्रे तोडण्यासाठी ह्या वैशिष्ट्याचा विशेष उपयोग होतो::"

इथे ``msgid`` समोर किंवा खालच्या ओळींवर लिहिलेले सूत्र हे इंग्रजीतील स्त्रोत सूत्र असते, तसेच ``msgstr`` समोर किंवा खालच्या ओळींवर लिहिलेले सूत्र हे इष्ट (इच्छुक) सूत्र असते (जे की आपल्या बाबतीत मराठीत असेल). 


-------------
\<English section from here\>

Translation of the Python Documentation — mr
============================================

.. image:: https://travis-ci.org/python/python-docs-mr.svg?branch=3.7
  :target: https://travis-ci.org/python/python-docs-mr


Documentation Contribution Agreement
------------------------------------

NOTE REGARDING THE LICENSE FOR TRANSLATIONS: Python's documentation is
maintained using a global network of volunteers. By posting this
project on Transifex, Github, and other public places, and inviting
you to participate, we are proposing an agreement that you will
provide your improvements to Python's documentation or the translation
of Python's documentation for the PSF's use under the CC0 license
(available at
https://creativecommons.org/publicdomain/zero/1.0/legalcode). In
return, you may publicly claim credit for the portion of the
translation you contributed and if your translation is accepted by the
PSF, you may (but are not required to) submit a patch including an
appropriate annotation in the Misc/ACKS or TRANSLATORS file. Although
nothing in this Documentation Contribution Agreement obligates the PSF
to incorporate your textual contribution, your participation in the
Python community is welcomed and appreciated.

You signify acceptance of this agreement by submitting your work to
the PSF for inclusion in the documentation.


Contributing to the Translation
-------------------------------

How to Contribute
~~~~~~~~~~~~~~~~~

You can contribute using:

- Github
- `transifex <https://www.transifex.com/python-doc/public/>`_
- Or just by opening `an issue on github <https://github.com/python/python-docs-mrfr/issues>`_


Contributing using Github
~~~~~~~~~~~~~~~~~~~~~~~~~

Prerequisites:

- A `github account <https://github.com/join>`_.
- ``git`` `installed <https://help.github.com/articles/set-up-git/>`_ (for windows, see
  https://gitforwindows.org/).
- A ``.po`` file editor (Use `poedit <https://poedit.net/>`_
  if you don't already have one).


Let's start:

You'll need to fork the `python-docs-mr
<https://github.com/python/python-docs-mr>`_ clicking its ``Fork``
button. This creates a copy of the whole project on your github
account: a place where you have the rights to do modifications.

Step by step:

.. code-block:: bash

    # Git clone your github fork using ssh (replace JulienPalard):
    git clone git@github.com:JulienPalard/python-docs-mr.git

    # Go to the cloned directory:
    cd python-docs-mr/

    # Add the upstream (the public repository) using HTTPS (won't ask for password):
    git remote add upstream https://github.com/python/python-docs-mr.git

All the translations must be made on the latest release.
We never translate on an oldest version, by example, the latest python release
is python 3.7, we don't want to translate directly on the python 3.5 release.
If needed translations would be backported on the oldest versions by the
`documentation team <https://www.python.org/dev/peps/pep-8015/#documentation-team>`_.

Now you're ready to start a work session, each time you'll start a new task, start here:

.. code-block:: bash

    # To work, we'll need a branch, based on an up-to-date (freshly fetched)
    # upstream/3.7 branch, let's say we'll work on glossary so we name
    # the branch "glossary":
    git fetch upstream
    git checkout -b glossary upstream/3.7

    # You can now work on the file, typically using poedit,
    poedit directory/file.po

    # When everything is clear (syntax errors from Sphinx, html rendering,
    # semantics, typography),
    # you can commit your work with a nice explicit message:
    git commit -a -m "Working on glossary."

    # Then push your modifications to your github clone,
    # as they are ephemeral branches, let's not configure git to track them all,
    # "origin HEAD" is a "special" syntax to say "Push on origin,
    # on a branch with the same name as the local one",
    # it's nice as it's exactly what we want:
    git push origin HEAD

    # The previous command will print you a link to open a PR on github.
    # If you missed it, just go to
    # https://github.com/python/python-docs-mr/ and a nice "Compare & pull request"
    # button should appear after a few seconds telling you can ask for a pull request.

    # Now someone is reviewing your modifications, and you'll want to fix their
    # findings, get back to your branch
    # (in case you started something else on another branch):
    git checkout glossary
    # Fix the issues, then commit again:
    git commit -a -m "glossary: small fixes."
    git push origin HEAD


You may have noted that this looks like a triangle, with a missing segment:

- You're fetching from upstream (public common repo on github)
- You're pushing to origin (your clone on github)

So yes it's the work of someone to add the last segment, from your
origin to the public upstream, to "close the loop", that's the role of
the people who merges pull requests after proofreading them.

You may also have noted you never ever commit on a version branch
(``3.6``, ``3.7``, ...), only pull from them, consider them read-only
you'll avoid problems.


What to translate
~~~~~~~~~~~~~~~~~

You can start with easy tasks like reviewing fuzzy entries to help
keeping the documentation up to date (find them using ``make fuzzy``).

You can also proofread already translated entries, and finally
translate untranslated ones (find them using ``make todo``)..

- Do not translate content of ``:ref:...`` and ``:term:...``
- Put english words, if you have to use them, in *italics* (surrounded
  by stars).
- If you translate a link title, please translate the link too
  (typically if it's Wikipedia and the article has a translation). If
  no translation of the target exists, do not translate the
  title.


Where to get help
~~~~~~~~~~~~~~~~~


Translation Resources
---------------------


Glossary
--------

For consistency in our translations, here are some propositions and
reminders for frequent terms you'll have to translate, don't hesitate
to open an issue if you disagree.

To easily find how a term is already translated in our documentation,
you may use
`find_in_po.py <https://gist.github.com/JulienPalard/c430ac23446da2081060ab17bf006ac1>`_.

**टीप : TBD = to be decided = अजून ठरवायचे आहे**

========================== ===========================================
Term                       Proposed Translation
========================== ===========================================
-like                      -सम
abstract data type         अमूर्त डेटा प्रकार
argument                   कोनांक
backslash                  बॅकस्लॅश
bound                      बद्ध
bug                        बग/किडा TBD
built-in                   अंगभूत
call stack                 कॉल स्टॅक context TBD
debugging                  दोषनिवारण
deep copy                  खोल प्रत context TBD
double quote               दुहेरी अवतरण
e.g.                       उदा.
garbage collector          कचरा संग्रही
identifier                 ओळखकर्ता
immutable                  अपरिवर्तनीय
installer                  इंस्टॉलर
interpreter                संकेतवाचक
library                    लायब्ररी
list comprehension         यादी आकलन context TBD
little-endian, big-endian  लहान-अंत्य, मोठे-अंत्य
mutable                    परिवर्तनीय
namespace                  नेमस्पेस
parameter                  पॅरामीटर
prompt                     कान
raise                      वाढ context TBD
regular expression         नियमित पदावली
return                     परत context TBD
simple quote               साधे अवतरण
socket                     सॉकेट
statement                  विधान
subprocess                 उपप्रक्रिया
thread                     धागा
underscore                 अधोरेख
expression                 पदावली
========================== ===========================================

Simplify git diffs
------------------

Git diffs are often crowded with useless line number changes, like:

.. code-block:: diff

    -#: ../Doc/library/signal.rst:406
    +#: ../Doc/library/signal.rst:408

To tell git they are not usefull information, you can do the following
after ensuring ``~/.local/bin/`` is in your ``PATH``.

.. code-block:: bash

    cat <<EOF > ~/.local/bin/podiff
    #!/bin/sh
    grep -v '^#:' "\$1"
    EOF

    chmod a+x ~/.local/bin/podiff

    git config diff.podiff.textconv podiff


Maintenance
-----------

All those snippets are to run from the root of a ``python-docs-mr``
clone, and some expect to find an up-to-date CPython clone near to it,
like:

.. code-block:: bash

  ~/
  ├── python-docs-mr/
  └── cpython/

To clone CPython you may use:

.. code-block:: bash

  git clone --depth 1 --no-single-branch https://github.com/python/cpython.git

This avoids to download the whole history (not usefull to build
documentation) but still fetches all branches.


Merge pot files from CPython
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. code-block:: bash

  make merge


Find fuzzy strings
~~~~~~~~~~~~~~~~~~

.. code-block:: bash

  make fuzzy


Run a test build locally
~~~~~~~~~~~~~~~~~~~~~~~~

.. code-block:: bash

  make


Synchronize translation with Transifex
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You'll need the ``transifex-client`` and ``powrap``
from Pypi.

You'll need to configure ``tx`` via ``tx init`` if not already done.

.. code-block:: bash

   pomerge --from-files **/*.po
   tx pull -f
   pomerge --to-files **/*.po
   pomerge --from-files **/*.po
   git checkout -- .
   pomerge --to-files **/*.po
   powrap --modified
   git commit -m "tx pull"
   tx push -t -f
