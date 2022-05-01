# Google Season of Docs 2022 

### Table of Contents
* [**Introduction**](#Introduction)
* [**Project Structure**](#Project-structure)
* [**Task 1**](#Task-1)
  - [How to Contribute to the Chaoss Website](#Task-1)
  - [Design](#Design)
  - [Development](#Development)
  - [Documentation](#Documentation)
* [**Task 2**](#Task-2)
  - [Metrics](#Metrics) 
  - [Release](#Release)
  - [Review and Revisions](#Review-and-revisions)
* [**Proposal for GSoD 2022**](#Proposal-for-GSoD-2022)
 
## Introduction

This Fork of the Community handbook contains tasks related to the __Topic - Website and Metric releases__.
As a part of the Google Season of Docs interest process, I have collected all the documents related to the website and the metric releases and compiled them into present fork. These documents are stored into the folders `Metric release-review-revision` and `Website Contributing` respectively. In the following README I will link these relevant documents accordingly.

## Project Structure

```text
  ├── .gitbook/assets   
  |
  ├── Metric release-review-revision           # compiled docs for metric release, review and revision          
  |    ├── release-pdfs                               
  │    ├── README.md                          
  │    ├── chaoss-metric-release.md                        
  |    ├── latest-release-notes.md 
  |    ├── metrics-faq.md
  |    ├── release-history.md                      
  |
  ├── Website Contributing                     # compiled documents for website contribution
  |    ├── design                               
  │    ├── development                          
  │    ├── documentation                        
  |    ├── outreach.md 
  |    ├── CONTRIBUTING.md
  |    ├── README.md
  |    ├── contributing.md                      
  |
  ├── about                                     
  ├── badging                                   
  ├── community-initiatives                     
  ├── contributing                                                       
  ├── mentorships                               
  ├── newcomers                                 
  ├── LICENSE                                   
  ├── README.md                                 
  ├── SUMMARY.md                                
  └── handbook-usage.md                         
```
I have added two files `Metric release-review-revision` and `Website Contributing` for my Google Season of Docs application. These two files contain Documents related to Contribution and Metric release, reviews, revision and are compiled from Chaoos's various Github repositories.

## TASK 1
`Task - Audit documents on how to contribute to the website. This would include compiling all of the documents related to website contribution into a folder in the community handbook (in a forked repo). This would also include the creation of a website contribution readme that would link to relevant documents.`

### HOW TO CONTRIBUTE TO THE CHAOSS WEBSITE
Start contributing to the Chaoss website by following the guidelines given in the [contributing.md](https://github.com/pratik2315/community-handbook/blob/season-of-docs/Website%20Contributing/contributing.md). Here you can learn contributing best practices and submit your first ever [Pull request](https://github.com/pratik2315/community-handbook/blob/season-of-docs/Website%20Contributing/contributing.md#code-or-document-change-contributions-pull-request). The document also contains guidelines on how to submit a PR via the github [web interface](https://github.com/pratik2315/community-handbook/blob/season-of-docs/Website%20Contributing/contributing.md#code-or-document-change-contributions-github-user-interface). Along with this learn how to use the DCO plugin to your advantage for signing commits. A good contribution is more than a Pull request. You can also contribute to the organization by reporting bugs and having discussions about various [feature requests](https://github.com/pratik2315/community-handbook/blob/season-of-docs/Website%20Contributing/contributing.md#bug-report-and-feature-request-contributions-issue).

The [CONTRIBUTING.md](https://github.com/pratik2315/community-handbook/blob/season-of-docs/Website%20Contributing/CONTRIBUTING.md) and [README.md](https://github.com/pratik2315/community-handbook/blob/season-of-docs/Website%20Contributing/README.md) files contain information about repository specific guidelines and Website maintainers information respectively. Both point to the `contributing.md` for contribution guidelines.

### Design
Contribution guidelines for User Interface Design (UI), User Experience Design (UX), Graphic Design and Visual Identity, User Design Research and Documentation. These [Design guidelines](https://github.com/pratik2315/community-handbook/tree/season-of-docs/Website%20Contributing/design) are listed in the Community Handbook under the Website header navigation. 

### Development
To contribute to Chaoss projects like Augur, GrimoireLab and Cregit. We need to follow project specific contribution guidelines. This document contains contribution information releated to [Development guidelines](https://github.com/pratik2315/community-handbook/tree/season-of-docs/Website%20Contributing/development).

### Documentation
Unfortunately, good code won't speak for itself. That's why we need a good documentation for our projects and website. This document explains the [Documentation contribution guidelines](https://github.com/pratik2315/community-handbook/tree/season-of-docs/Website%20Contributing/documentation) and guides you to submit your documentation related PR.

## TASK 2
`Task - Audit documents on metrics release, review, and revision. This would include compiling all of the documents related to the release, review, and revision of metrics into a folder in the community handbook (in a forked repo). This would also include the creation of metrics release readme that would link to all relevant documents.`

### Metrics
CHAOSS metrics are identified and defined using a [continuous contribution process](https://handbook.chaoss.community/community-handbook/community-initiatives/metrics/chaoss-metric-release). The metrics are officially released biannually following a 30 day comment period. 

### Release
To see the list of metric releases from 2019-2022 in pdf format you can go to [release-pdfs](https://github.com/pratik2315/community-handbook/tree/season-of-docs/Metric%20release-review-revision/release-pdfs). The pdf’s contain detailed information about various metric definitions, releases, review process along with the contributors information. 
The [chaoss-metric-release](https://github.com/pratik2315/community-handbook/blob/season-of-docs/Metric%20release-review-revision/chaoss-metric-release.md) talks about the metric [regular release](https://github.com/pratik2315/community-handbook/blob/season-of-docs/Metric%20release-review-revision/chaoss-metric-release.md#regular-release), preparing the [final release](https://github.com/pratik2315/community-handbook/blob/season-of-docs/Metric%20release-review-revision/chaoss-metric-release.md#prepare-the-final-release) and [preparing the pdf’s release](https://github.com/pratik2315/community-handbook/blob/season-of-docs/Metric%20release-review-revision/chaoss-metric-release.md#prepare-the-pdf-release) containing the final release.

If you are interested in metric release history, you should check out [release-history.md](https://github.com/pratik2315/community-handbook/blob/season-of-docs/Metric%20release-review-revision/release-history.md) to see the detailed history and notes of releases from 2019 to 2022. The section also includes the content in English as well as Chinese.

CHAOSS metrics are released continuously. The regular release is when we update the version number, update the full release notes, and make a big announcement. These releases occur one to two times a year and may correspond with the dates of a CHAOSScon event. Prior to regular release, continuous released metrics go through a comment period of at least 30 days. To see the latest release notes you can go to [latest-release-notes](https://github.com/pratik2315/community-handbook/blob/season-of-docs/Metric%20release-review-revision/latest-release-notes.md). 
If you have any additional queries about metric release process, version or other questions you can visit Metrics [Frequently Asked Questions](https://github.com/pratik2315/community-handbook/blob/season-of-docs/Metric%20release-review-revision/metrics-faq.md)

### Review and Revisions
The CHAOSS Metrics Committee defines implementation-agnostic metrics for assessing open source communities' health and sustainability. All metrics get approved before they are visible on the website. To know more about the process of metrics getting approved, you can check out Metric [README.md](https://github.com/pratik2315/community-handbook/blob/season-of-docs/Metric%20release-review-revision/README.md). The document also contains information regarding the [Community Review](https://github.com/pratik2315/community-handbook/blob/season-of-docs/Metric%20release-review-revision/README.md#when-should-a-previously-released-metric-be-returned-to-community-review) of the released metrics and some [Metric useful resources](https://github.com/pratik2315/community-handbook/blob/season-of-docs/Metric%20release-review-revision/README.md#-some-metric-useful-resources).

The `chaoss-metric-release` mentioned in the release section also contains important information regarding [Revising](https://github.com/pratik2315/community-handbook/blob/season-of-docs/Metric%20release-review-revision/chaoss-metric-release.md#revising-existing-metrics) the exisiting metric. As the process of developing metric evolves chaoss implements a process to go back to old metrics and revise them every two years.

### Proposal for GSoD 2022
