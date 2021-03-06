---
title: "Web Accessibility First Aid: Approaches for Interim Repairs"
permalink: /planning/interim-repairs/
github:
  repository: w3c/wai-first-aid
footer: >
  <p><strong>Date:</strong> Minor link updated 23 May 2018. Last substantive update November 2016. First published March 2006.<br>History: Previously titled "Short Term Website Accessibility Improvements" and "Improving the Accessibility of Your Website".</p>
  <p><strong>Editor: </strong><a href="https://www.w3.org/People/shadi/">Shadi Abou-Zahra</a>. Previous editors: <a href="https://www.w3.org/People/kevin">Kevin White</a> and <a href="https://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>.  Previous contributors: Sharron Rush, Anna Belle Leiserson, Judy Brewer, and <a href="https://www.w3.org/WAI/EO/participants">EOWG Participants</a>.</p>
  <p>Developed by the Education and Outreach Working Group (<a href="http://www.w3.org/WAI/EO/">EOWG</a>). First developed with support from <a href="https://www.w3.org/WAI/TIES/"><acronym title="Web Accessibility Initiative: Training, Implementation, Education, Support">WAI-TIES</acronym> Project</a>, then updated with support of the <a href="https://www.w3.org/WAI/ACT/"><acronym title="Web Accessibility Initiative - Cooperation Framework for Guidance on Advanced Technologies, Evaluation Methodologies, and Research Agenda Setting to Support eAccessibility">WAI-ACT</acronym> Project</a>, and later the <a href="https://www.w3.org/WAI/DEV/"><acronym>WAI-DEV</acronym> Project</a>.</p>
---

{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}

Do you need to urgently address accessibility in an on-going web project?
This page provides a concise overview with pointers to help address the most critical issues.
Find a more comprehensive accessibility approach for the entire design and development process in [Planning and Managing Web Accessibility]({{ "/planning-and-managing/" | relative_url }}).

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::options toc_levels="2" /}
{::nomarkdown}
{% include_cached toc.html type="start" title="Page Contents" class="full" %}
{:/}
-   TOC is created automatically.
{:toc}
{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}


