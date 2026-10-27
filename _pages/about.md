---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div class="about-intro" markdown="1">

I am a PhD candidate in Economics at the Ghent University under the direction of prof. [Yasin Kürşat Önder](https://sites.google.com/view/yasin-kursat-onder). **I am on the 2026–2027 job market.**

**Job Market Paper:** Mortgage Moratoria as Fiscal-free Stimulus: Evidence from Belgium [(pdf)]({{ site.baseurl }}/files/Belgian_Mortgage_Moratoria_WP.pdf)

In my PhD dissertation, I study the impact of debt suspension policies on household finance and firms performance and aggregate economy. I use highly granular data and causal micro-data to apply to macro models.

</div>

<h2>News</h2>
<ul class="news-list">
  <li><strong>October 8–9, 2026</strong> — Attended the <a href="https://www.nbb.be/doc/ts/enterprise/conferences/colloquium-2026/conference_2026_programme.pdf">NBB Conference 2026</a> of the National Bank of Belgium on <em>Fiscal-monetary policy interactions in the 21st century</em>.</li>
  <li><strong>August 24–28, 2026</strong> — Participated in the <a href="https://www.ugent.be/eb/economics/en/news-events/news/summerschoolmacro2026">Empirical Macroeconomics Summer School</a>, taught by Professor Christiane Baumeister (University of Notre Dame, NBER, CEPR) and focused on state-of-the-art Bayesian methods for structural VAR analysis.</li>
  <li><strong>August 2026</strong> — Attended the <a href="https://efa2026.efa-finance.org/program/phd-program/">Pre-EFA PhD Program</a> and the 53rd EFA Annual Meeting in Ghent, where I presented a poster on <em>Corporate Moratoria</em>.</li>
</ul>

<div class="about-columns">
  <div class="about-column">
    <h2>Interests</h2>
    <ul class="interests-list">
      <li>Private debt and default</li>
      <li>Debt suspension policies</li>
      <li>Households finance</li>
      <li>Corporate finance</li>
      <li>Inequalities</li>
    </ul>
  </div>

  <div class="about-column">
    <h2>Education</h2>
    <ul class="education-list">
      <li>
        <i class="fas fa-graduation-cap education-icon"></i>
        <strong>Ph.D. in Quantitative Macroeconomics</strong><br />
        Ghent University <span class="education-date">— 2023–2027 (expected)</span>
      </li>
      <li>
        <i class="fas fa-graduation-cap education-icon"></i>
        <strong>Research Master's in Models and Methods of Quantitative Economics (QEM)</strong><br />
        Université Catholique de Louvain / Warsaw School of Economics <span class="education-date">— 2019–2021</span>
      </li>
      <li>
        <i class="fas fa-graduation-cap education-icon"></i>
        <strong>B.A. in Quantitative Methods in Economics and Information Systems</strong><br />
        Warsaw School of Economics, Poland <span class="education-date">— 2016–2019</span>
      </li>
    </ul>
  </div>
</div>

<style>
  .page__title {
    display: none;
  }
  .about-columns {
    display: flex;
    flex-wrap: wrap;
    gap: 3em;
    margin-top: 1em;
  }
  .about-column {
    flex: 1 1 300px;
  }
  /* Align the intro with the sidebar photo (only where the sidebar sits beside the text).
     --photo-top: the sidebar's padding-top, i.e. how far the photo starts below the text.
     --photo-height: 200px wide from a 1279x1600 source, plus 5px padding + 1px border. */
  @media screen and (min-width: 1024px) {
    .about-intro {
      --photo-top: 0px;
      --photo-height: 262px;
      box-sizing: border-box;
      padding-top: var(--photo-top);
      min-height: calc(var(--photo-top) + var(--photo-height));
      display: flex;
      flex-direction: column;
      justify-content: center;
    }
    .about-intro > p:first-child {
      margin-top: 0;
    }
    .about-intro > p:last-child {
      margin-bottom: 0;
    }
  }
  .news-list {
    margin: 0.5em 0 1.5em;
    padding-left: 1.2em;
  }
  .news-list li {
    margin-bottom: 0.5em;
  }
  .interests-list,
  .education-list {
    margin: 0.5em 0 0;
    padding-left: 1.2em;
  }
  .interests-list li,
  .education-list li {
    margin-bottom: 0.5em;
  }
  .education-list {
    list-style: none;
    padding-left: 0;
  }
  .education-date {
    color: var(--global-text-color-light);
    font-size: 0.9em;
  }
  .education-icon {
    margin-right: 0.4em;
    color: var(--global-link-color, #6b7f9e);
  }
</style>
