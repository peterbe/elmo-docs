.. index:: life

.. _life-chapter:

Life
====

`life <https://github.com/mozilla/elmo/tree/master/apps/life>`_ is the
app that defines the most fundamental models of elmo. It basically
reflects the state of translation work done and to be done. All other
applications depend on this app for interactions.

Let's delve into some of the key models:

Locale
------

Key fields:

* ``code`` - e.g. "nn-NO"
* ``name`` - e.g. "Norweigian (Nynorsk)"
* ``native`` - e.g. "Norsk nynorsk"

Every repository and every shipping signoff references a locale. It's

Changeset
---------

Key fields:

* ``revision`` - e.g. "9b2a99adc05e53cd4010de512f50118594756650"
* (TODO: any more "key" fields here?)