Key Resources for Designers and Developers {#resources}
------------------------------------------

-   [Tips for Getting
    Started]({{ "/tips/" | relative_url }}) — Practical
    considerations with examples for designing, writing, and developing
    accessible web content.
-   [Web Accessibility Tutorials](https://www.w3.org/WAI/tutorials/) —
    Detailed information on specific topics with guidance on addressing
    accessibility requirements.
-   [How to Meet WCAG 2 (Quick Reference)](https://www.w3.org/WAI/WCAG20/quickref/) — A
    customizable quick reference to Web Content Accessibility Guidelines
    (WCAG) 2.

What is Accessibility? {#understand}
----------------------

If you are new to accessibility, it is often helpful to first get a
basic understanding of accessibility:

-   [Introduction to Web Accessibility](https://www.w3.org/WAI/fundamentals/accessibility-intro/) — Introduces essential concepts, rationale, and resources.
-   [Web Accessibility
    Perspectives]({{ "/perspective-videos/" | relative_url }}) — Short
    non-technical videos that introduce accessibility features and their
    benefits for everyone.

### More Background {#background}

When you need more in-depth background:

-   [How People with Disabilities Use the
    Web]({{ "/people-use-web/" | relative_url }}) — Introduces
    experiences and terminology in accessibility and disability.
-   [Accessibility
    Principles]({{ "/fundamentals/accessibility-principles/" | relative_url }})
    — Introduces accessibility requirements defined by the W3C
    guidelines.

Identify the Issues {#explore}
-------------------

If you already know your accessibility issues, you can skip this
section. If you need to identify potential issues, these resources can
help:

-   [Easy Checks — A First Review of Web
    Accessibility]({{ "/test-evaluate/preliminary/" | relative_url }}) —
    Simple checks that can be carried out by anyone, regardless of
    technical skills and accessibility knowledge.
-   [List of Web Accessibility Evaluation
    Tools](https://www.w3.org/WAI/ER/tools/) — Customizable list that
    allows you to search for different types of tools.

### Detailed Review {#comprehensive}

When you want to do a comprehensive evaluation:

-   [Website Accessibility Conformance Evaluation Methodology
    (WCAG-EM)](https://www.w3.org/WAI/eval/conformance.html) — Provides
    a structured approach to help evaluate websites for accessibility.
-   [WCAG-EM Report Tool](https://www.w3.org/WAI/eval/report-tool/) —
    Free online tool to help create evaluation reports following the
    WCAG-EM procedure.

Consider the Scope {#scope}
------------------

You may not be able to address all the issues on every part of your
website at once. To determine which parts you want to improve right
away, and which to address in later stages, consider prioritizing:

-   **Key tasks**, such as registration, search, submit, or checkout
    processes. Include all steps involved to complete each task.
-   **Key content**, such as frequently accessed content and content
    that is relevant to people with disabilities.
-   **Reported content**, that has known barriers; for example, from
    user comments submitted through the website feedback form.
-   **In-development content**, such as areas of the website that are
    currently being redesigned, to avoid the creation of new barriers.

Within your scope of repair, consider prioritizing what you repair first
by focusing on:

-   **High-impact repairs**
    -   Appear on multiple web pages, such as navigation bars
    -   Appear on frequently-used web pages, such as the home page
    -   Are critical to complete processes, such as purchase forms
    -   Web Content Accessibility Guidelines (WCAG) Level A issues
-   **Low-effort repairs**
    -   Require less time, cost, or skills to repair
    -   Requires less testing and validation

Set your Accessibility Target Level {#target}
-----------------------------------

The generally accepted target for accessibility is the latest version of [Web Content
Accessibility Guidelines (WCAG)]({{ "/standards-guidelines/wcag/" | relative_url }})
Level AA. This may already be the standard specified in your
organizational policy or it may be the legal requirement for your
website.

You may need to define a phased approach with different dates for
different levels. For example, meet particular WCAG 2 success criteria
in the next release, and meet all [Level A and Level
AA](https://www.w3.org/WAI/WCAG20/quickref/?currentsidebar=%23col_overview&levels=aaa)
success criteria in the following release.

Note that in some cases, some Level AAA success criteria may be fairly
easy to meet. For example, refining appropriate link text (2.4.4, Level
A) and heading structure (2.4.10, Level AAA) may be easy to address
together when revising content.

Tips for Efficient Repair {#repair}
-------------------------

-   **Leverage the different skills in your team** — While many tasks
    will be for developers, other roles have plenty to contribute. For
    example, designers can select better colors and content authors can
    improve the wording of links, headings, and text alternatives. The
    resource [Using Combined Expertise to Evaluate Web
    Accessibility](https://www.w3.org/WAI/eval/reviewteams.html) may be
    helpful.
-   **Communicate requirements across your team** — Ensure that everyone
    involved in repairs understands the basics of web accessibility and
    the specific requirements they need to address. Distribute the
    [Important Resources](#resources) to the relevant members of your
    team.
-   **Validate solutions as early as possible** — Ensure that any
    solutions adequately address the issues raised to avoid implementing
    changes that do not work in practice. If at all possible, it is
    important to involve people with disabilities in such validation.
    The resources about [involving users in web
    projects]({{ "/planning/involving-users/" | relative_url }}) and [evaluating
    with users]({{ "/test-evaluate/involving-users/" | relative_url }}) provide more
    background.
-   **Optimize your Tools** — Explore and configure accessibility
    settings in the authoring tools you use to create web content, such
    as your content management system (CMS). The resources about
    [selecting evaluation
    tools]({{ "/test-evaluate/tools/selecting/" | relative_url }}) and [selecting
    authoring tools](https://www.w3.org/WAI/impl/software) may be
    helpful.

Longer Term: Planning and Managing {#plan}
----------------------------------

Once you have addressed some of the most critical web accessibility
issues on your web project, it is essential you plan to integrate
accessibility throughout future design and development processes. The
[Planning and Managing Web
Accessibility]({{ "/planning-and-managing/" | relative_url }}) guide can help you
develop that plan.
