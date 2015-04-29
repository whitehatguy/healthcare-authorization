
##Audience##

This document is intended for:

* Security specification authors
* Electronic Health Record (EHR) developers
* Application developers

##Goal##

This document is intended to complement, aid, and influence the development of open standards for EHR interoperability—specifically the HL7® FHIR® standard to ensure security risks are identified and mitigated in consistent manner, to maximize interoperability.

##Executive Summary##

To make off-the-shelf interoperability a reality in healthcare, security protocols are needed that standardize how applications can obtain the authorization to utilize EHR services on the behalf of a user.  To further the development of secure, consistent, and interoperable implementations of EHR services and applications in this ecosystem, this document provides the following:

* An enumeration of the use cases (user stories), risks, and threats that must be considered when developing security specifications by specification authors.
* A base framework to be considered by security specification authors that addresses the use cases and identified risks/threats.
* A list of functional and technical considerations for software developers when implementing security services, EHR services, or consuming applications.
* A list of requirements and best practices that are recommended for both specification authors and software developers to agree upon to enable consistent, secure, and interoperable implementations to be developed.

##License##

This document is licensed under Creative Commons "No Rights Reserved" (CC0) [1]. 

[1] http://creativecommons.org/publicdomain/zero/1.0/