---
title: "Retrieving Lexile Levels in R"
tags: ["R", "education", "data", "text"]
date: 2017-04-28
---

<div dir="ltr" style="text-align: left;" trbidi="on">
For those that don't work in education or aren't aware, there is a measurement for a child's reading level called a <a href="https://lexile.com/" target="_blank">Lexile ® Level</a>. &nbsp;There are ways in which this level can be retrieved using different reading assessments. &nbsp;The measurement can be used to match a child's reading level to books that are the same level. &nbsp;So the company maintains a database of books that they have assigned levels. &nbsp;There are other assessments that measure how well a child is reading, but I'm not aware of any systems that assign books as comprehensively. &nbsp;The library at the school I work at lacked <a href="https://lexile.com/" target="_blank">Lexile Levels</a> for their books. &nbsp;This is unfortunate because of the fact that teachers are not able provide students with books for their respective Lexile Level. &nbsp;Fortunately though the library had a list of ISBNs for the books.<br />
<br />
On the <a href="https://lexile.com/" target="_blank">Lexile website</a>&nbsp;there is a way to search for books using ISBN numbers to retrieve their Lexile&nbsp;®&nbsp;Level if the book is available in their database. &nbsp;Entering every ISBN number available is a task fit for something not human. <br />
<br />
<a href="https://cran.r-project.org/web/packages/rvest/rvest.pdf" target="_blank">rvest</a> to the rescue. <br />
<br />
Below is the script to retrieve the Lexile Levels of books if a list of ISBNs is available. &nbsp;This was an incredible time save provided by some R code and hopefully someone else out there could use it.<br />
&nbsp; <br />

<a href="https://github.com/justlebeau/Blog-Code/blob/master/LexileLevelScrape.R" target="_blank">Link to code</a><br />
<br />
<br /></div>

