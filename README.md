Project 64 reloaded
===================
Introduction
------------
Some good time ago Dean Thompson had a very valuable idea of collecting important documents from the previous era of computing in a "future proof" format and making them publicly available. He created a [website](http://project64.c64.org/) where he maintained the [archive](http://project64.c64.org/archive.htm) of important documents.

Obviously maintaining the website and updating all the documents is something that requires time and may quickly become a tedious job rather than hobby fun. Also - the formula of running a website, which has to be maintained the classic way didn't allow for fast-paced collaboration and updating the documents. Some people have since then accumulated many corrections to the content originating from Dean's website. Those ranged from corrections of simple typos/OCR errors up to corrections of real, conceptual errors. Unfortunately, for quite a long time those updated are nowhere to be sent as Dean's e-mail address presented on the page is long time invalid. Also Cris Berneburg's addresses no longer accept mail.

With the advent of online version control services like Github (and some earlier), things can change. This repository is meant to be publicly available and everyone can clone it, send pull request, etc. I also try to make it "loosely connected" to any person, especially myself. The owner of the repository is an "organisation" (in the sense of Gihub's terminology) called "Project-64" and can have multiple maintainers or can be transferred along with its whole content to another entity with ease.

Regards,

silverdr

Rules and Conventions
---------------------
Textual representations __only__ are to be stored and revision-maintained in this repository. Textual formats mean (in the order of preference):
* text/plain
* application/x-tex
* text/html
* text/rtf

Other, non-easily-editable formats are currently welcome only for inclusion in the list of documents awaiting to be processed into textual format.

The original Project 64 documents contain a header with several important points:
* The goal of Project 64 is to preserve Commodore 64 related documents in electronic text format that might otherwise cease to exist with the rapid advancement of computer technology and declining interest in 8-bit computers on the part of the general population.
* Extensive efforts were made to preserve the contents of the original document.  However, certain portions, such as diagrams, program listings, and indexes may have been either altered or sacrificed due to the limitations of plain vanilla text.  Diagrams may have been eliminated where ASCII-art was not feasible.  Program listings may be missing display codes where substitutions were not possible.  Tables of contents and indexes may have been changed from page number references to section number references. Please accept our apologies for these limitations, alterations, and possible omissions.
* The author(s) of the original document and members of Project 64 make no representations about the accuracy or suitability of this material for any purpose. This etext is provided "as-is". Please refer to the warrantee of the original document, if any, that may be included in this etext. No other warranties, express or implied, are made to you as to the etext or any medium it may be on. Neither the author(s) nor the members of Project 64 will assume liability for damages either from the direct or indirect use of this etext or from the distribution of or modification to this etext. Therefore if you read this document or use the information herein you do so at your own risk.

All of the above points remain valid and unaltered.

Some documents contain also one more header paragraph about the file format:
* Document names are limited to the 8.3 file convention of DOS. The first characters of the file name are an abbreviation of the original document name. The version number of the etext follows next. After that a letter may appear to indicate the particular source of the document. Finally, the document is given a .TXT extension.

This one is much more controversial.  God only knows how much I detest msdos and its "conventions",  which held computer science and the whole industry aback for more than a decade and still keep haunting us even today. I am - however - willing to bury my personal feelings about "8.3 file convention of DOS" and "extensions" (SCNR) for the sake of continuity and consistency. This means that:
* documents file names will remain limited to 8.3 uppercase characters
* version numbers for unaltered documents will remain as they were in the original archive
* version numbers of the documents updated within this repository will be bumped  by one minor number over the highest available and will remain so for its life in the repository
* If an updated version (with a higher version number than the originally used one) is found elsewhere and the changes are merged into the version available here - the version number will be updated accordingly

A line in the etext like
>MAPC6412.TXT, etext #351#. This replaces MAPC6411.TXT from June 1998

shall be used to distinguish and make it clear what document in what version it is updated from.
* new documents will adhere to the original file naming specifications (huh - is it really me writing this?) for consistency with the original project.

Unlike Dean I don't exclude possibility of accepting documents, which originated in languages other than English. Usually original language versions are in fact better than the translations. An example: "Das Große Floppybuch zur 1541", written originally by German authors and translated into English. While the English version (published by Abacus Software under the title "The Anatomy Of The 1541 Drive - A Complete Guide to Using The Commodore Disk Drive) is surprisingly good, I still have this kind of feeling that German book is somehow better. No, German is not my mother tongue.. ;-)
