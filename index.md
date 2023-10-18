---
layout: home
---
<img id="headshot" src="sebastian-benthall.jpg" class="pure-img" width="200">

# Sebastian Benthall, Ph.D.

* Senior Research Fellow, <a href="https://www.law.nyu.edu/centers/ili">Information Law Institute</a>, New York University School of Law
* Research Scientist, International Computer Science Institute
* External Faculty, New York University <a href="https://publichealth.nyu.edu/research-scholarship/centers-labs-initiatives/agent-based-modeling-lab">Agent Based Modeling Lab</a>
* Research Engineer, <a href="https://econ-ark.org/">Econ-Ark</a>

<h2 id="projects"><a href="#projects">&sect;</a> Current Projects</h2>

* Designing fiduciary artificial intelligence. Fiduciaries are trusted roles in society with specific legal duties. How can these duties inform the design of Trustworthy AI?
* Simulating the interaction between consumers and financial markets by building <a href="https://github.com/sbenthall/SHARKFin">SHARKFin</a> with a <a href="https://www.icds.psu.edu/penn-state-smeals-liechty-leading-darpa-funded-project-to-study-financial-disruptions/">DARPA-funded</a> team.
* Developing new tools for building and solving lifecycle models in heterogeneous agent macroeconomics for the <a href="https://github.com/econ-ark/HARK">HARK</a> project.
* Creating methods for using Agent-Based Modeling to hold software accountable to legal regulation. I am (co-)PI, <a href="https://www.nsf.gov/awardsearch/showAward?AWD_ID=2131532&HistoricalAwards=false">NSF #2131532</a>, with the NYU School of Law, the <a href="https://publichealth.nyu.edu/research-scholarship/centers-labs-initiatives/agent-based-modeling-lab">Agent-Based Modeling Lab at NYU School of Global Public Health</a>, and the <a href="https://www.nsf.gov/awardsearch/showAward?AWD_ID=2131533&HistoricalAwards=false">International Computer Science Institute</a>.
* Building <a href="https://github.com/datactive/bigbang">BigBang</a>, a suite of computational social science tools for studying standards-setting and infrastructure governance, and contributing to the <a href="https://datatracker.ietf.org/group/rasprg/about/">RASP</a> IRTF Research Group.

<h2 id="publications"><a href="#publications">&sect;</a> Publications</h2>

<h3>Research Articles</h3>

<ul>
  {% for ref in site.data.references.publications %}
  <li>
  {{ref.authors}} ({{ref.year}}). {{ref.title}}. {{ref.venue}}.
    {% for link in ref.links %}
    (<a href="{{link.url}}">{{link.label}}</a>)
    {% endfor %}
  </li>
  {% endfor %}
</ul>

<h3>Popular Writing and Trade Literature</h3>

<ul>
  <li>Benthall, S. and Goldenfein, J. "Essential Infrastructures". <i>Phenomenal World</i>. (<a href="https://phenomenalworld.org/analysis/essential-infrastructures">link</a>)</li>
  <li>Benthall, S. and Haynes, B. "Understanding Race with AI". <i>Public Books</i>. (<a href="https://www.publicbooks.org/understanding-race-with-ai/">link</a>)</li>
  <!--
  <li>
    Benthall, S. (2013) "Why Weird Twitter", <em>Ethnography Matters</em>. (<a href="http://ethnographymatters.net/blog/2013/06/30/why-weird-twitter-part-1/">link</a>) <em>A brief and unlikely foray into social media ethnography...</em>
  </li>
  -->
  <li>Benthall, S. (2009). An open source web GIS solution-the OpenGeo stack. <em>GEO informatics, 12</em>, 40-43.
  </li>
</ul>

