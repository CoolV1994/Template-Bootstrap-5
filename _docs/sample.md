---
layout: document
title: Sample Document
description: Sample page using Markdown formatting and table of contents.
author: CoolV1994
categories: Sample
tags: Sample Document
headings:
  - text: Intro
    slug: intro
  - text: Section 1
    slug: section-1
    children:
      - text: Section 1.1
        slug: section-1.1
        children:
          - text: Section 1.1.1
            slug: section-1.1.1
          - text: Section 1.1.2
            slug: section-1.1.2
      - text: Section 1.2
        slug: section-1.2
        children:
          - text: Section 1.2.1
            slug: section-1.2.1
  - text: Section 2
    slug: section-2
    children:
      - text: Section 2.1
        slug: section-2.1
        children:
          - text: Section 2.1.1
            slug: section-2.1.1
  - text: Section 3
    slug: section-3
---


* Sections

{:toc}



# Intro

This is a sample document with table of contents.



# Section 1

This is the first section.


## Section 1.1

This is the first sub-section of section 1.


### Section 1.1.1

This is the first sub-section of sub-section 1.1.


### Section 1.1.2

This is the second sub-section of sub-section 1.1.



# Section 2

This is the second section.


## Section 2.1

This is the first sub-section of section 2.


### Section 2.1.1

This is the first sub-section of sub-section 2.1.



# Section 3

This is the third section.
