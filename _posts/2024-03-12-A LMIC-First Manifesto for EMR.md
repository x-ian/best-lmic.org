---
title: A LMIC-First Approach to Developing Electronic Medical Record Systems
author: x-ian
date: 2024-03-12
category: Jekyll
layout: post
---

# A LMIC-First Approach to Developing Electronic Medical Record Systems

Christian Neumann<sup>1</sup>, Elizabeth L. Dunbar<sup>2</sup>, Jeremy
U. Espino<sup>1,3</sup>, Timothy M. Mtonga<sup>1</sup>,

Gerald P. Douglas<sup>1,3</sup>

<sup>1</sup>Global Health Informatics Institute, Lilongwe, Malawi

<sup>2</sup>Department of Human Centered Design and Engineering,
University of Washington, Seattle, Washington, USA

<sup>3</sup>Department of Biomedical Informatics, University of
Pittsburgh, Pittsburgh, USA

## Letter to the Editor

Having spent almost two decades developing electronic medical record
(EMR) systems in low- and middle-income countries (LMIC), the inability
to quickly design, develop systems and deploy new clinical guidelines
remain bottlenecks to successful scale up and continued use. Significant
gaps persist in EMR designs for LMIC settings. These gaps result from
failure to understand how the environments, models and processes of
delivering healthcare in LMICs are fundamentally different from high
income countries [\[1\],
\[2\]](https://www.zotero.org/google-docs/?PYBOwr). Additionally, EMRs
are often planned in top-down fashion, driven by an implementers or
external funder’s vision. EMR systems for LMICs model those used in the
global north, requiring heavy text data entry, complex data models, and
heavyweight hardware to support. Here we outline a “LMIC-First” approach
to designing EMR systems intended for LMICs. This approach considers the
EMR system, its environment and how these interact when the system is
implemented. The following six themes describe the proposed LMIC-First
approach to EMR design:

### Democratised EMR Development

EMR implementation in LMICs has mostly followed a project-based approach
with independent contractors or implementing partners funded by donors
working independently with little-to-no direct involvement from the
Ministry of Health (MoH) staff in the host country
[\[3\]](https://www.zotero.org/google-docs/?R7SydB). While this was done
to fasttrack EMR implementation, it has led to reduced country
ownership, increased dependency on external organizations, and
protracted development cycles, sometimes including transitions between
implementing partners and often exceeding donor funding cycles
[\[4\]](https://www.zotero.org/google-docs/?FCtJb8). This approach has
led to a graveyard of failed digital health systems where software or
hardware breaks lead to their abandonment. Furthermore, reliance on
independent contractors increases the risk of ‘over-engineered’ systems
with inherent complexity that requires highly-qualified and
specifically-trained technical staff to support and maintain. To reverse
this worrying trend, MoH staff must be empowered with EMRs that have
easy-to-use, built-in tools for addressing continually changing clinical
landscapes and guidelines.

### Process- & guideline-centric

Many attempts to build EMR systems for LMIC settings focus on data
collection with limited consideration of the care process. Healthcare is
delivered through a sequence of physical and mental tasks performed by
multiple people in one or more work environments i.e. workflows [\[5\],
\[6\]](https://www.zotero.org/google-docs/?YDnIQo). The sequences of
tasks form the basic building blocks of healthcare delivery and define
the data elements needed to complete and document the performance of an
activity. These activities roll up into a care visit where ideally a
clinician is presented with information to support best clinical
decisions for a patient. Given the complexity of care, workflows further
describe the different paths, through one or more branches, for
completing an activity. Electronic systems are most beneficial when they
help the healthcare provider successfully navigate the care delivery
workflow [\[7\]](https://www.zotero.org/google-docs/?749PG6). To provide
value for the healthcare provider and patients, EMR systems must
prioritise displaying accurate and timely information through
well-designed workflows rather than being designed for data collection,
billing, and reporting.

### Point-of-care

EMRs hold promise for improving the quality and delivery of care when
used by frontline healthcare workers during care delivery. Point-of-care
use has the dual benefit of supporting improved quality of care through
clinical decision support in addition to not requiring additional
staff/time to perform data entry required for reporting. Point-of-care
EMRs must offer value to clinicians to be used consistently and be
designed in a way that does not interfere with care provision.

### Touchscreen-first

Touchscreen user interfaces greatly reduce the need for hand-to-eye
coordination over traditional mouse and keyboard interfaces and offer an
intuitive user experience that facilitates learning and reduces the time
it takes to gain proficiency with electronic systems
[\[8\]](https://www.zotero.org/google-docs/?CAlvCm). Software initially
designed without a touchscreen user interface may have significant
limitations when later adapted for touchscreen
[\[9\]](https://www.zotero.org/google-docs/?Lte3sO). Developing a native
user interface around a well-defined set of criteria improves the
usability of systems and makes user adoption of the system easier.

### Low cost

LMICs have limited healthcare resources. While electronic systems can
improve the delivery and quality of care, this cannot be done at the
expense of providing essential commodities such as medicine, diagnostic
capabilities, or human resources. If the precious resources are to be
spent on electronic systems, the total cost of buying and owning the
system must be low and show positive return on investment. Furthermore,
many EMR projects in LMIC start as pilot projects to assess the
feasibility of different systems. Donors frequently pay for
demonstration/pilot projects with the expectation that the host country
governments will pay for nationwide scale-up and future maintenance of
successful projects. However, little attention is paid during
design-time to the overall cost of ownership of these solutions and what
they entail for the limited resources available.

### Low power

Continuous availability of electricity remains a problem in many LMICs
and their health facilities \[10\]. EMRs require electricity, preferably
uninterrupted, to function. As such, power backups are essential to
ensure uninterrupted service. The cost of power backup can often exceed
the cost of the computing hardware when power consumption is not
considered. To make economical use of available power during prolonged
power outages, low power devices (especially for workstations, servers,
and network equipment) are preferable. Further consideration must be
paid to the choice of power backups as traditional UPS systems are
designed for infrequent and brief power outages unlike the frequent,
prolonged outages that are common in LMICs.

We believe careful consideration of these themes will spark a rethink of
choices and approaches when developing EMRs in LMICs. We acknowledge
that the LMIC-first approach may result in different interpretations and
implementations based on the context and the different problems that the
implementations address. However, these themes support more careful
exploration of creative, innovative, and sustainable EMR solutions that
positively impact care delivery processes and ultimately, patient
outcomes.

## References

[\[1\] L. M. Puchalski Ritchie *et al.*, “Low- and middle-income
countries face many common barriers to implementation of maternal health
evidence products,” *Journal of Clinical Epidemiology*, vol. 76, pp.
229–237, Aug. 2016, doi:
10.1016/j.jclinepi.2016.02.017.](https://www.zotero.org/google-docs/?7We5BB)

[\[2\] L. Dornan, K. Pinyopornpanish, W. Jiraporncharoen, A. Hashmi, N.
Dejkriengkraikul, and C. Angkurawaranon, “Utilisation of Electronic
Health Records for Public Health in Asia: A Review of Success Factors
and Potential Challenges,” *Biomed Res Int*, vol. 2019, Jul. 2019, doi:
10.1155/2019/7341841.](https://www.zotero.org/google-docs/?7We5BB)

[\[3\] F. F. Odekunle, R. O. Odekunle, and S. Shankar, “Why sub-Saharan
Africa lags in electronic health record adoption and possible strategies
to increase its adoption in this region,” *Int J Health Sci (Qassim)*,
vol. 11, no. 4, pp. 59–64,
2017.](https://www.zotero.org/google-docs/?7We5BB)

[\[4\] P. Littlejohns, J. C. Wyatt, and L. Garvican, “Evaluating
computerised health information systems: hard lessons still to be
learnt,” *BMJ*, vol. 326, no. 7394, pp. 860–863, Apr. 2003, doi:
10.1136/bmj.326.7394.860.](https://www.zotero.org/google-docs/?7We5BB)

[\[5\] C. Cain and S. Haque, “Organizational Workflow and Its Impact on
Work Quality,” in *Patient Safety and Quality: An Evidence-Based
Handbook for Nurses*, R. G. Hughes, Ed. Rockville (MD): Agency for
Healthcare Research and Quality (US),
2008.](https://www.zotero.org/google-docs/?7We5BB)

[\[6\] “What is workflow? \| AHRQ Digital Healthcare Research: Informing
Improvement in Care Quality, Safety, and Efficiency.”
https://digital.ahrq.gov/health-it-tools-and-resources/evaluation-resources/workflow-assessment-health-it-toolkit/workflow
(accessed Feb. 08, 2021).](https://www.zotero.org/google-docs/?7We5BB)

[\[7\] C. P. Friedman, “What informatics is and isn’t,” *J Am Med Inform
Assoc*, vol. 20, no. 2, pp. 224–226, 2013, doi:
10.1136/amiajnl-2012-001206.](https://www.zotero.org/google-docs/?7We5BB)

[\[8\] Z. L. Lewis, G. P. Douglas, V. Monaco, and R. S. Crowley,
“Touchscreen task efficiency and learnability in an electronic medical
record at the point-of-care,” *Stud Health Technol Inform*, vol. 160,
no. Pt 1, pp. 101–105,
2010.](https://www.zotero.org/google-docs/?7We5BB)

[\[9\] G. P. Douglas, Z. Landis-Lewis, and H. Hochheiser, “Simplicity
and usability: lessons from a touchscreen electronic medical record
system in Malawi,” *interactions*, vol. 18, no. 6, pp. 50–53, Nov. 2011,
doi:
10.1145/2029976.2029990.](https://www.zotero.org/google-docs/?7We5BB)

[\[10\] S. Chawla *et al.*, “Electricity and generator availability in
LMIC hospitals: improving access to safe surgery,” *J Surg Res*, vol.
223, pp. 136–141, Mar. 2018, doi:
10.1016/j.jss.2017.10.016.](https://www.zotero.org/google-docs/?7We5BB)
