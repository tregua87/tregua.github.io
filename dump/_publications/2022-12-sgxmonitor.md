---
title: "Designing a Provenance Analysis for SGX Enclaves"
collection: publications
permalink: /publication/2022-12-sgxmonitor
excerpt:
date: "Dec 2022"
venue: "The 38th Annual Computer Security Applications Conference (ACSAC)"
paperurl: https://www.flaviotoffalini.info/files/sgx-monitor.pdf
citation:
---

**Authors:** **Flavio Toffalini**, Mathias Payer, Jianying Zhou, Lorenzo
Cavallaro

**Abstract:** SGX enclaves are trusted user-space memory regions that ensure isolation from the host, which is considered malicious. However, enclaves may suffer from vulnerabilities that allow adversaries to compromise their trustworthiness. Consequently, the SGX isolation may hinder defenders from recognizing an intrusion. Ideally, to identify compromised enclaves, the owner should have privileged access to the enclave memory and a policy to recognize the attack. Most importantly, these operations should not break the SGX properties.  
In this work, we propose SgxMonitor a novel provenance analysis to monitor and identify compromised enclaves. SgxMonitor is composed of two elements: (i) a technique to extract contextual runtime information from an enclave, and (ii) a novel model to recognize enclaves’ intrusions. Our evaluation shows that SgxMonitor successfully identifies enclave intrusions against state-of-the-art attacks without undermining the SGX isolation. Our experiments did not report false positives and negatives during normal enclave executions, while incurring a marginal overhead that does not affect real use cases deployment, thus supporting the use of SgxMonitor in realistic scenarios.

[Artifact](https://github.com/tregua87/sgxmonitor-artifact)

[Slides](https://www.slideshare.net/FlavioToffalini/sgxmonitor-presentation-acsac-2022)

[Download paper here](https://www.flaviotoffalini.info/files/sgx-monitor.pdf)
