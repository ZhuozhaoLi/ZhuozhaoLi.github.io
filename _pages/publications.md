---
layout: page
permalink: /publications/
title: Publications
description: A full list of my publications can be found on <u><a href="https://scholar.google.com/citations?user=CbH_SlcAAAAJ&hl=en" target="\_blank">Google Scholar</a></u> and <u><a href="https://dblp.org/pid/148/1926.html" target="\_blank">dblp</a></u>. <!-- <br> Authors with an underscore "_" are students/scholars mentored by me.--> <br><u><a href="#journal">Journal Publications,</a></u> <u><a href="#conference">Conference Publications,</a></u> <u><a href="#preprint">Preprints</a></u>.
years: [2022, 2012]
nav: true
---

<div class="publications">

<a id="journal"><h1 class="bibliography">Journal Publications</h1></a>

{% bibliography -f papers -q @article[status!=arXiv] --group_by year --group_order descending %}

<a id="conference"><h1 class="bibliography">Conference Publications</h1></a>

{% bibliography -f papers -q @inproceedings --group_by year --group_order descending %}

<a id="preprint"><h1 class="bibliography">Preprints</h1></a>

{% bibliography -f papers -q @article[status=arXiv] --group_by year --group_order descending %}

<h1 class="bibliography">Thesis</h1>

{% bibliography -f papers -q @phdthesis --group_by year --group_order descending %}



</div>
