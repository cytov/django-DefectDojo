---
title: "Kubeaudit Scan"
toc_hide: true
---
Kubeaudit is a command line tool and a Go package to audit Kubernetes clusters for various different security concerns. The output of of Kubeaudit which is supported within this parser is JSON. The tool can be found [here](https://github.com/Shopify/kubeaudit)

### Sample Scan Data
Sample Kubeaudit scans can be found [here](https://github.com/DefectDojo/django-DefectDojo/tree/master/unittests/scans/kubeaudit).

### Default Deduplication Hashcode Fields
By default, DefectDojo identifies duplicate Findings using these [hashcode fields](https://docs.defectdojo.com/en/working_with_findings/finding_deduplication/about_deduplication/):

- title
- cwe
- line
- file path
- description
