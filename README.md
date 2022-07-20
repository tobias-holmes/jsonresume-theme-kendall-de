# jsonresume-theme-kendall-de

This is a German translated fork of M. Adam Kendall's original [jsonresume-theme-kendall](https://github.com/LinuxBozo/jsonresume-theme-kendall/blob/master/README.md). Please contact M. Adam Kendall directly for any issues which are not related to the German translation.

## Changes made

* translation of relevant English terms into German
* adoption of address layout to German standards
* commented out volunteer section in index.js as I personally had no use for it

Note that even though it is mentioned in the original project that

> Every section is optional. If you do not include the publications array in your resume.json, no publications section will appear.

I experienced that this is not true for the volunteer section. Deleting the volunteer section in the resume.json file lead to errors. As a quick fix I therefore disabled it by commenting it out in the index.js file. Should you have use for it please uncomment it again.

"Grade" in the section awards was translated to "Abschluss". This allows besides grades also certificates or other distinctions.

Regarding the usage of the theme I refer to the original project instructions of [M. Adam Kendall](https://github.com/LinuxBozo/jsonresume-theme-kendall) and the ones of [jsonresume.org](https://jsonresume.org/) in general.