<h3>Technical Reports and Pre-prints</h3>
<ul>
  <li>Nissenbaum, H., Benthall, S., Datta, A., Tschantz, M. C., & Mardziel, P. (2018). Origin Privacy: Protecting Privacy in the Big-Data Era. Technical Report. New York University. (<a href="http://www.dtic.mil/dtic/tr/fulltext/u2/1057995.pdf">link</a>)</li>
  <li>Benthall, S. (2017) Don't Fear the Reaper: Refuting Bostrom's Superintelligence Argument. Preprint, arXiv:1702.08495 (<a href="https://arxiv.org/abs/1702.08495">link</a>)</li>
  <li>
    Benthall, S. and Chuang, J. (2013) Computational Asymmetry in Strategic Bayesian Networks. Poster at W-PIN+NetEcon 2013, Pittsburgh. arXiv:1206.2878 [cs.GT] (<a href="http://arxiv.org/abs/1206.2878">arXiv</a>)
  </li>
  <li>
   Fanti, G., David, Y. B., Benthall, S., Brewer, E., and Shenker, S.. (2013) Rangzen: Circumventing Government-Imposed Communication Blackouts. Technical Report UCB/EECS-2013-128, EECS Department, University of California, Berkeley, Jul 2013. (<a href="http://www.eecs.berkeley.edu/Pubs/TechRpts/2013/EECS-2013-128.html">link</a>)
   </li>
</ul>
    
<h2 id="software"><a href="#software">&sect;</a>Software</h2>
<ul>
  <li><a href="https://github.com/sbenthall/SHARKFin">SHARKFin</a>, for modeling the interaction between the macroeconomy and the financial system.</li>
  <li><a href="https://github.com/econ-ark">Econ-Ark</a>, for structural economic modeling with heterogeneous agents.</li>
  <li><a href="http://github.com/sbenthall/bigbang">BigBang</a>, for the analysis of standards-seting, infrastructure governance, and open collaborative communities. A founding technology of the <a href="https://datatracker.ietf.org/rg/rasprg/about/">Reserach and Analysis of Standard-Setting Processes Research Group</a> of the Internet Engineering Task Force.</li>
  <li><a href="http://geonode.org/">GeoNode</a>, an open source geospatial data management system. It was part of an <a href="https://opendri.org/wp-content/uploads/2017/03/OpenDRI-and-GeoNode-a-Case-Study-on-Institutional-Investments-in-Open-Source.pdf">innovative strategy</a> to leverage open source development practices for international development. There is still a great team working on it and deploying it as a product.</li>
</ul>

<h2 id="dissertation">Dissertation</h2>

<p>Sebastian Benthall. <em>Context, Causality, and Information Flow: Implications for Privacy Engineering, Security, and Data Economics</em>. Ph.D. dissertation. Advisors: John Chuang and Deirdre Mulligan. University of California, Berkeley. 2018. (<a href="https://escholarship.org/uc/item/5sg7q32q">eScholarship</a>) (<a href="https://www.slideshare.net/SebastianBenthall/context-causality-and-information-flow-implications-for-privacy-engineering-security-and-data-economics">slideshare</a>)</p>

<!--
<h2>Background</h2>
<p>2021 - NSF SBE Postdoctoral Research Fellow</p>
<p>2019 - Research Engineer, Econ-Ark</P>
<p>2018 - : Research Scholar at NYU. <a href="https://www.guariniglobal.org/">GGLT</a> (2019 - ), <a href="http://www.law.nyu.edu/centers/ili">ILI</a> (2018 - ) and <a href="http://cyber.nyu.edu/">CCS</a> (2018 - 2019).</p>
 <p>2016 - 2018 : Researcher at Cornell Tech under Prof. Helen Nissenbaum.</p>
 <p>2016 - 2019 : Data scientist at Ion Channel.</p>
 <p>2011 - 2018 : PhD at UC Berkeley's School of Information.</p>
 <p>2007 - 2011 : Worked in programming, management, and marketing in geospatial civic tech company, OpenGeo.</p>
 <p>2007 : B.A., Brown University, Cognitive Science.</p>
 -->

<h2>On the Web</h2>

<p><a href="https://github.com/sbenthall">github</a> <a href="https://scholar.google.com/citations?user=iOgZOWYAAAAJ&hl=en">google scholar</a> <a href="http://digifesto.com">blog</a> <a href="http://twitter.com/sbenthall">twitter</a> <a href="http://lnkd.in/dQXWUp3">linkedin</a>  <a href="http://www.slideshare.net/SebastianBenthall">slideshare</a> <!-- <a href="https://medium.com/@sbenthall">medium</a> --></p>

<h2>Contact</h2>
<p>e-mail: spb413 at nyu dot edu</p>
    