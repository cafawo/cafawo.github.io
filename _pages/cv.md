---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Employment and Affiliations
======
* 09/2022 - Present: IWH - Leibniz Institute for Economic Research, Halle, Germany. Head of research group: "Data Science in Financial Economics"
* 11/2022 - Present: Martin Luther University Halle-Wittenberg, Germany. Assistant Professor for Financial Economics
* 02/2015 - Present: Frankfurt School of Finance & Management, Germany. Lecturer (part-time): Financial Economics
* 12/2020 - Present: Hiveanalytica GmbH, Germany. Co-Founder
* 02/2019 - 11/2022: Axiomatec AG, Liechtenstein. Co-Founder
* 11/2015 - 11/2018: Goethe University Frankfurt, Germany. Research assistant

Education
======
* 01/2018 - 05/2018: Columbia University, New York City, USA. Visiting Scholar: Decision, Risk and Operations division
* 11/2014 - 04/2019: Goethe University Frankfurt, Germany. Ph.D. (Dr. rer. pol.), summa cum laude
* 03/2013 - 08/2014: Frankfurt School of Finance & Management, Germany. Master of Finance (M.Sc.), Capital Markets concentration
* 01/2011 - 08/2011: University of California Santa Barbara, USA. Two semesters abroad
* 09/2009 - 03/2013: Frankfurt School of Finance & Management, Germany. International Business Administration (B.Sc.)


Publications
======
  <ul>{% assign publications_sorted = site.publications | sort: "date" | reverse %}{% for post in publications_sorted %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Selected Grants and Awards
======
* Frankfurt Institute for Risk Management and Regulation (EUR 86,000), 2022
* Goethe University, Sturm & Drang Prize (co-author), 2022
* Best Paper Award, Lazaridis Institute and the CAAA Annual Conference, 2021
* Best Paper Award, 82nd VHB Annual Meeting, 2020

Teaching and Seminars
======
  <ul>{% assign cv_teaching = site.teaching | where_exp: "post", "post.title != 'Bachelor and Master Theses'" %}{% for post in cv_teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
  <li>Econometrics - Machine Learning (IWH-DPE, Ph.D.)</li>
  <li>Seminar: Applied Econometrics (Martin Luther University, B.Sc.)</li>
  <li>Financial Institutions and Risk Management (Goethe Business School)</li>
  <li>Derivative Analytics (Vietnamese German University, M.Sc.)</li>
  <li>Risk Management (Frankfurt School / VDT)</li>
  <li>Spezielle Fragen der Unternehmensfinanzierung (Frankfurt School, LL.M.)</li>
  <li>Finance I (Frankfurt School, B.Sc.)</li>
  <li>Finance II (Frankfurt School, B.Sc.)</li>
  <li>Financial Markets Certification (LFMA/AEFMA)</li>
  <li>Finance Bootcamp (Frankfurt School, MBA)</li>
  <li>Seminar: Analyse komplexer Produkte (Commerzbank)</li>
  </ul>

Service
======
* Since 2021: Management board member at "Wohltätigkeitsanstalt zur Einigkeit", a charitable foundation that distributes need-based scholarships to support access to higher education for young adults.
