Auto Multiple Choice (AMC) for Moodle
=====================================

### Updated at 20200628 By A. DAAIF
### Hassan II University of Casablanca
### Forked from : 
[UGA-DAPI](https://github.com/UGA-DAPI/moodle-mod-automultiplechoice) repository.

This is an interface to use [AMC](http://home.gna.org/auto-qcm/) within Moodle.

This Moodle module is intended for use with the moodle-local-questionssimplified module.
It handles the paper quizzes built from Moodle multiple-choice questions,
while the other module provides a simple interface to type these questions.

It is also recommended to install the filter module moodle-filter-amc.

This module was created for the *service TICE de l'Université Pierre-Mendès-France - Grenoble 2, Sciences sociales et humaines*.

Features
--------

An admin can:

* Define complex scoring rules.
* Define how to match a student number from the paper test to a student number in Moodle.
* Define various default text for paper tests.

A teacher can:

* Configure various [AMC](https://www.auto-multiple-choice.net/) parameters (randomization, etc).
* Select questions and assign a number of points to each one.
* Select a scoring rule.
* Configure various texts that appear on print sheets.
* Prepare PDF question sheets and answer sheets.
* Upload the scanned answer shhets and automatically grade them.
* See the grades in Moodle or download them.
* Download graded copies with PDF annotations.

### Warning

The interface is not fully localized.
There will be French texts here and there.


Requirements
------------

Here are the requirements :

* auto-multiple-choice 1.4.0
* Moodle 2020061500
* Tested in Ubuntu 20.04

Issues & todo
------
*  ~~Students access to there annotated copies~~
* Students notifications

Don't forget to install the associated plugin **moodle-local-questionssimplified** and the filter **moodle-filter-amc**

Installation
------------

Put the source directory under the `mod/` path of a Moodle instance.

```
cd /path/to/moodle
cd mod
git clone https://github.com/daaif/amc.git automultiplechoice
```

Then connect as an admin, and Moodle will complete the installation.


License
-------
GPL v3

