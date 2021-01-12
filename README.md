# re-Inspector Documentation

## Intro
re-Inspector is a fully passive Burp extension written in Python. It helps to identify security issues including missing/misconfigured security headers and sensitive information in HTTP Response for the selected target. It can extract all the vulnerable endpoints in simple text format, as well as issues, can be CSV format which can be imported directly in Resolve. 

**Reporting**

Currently, re-Inspector helps to generate reports in CSV and text format which contains vulnerable endpoints.

## Features
- Discovering security issues through the passive scan.
- Analysing HTTP response for sensitive information.
- Low false positive rate.
- Generate report in CSV and Text format.

## Usage
Once target application crawling is completed, right-click on the URL from anywhere and select “Send to re-Inspector”. Open re-Inspector tab from extension bar. Check all the vulnerabilities which are needed to be tested and click on Scan.

![Alt Text](https://raw.githubusercontent.com/dubey-amit/re-Inspector/main/Demo.gif)


## Installation
Download latest python file

![Alt Text](https://raw.githubusercontent.com/dubey-amit/re-Inspector/main/installation.gif)

## Todo list
- Support for multiple host.
- More vulnerabilities to be added.
- Identifying API keys and secrets.
