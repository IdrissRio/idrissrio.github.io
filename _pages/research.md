---
title: "Reserach"
layout: gridlay
sitemap: false
permalink: /research/
---

<style>
img{
  border-radius: 10px;
}
iframe {
  width: 175px;
  display: inline;
  vertical-align:middle;
  <!-- margin-bottom:5px; -->
  <!-- margin-left:5px; -->
  <!-- border: 1px solid red; -->
}
.col-md-3 {
  margin:0;
  padding:0;
  margin-top:10px;
  margin-bottom:10px;
  display:block;
  overflow:hidden;
  text-align:center;
  display: table-cell;
  height: auto;
  float: none;
  background:white;
  border-radius:20px;
  <!-- border: 1px solid black; -->
}

.imgfit{
  width: 500px;
  height: 200px;
  object-fit: contain;
}
</style>

## Research @Lund University

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">





## JFeature

We started analysing some Java projects taken from the DaCapo corpus to evaluate the precision
of IntraJ on Java 8 projects. 
After a while, I realised there are no Java 8 projects in the DaCapo Benchmark Suite. So, I started 
looking at more corpora (yes, not corpuses), and we realised that the most used corpora in Static Analysis don't include Java 8 projects at all. I needed to find Java 8 projects that heavily use 
all Java 8 features, e.g., Lambda Expressions, Intersection Cast, Default, Method and Constructor references.

I started looking at the literature, and I found nothing. I found no paper nor source-level tool able to extract this kind of information. I thought: "Good opportunity to do something new". I pressed pause on the IntraJ project and I started with JFeature. 

<p align="center">
  <img width="700"  src="{{ site.url }}{{ site.baseurl }}/images/conferences/jfeature/main_results.png">
</p>





## IntraJ 

<p align="center">
  <img width="300"  src="{{ site.url }}{{ site.baseurl }}/images/conferences/intraj/logo.png">
</p>


---

**IntraJ** is an application of the language independent framework **[IntraCFG](https://github.com/lu-cs-sde/IntraCFG)** for the Java language, build as an extension of the **[ExtendJ](https://extendj.org)** Java Compiler. More details can be found in the following paper:
* __[A Precise Framework for Source-Level Control-Flow Analysis](https://ieeexplore.ieee.org/document/9610697)__, _[Idriss Riouak 🔗](https://github.com/IdrissRio), [Christoph Reichenbach 🔗](https://creichen.net), [Görel Hedin 🔗](https://cs.lth.se/gorel-hedin/) and [Niklas Fors 🔗](https://portal.research.lu.se/portal/en/persons/niklas-fors(c1e9efdd-5891-45ec-aa9d-87b8fb7f3dbc).html)_. _[IEEE-SCAM 2021 🔗](http://www.ieee-scam.org/2021/#home)._ 

---

With **IntraJ** you can:
- construct intra-procedural **Control Flow Graph**,
- (*DAA*) detect **Dead assignments** in your codebase, and
- (*NPA*) detect occurences of **NullPointerException**.
You can run IntraJ on other Java codebases (in Java-4, Java-5, Java-6, and Java-7) in order to construct CFGs and get DAA and NPA analysis results.

</div>
<div class="col-md-3 col-sm-12" style="background-color:transparent" >
<a href="https://github.com/lu-cs-sde/IntraJ" target="_blank"><img  src="{{ site.url }}{{ site.baseurl }}/images/github-light.png"></a>
<p float="center" align="center">
<a href="https://icsme2021.github.io/cfp/AEandROSETrack.html">
  <img  width="70"  src="{{ site.url }}{{ site.baseurl }}/images/conferences/intraj/Open_Research.png"> </a>
  <a href="https://icsme2021.github.io/cfp/AEandROSETrack.html"><img width="70"  src="{{ site.url }}{{ site.baseurl }}/images/conferences/intraj/Research_Objects.png"> </a>
</p>
</div>
</div>
</div>





<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">

## Will it Blend? Composable Source Code Analysis

<a href="{{ site.url }}{{ site.baseurl }}/papers/ProjectCourse.pdf" target="_blank"><button class="btn btn-success btm-sm">PDF</button></a>
<a href="https://www.youtube.com/watch?v=EZq9lr4uFLc"> <button class="btn btn-warning btm-sm"
        style="background-color: seagreen; border-color: seagreen;"> YouTube</button> </a>

<img class="imgfit" src="{{ site.url }}{{ site.baseurl }}/images/projects/wb.png">

---
In collaboration with: @Khashayar Etemadi, @Deepika Tiwari, @Mohammad Reza, @Momina Rizwan and @Matthías Páll Gissurarson 

---

In the beginning, there were command line tools.
Each was beautifully designed and served a single function, such as _wc_ and _cat_. A
single editor was born, _ed_, to serve as
the standard editor. However, mankind was convinced
of its greatness, and wanted more. They started
small and wrote _vi_, a visual interface
for _ed_. An editor with a simple interface
and humble features, which greatly improved
productivity. However, in its success, mankind
grew vain and wrote ever more complex editors,
with grand interfaces and rich graphics, with
feature upon feature built into the editor itself.
But they could not agree. Some wanted to use
a LISP dialect, others shouted for JavaScript.
And thus, like the fall of the tower of Babel, the editor
wars began, with each editor writing features
integrated into its very being, completely
assimilated into its very core. Mankind
grew to like some of these features, but a
problem emerged: how can we share these
features between editors so that we
may all benefit, and avoid another
bloodshed like the editor wars? In this
paper, we describe an interface and units
for that interface which abstract common
GUI editor operations into simple,
one-feature-per-unit command line programs,
and peace in our time.



</div>
<div class="col-md-3 col-sm-12" style="background-color:transparent" >
<a href="https://github.com/IdrissRio/Composable-Software-Tools" target="_blank"><img  src="{{ site.url }}{{ site.baseurl }}/images/github-light.png"></a>
</div>

</div>
</div>
