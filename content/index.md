---
doc-note-type: draft
doc-note-message: <p>This is a draft re-wording of 'Personalization' to 'Adapt'. See background and discussion in <a href='https://github.com/w3c/wai-personalization-standards/issues/8'>GitHub issue 'branding'</a></p>

title: WAI-Adapt Overview
title_html: "<span style='line-height:1'><br>WAI-Adapt Overview<br><span style='font-style: italic; font-size: 0.75em'>Enabling users to adapt content<br>Enabling users to adapt content presentation<br>Enabling users to change content presentation<br>Enabling users to personalize content presentation</span></span>"	
permalink: /personalization/
ref: /personalization/
lang: en
layout: default
github:
  repository: w3c/wai-personalization-standards
feedbackmail: wai@w3.org
footer: >
  <p><strong>Date:</strong> DRAFT idea. First published March 2019.</p>
  <p><strong>Editors:</strong> <a href="http://www.w3.org/People/roy/">Ruoxi Ran</a>, <a href="http://www.w3.org/People/cooper/">Michael Cooper</a>, and <a href="http://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>.</p>
  <p>Developed with input from the <a href="https://www.w3.org/WAI/APA/task-forces/personalization/">Personalization Task Force</a>.<p>
---

{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}

This page introduces the WAI-Adapt series of technical specifications. WAI-Adapt enables users to adapt (or 'personalize') how content is presented.
  
Why Adapt: It's important to meet individual needs and preferences for content presentation, including the accessibility needs of people with disabilites.

Quick links to documents:
* [Requirements for WAI-Adapt Specifications](https://www.w3.org/TR/personalization-semantics-requirements-1.0/)
* [WAI-Adapt Explainer](https://www.w3.org/TR/personalization-semantics-1.0/)
* [WAI-Adapt: Content Module](https://www.w3.org/TR/personalization-semantics-content-1.0/)
* [WAI-Adapt: Help and Support Module](https://www.w3.org/TR/personalization-semantics-help-1.0/)
* [WAI-Adapt: Tools Module](https://www.w3.org/TR/personalization-semantics-tools-1.0/)

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
  
WAI-Adapt specifications enable users to personalize how content is presented to meet their needs and preferences.
  
As web technology broadens in scope and reach, and understanding of users' needs increases through research and experience, the set of accessibility considerations for websites becomes larger. Rather than developing complex solutions for a wide range of users, designing sites in a way that they can be personalized to the needs of each user provides more optimal accessibility.

WAI-Adapt enables users to use adaptive widgets and user preferences to customize their user experience. It enables content authors to provide a default design and enable user adaptation with minimal work.

### Examples of WAI-Adapt to Meet User Needs {#examples}

* Some people are easily **distracted or overwhelmed by lots of information** on a website. They have difficulty finding and focusing on key information. WAI-Adapt allows users to hide extraneous information so they only get what they need to understand and use the main content.
* Some people have **difficulty understanding numbers** ("dyscalculia"). WAI-Adapt allows users to change numeric information. For example, a temperature of 32&deg;F/0&deg;C is replaced with a picture of a person wearing a hat, scarf, and mittens, and the text "very cold".
* Some people with severe language impairment **cannot read text**. They use symbols to represent words. WAI-Adapt allows users to change text to symbols.

## Who the WAI-Adapt Specifications are for
* **Content developers** can add syntax to support adaptation. 
* **User agents** such as browser extensions and assistive technology can use the syntax to manipulate the content to meet the user’s need. User agents can also use user preferences for different interface options.

## The WAI-Adapt Documents
* [Requirements for WAI-Adapt Specificationss](https://www.w3.org/TR/personalization-semantics-requirements-1.0/) (Working Draft Note) includes user stories, specific use cases, and requirements for Adapt.
* [WAI-Adapt Explainer](https://www.w3.org/TR/personalization-semantics-1.0/) (Working Draft Note) is the core introductory document that explains general use cases, vocabulary, and anticipated uses.
* [WAI-Adapt: Content Module](https://www.w3.org/TR/personalization-semantics-content-1.0/) (Working Draft specification) is the technical specification that provides terms authors can use to enhance web content with information about controls, symbols, and user interface elements.
* [WAI-Adapt: Help and Support Module](https://www.w3.org/TR/personalization-semantics-help-1.0/) (Working Draft) lists examples of the adapted help and support properties.
* [WAI-Adapt: Tools Module](https://www.w3.org/TR/personalization-semantics-tools-1.0/) (Working Draft) lists examples of the adapt tools properties.

## Who Develops WAI-Adapt
WAI-Adapt documents are developed by the [Personalization Task Force](https://www.w3.org/WAI/APA/task-forces/personalization/) of the Accessible Platform Working Group ([APA WG](https://www.w3.org/WAI/APA/)), which is part of the World Wide Web Consortium ([W3C](http://www.w3.org/)) Web Accessibility Initiative ([WAI](http://www.w3.org/WAI/)). For more information about the task force, see the [Personalization Task Force page](https://www.w3.org/WAI/APA/task-forces/personalization/).

Formal periods for public review are described in [How WAI Develops Accessibility Guidelines through the W3C Process: Milestones and Opportunities to Contribute](http://www.w3.org/WAI/intro/w3c-process). To submit comments on specific WAI-Adapt documents, see the “Status of this Document” section of the resource. To get notices of opportunities for review and comment on WAI documents, see [Get WAI News](https://www.w3.org/WAI/news/subscribe/).

Opportunities for contributing to WAI-Adapt and other WAI work are introduced in [Participating in WAI](https://www.w3.org/WAI/about/participating/).
  
  ...
