Deedy-Resume
=========================

A **one-page**, **two asymmetric column** resume template in **XeTeX** that caters particularly to an **undergraduate Computer Science** student.
As of **v1.2**, there is an option to choose from two templates:

1. **MacFonts** - uses fonts native to OSX - *Helvetica*, *Helvetica Neue* (and it's Light and Ultralight versions) and the CJK fonts *Heiti SC*, and *Heiti TC*. The EULA of these fonts prevents distribution on Open Source.
2. **OpenFonts** - uses free, open-source fonts that resemble the above - *Lato* (and its various variants) and *Raleway*.

It is licensed under the Apache License 2.0.

## Motivation

Common LaTeX resume-builders such as [**moderncv**](http://www.latextemplates.com/template/moderncv-cv-and-cover-letter)  and the [**friggeri-cv**](https://github.com/afriggeri/cv) look great if you're looking for a multi-page resume with numerous citations, but usually imperfect for making a thorough, single-page one. A lot of companies today search resumes based on [keywords](http://www.businessinsider.com/most-big-companies-have-a-tracking-system-that-scans-your-resume-for-keywords-2012-1) but at the same time require/prefer a one-page resume, especially for undergraduates. 

This template attempts to **look clean**, highlight **details**, be a **single page**, and allow useful **LaTeX templating**.

## Dependencies

1. Compiles only with **XeTeX** and required **BibTex** for compiling publications and the .bib filetype.
2. Uses fonts that are usually only available to **Mac** users such as Helvetica Neue Light.

## Changelog
### v1.2
 1. Added publications in place of societies.
 2. Collapsed a portion of education.
 3. Fixed a bug with alignment of overflowing long last updated dates on the top right. 

### v1.1
 1. Fixed several compilation bugs with \renewcommand
 2. Got Open-source fonts (Windows/Linux support)
 3. Added Last Updated
 4. Moved Title styling into .sty
 5. Commented .sty file.

## TODO
1. Merge OpenFont and MacFonts as a single sty with options.
2. Figure out a smoother way for the document to flow onto the next page.
3. Add styling information for a "Projects/Hacks" section.
4. Add location/address information
5. Fix the hacky 'References' omission outside the .cls file in the MacFonts version.
6. Add various styling and section options and allow for multiple pages smoothly.

## Known Issues:
1. Overflows onto second page if any column's contents are more than the vertical limit
2. Hacky space on the first bullet point on the second column.
3. Hacky redefinition of \refname to omit 'References' text for publications in the MacFonts version.

