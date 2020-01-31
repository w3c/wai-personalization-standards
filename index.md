---
title: Personalization Overview
permalink: /personalization/
ref: /personalization/
lang: en
layout: default
github:
  repository: w3c/wai-personalization-standards
feedbackmail: wai@w3.org
footer: >
  <p><strong>Date:</strong> Updated 31 January 2020. First published March 2019.</p>
  <p><strong>Editors:</strong> <a href="http://www.w3.org/People/roy/">Ruoxi Ran</a>, <a href="http://www.w3.org/People/cooper/">Michael Cooper</a>, and <a href="http://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>.</p>
  <p>Developed with input from the <a href="https://www.w3.org/WAI/APA/task-forces/personalization/">Personalization Task Force</a>.<p>
---

{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}

This page introduces developing standards to support personalization.

Quick links to documents:
* [Requirements for Personalization Semantics](https://www.w3.org/TR/personalization-semantics-requirements-1.0/)
* [Personalization Semantics Explainer](https://www.w3.org/TR/personalization-semantics-1.0/)
* [Personalization Semantics Content Module](https://www.w3.org/TR/personalization-semantics-content-1.0/)
* [Personalization Help and Support](https://www.w3.org/TR/personalization-semantics-help-1.0/)
* [Personalization Tools](https://www.w3.org/TR/personalization-semantics-tools-1.0/)

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include_cached toc.html type="start" title="Page Contents" class="simple" %}
{:/}

{::options toc_levels="2" /}

-   This text will be replaced by the TOC.
{:toc}

{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}
 
## Introduction
Personalization involves tailoring the user experience to meet the needs and preferences of the individual user. As web technology broadens in scope and reach, and understanding of users' needs increases through research and experience, the set of accessibility considerations for websites becomes larger. Rather than developing complex solutions for a wide range of users, designing sites in a way that they can be personalized to the needs of each user provides more optimal accessibility.

Personalization enables users to use adaptive widgets and user preferences to customize their user experience. It enables content authors to provide a default design and enable user personalization with minimal work.

### Examples of Personalization to Meet User Needs {#examples}

* Some people are easily **distracted or overwhelmed by lots of information** on a website. They have difficulty finding and focusing on key information. Personalization allows users to hide extraneous information so they only get what they need to understand and use the main content.
* Some people have **difficulty understanding numbers** ("dyscalculia"). Personalization allows users to change numeric information. For example, a temperature of 32&deg;F/0&deg;C is replaced with a picture of a person wearing a hat, scarf, and mittens, and the text "very cold".
* Some people with severe language impairment **cannot read text**. They use symbols to represent words. Personalization allows users to change text to symbols.

## Who the Personalization Documents are for
* **Content developers** can add syntax to support personalization. 
* **User agents** such as browser extensions and assistive technology can use the syntax to manipulate the content to meet the user’s need. User agents can also use user preferences for different interface options.

## The Personalization Documents
* [Requirements for Personalization Semantics](https://w3c.github.io/personalization-semantics/requirements/) (Working Draft) includes user stories, specific use cases, and requirements for personalization.
* [Personalization Semantics Explainer](https://www.w3.org/TR/personalization-semantics-1.0/) (Working Draft) is the core introductory document that explains general use cases, vocabulary, and anticipated uses.
* [Personalization Semantics Content Module](https://www.w3.org/TR/personalization-semantics-content-1.0/) (Working Draft) is the technical specification that provides terms authors can use to enhance web content with information about controls, symbols, and user interface elements.
* [Personalization Help and Support](https://www.w3.org/TR/personalization-semantics-help-1.0/) (Working Draft) lists examples of the personalized help and support properties.
* [Personalization Tools](https://www.w3.org/TR/personalization-semantics-tools-1.0/) (Working Draft) lists examples of the personalized tools properties.

## Who Develops the Personalization Documents
Personalization documents are developed by the [Personalization Task Force](https://www.w3.org/WAI/APA/task-forces/personalization/) of the Accessible Platform Working Group ([APA WG](https://www.w3.org/WAI/APA/)), which is part of the World Wide Web Consortium ([W3C](http://www.w3.org/)) Web Accessibility Initiative ([WAI](http://www.w3.org/WAI/)). For more information about the task force, see the [Personalization Task Force page](https://www.w3.org/WAI/APA/task-forces/personalization/).

Formal periods for public review are described in [How WAI Develops Accessibility Guidelines through the W3C Process: Milestones and Opportunities to Contribute](http://www.w3.org/WAI/intro/w3c-process). To submit comments on specific personalization documents, see the “Status of this Document” section of the resource. To get notices of opportunities for review and comment on WAI documents, see [Get WAI News](https://www.w3.org/WAI/news/subscribe/).

Opportunities for contributing to Personalization and other WAI work are introduced in [Participating in WAI](https://www.w3.org/WAI/about/participating/).
