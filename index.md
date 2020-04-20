---

layout: col-sidebar
title: OWASP SecurityRAT
tags: securityrat
project: true
level: 2
type: tool
pitch: OWASP SecurityRAT is a tool used by development teams, helping them master security requirements during development. 
---
## Project status details
![Build Travis CI Master](https://travis-ci.org/SecurityRAT/SecurityRAT.svg?branch=master)
[![Join the chat at https://owasp.slack.com/archives/C76U4TNFJ](https://img.shields.io/badge/chat-on%20slack-blueviolet)](https://owasp.slack.com/archives/C76U4TNFJ)
[![OWASP Incubator](https://img.shields.io/badge/owasp-incubator%20project-orange.svg)](https://owasp.org/www-project-securityrat/)

## Tool mission 

Simplify security requirement management during development using automation approaches.

## Description
The core functionality of SecurityRAT ("**Security** **R**equirement **A**utomation **T**ool") can be described in the following steps:

1. You tell SecurityRAT what kind of a software artifact you're going to develop / are running
2. SecurityRAT tells you which requirements you should fulfill.
3. You decide how you want to handle the desired requirements.
4. You persist the the artifact state in an issue tracker and create tickets for the requirements where an explicit action is necessary
5. Throughout the continuous development of the particular artifact, you respect the rules defined in SecurityRAT and document relevant changes in requirement compliance whenever appropriate.

Focus of SecurityRAT is put on automation rather then the requirements. While we offer ASVS as an initial set of requirements which you can start with, we strongly recommended to create your own set of requirements which fits your company risk profile.
