---
layout: default
title: Sponsors
nav_order: 7
description:
---

# Projects & Sponsors



Developed the scope over the last months to narrow down to these projects similar difficulty and appropriate pre-requisites (ie: development language, loosely coupled to their internal systems). As such, the companies have already invested a notable amount of time in setting this up for you with no guarantee of a solid return.

All industry projects are real issues and an expectations of all that they will use at least a portion of your solution. Most projects have wider delivery scope while some have more fuzzy requirements... Like the real world. 


More details about the sponsors and projects available in the lecture notes
{: .note}



<img width="40%" src="{{ '/assets/figures/ae.jpg' | absolute_url }}">



**Business Requirement Statement:**

Each year the 20+ locations of AE create and submit thousands of proposals to prospective
clients across Canada. Each of these proposals includes the resumes of key resources who will
participate in the project should it be won. These resumes are time-consuming to create as
they are custom written for each proposal to highlight specific skills and experiences that are
important to project success. The finalized resumes are stored in the proposal folder of a
Network Drive and not easily located for use on future proposals.


**Project Profile:**

What is needed is a solution where resumes can be created, stored, and exported for the initial
proposal then recovered and modified when an employee is selected for a future proposal.

***



<img  width="40%" src="{{ '/assets/figures/hsbc.png' | absolute_url }}">


**Business Requirement Statement:**

HSBC has the ability to check owned AWS accounts for compliance violations using tools like
AWS Config and custom applications developed in-house. These tools also have the ability to
auto remediate and notify developers of violations.

We would like [to shift this work further left](https://en.wikipedia.org/wiki/Shift-left_testing) so developers can catch misconfigurations earlier and
we avoid having misconfigurations deployed even for a small amount of time. HSBC is already
using infrastructure as code to provision it’s AWS infrastructure, so it makes sense to have a
solution that checks our Terraform files in Github as part of a deployment pipeline when
changes to the Terraform script are applied.


**Project Profile:**

We need to have an application that can check out Terraform files stored in a Git repo and run
checks against them to ensure violations are not present.



