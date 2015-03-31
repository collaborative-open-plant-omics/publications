--------------   -------------------------------------------
**Title**        Aiding the journey from data to publication in the plant sciences
**Author**       _Presenting Author_, Author Two, Author Three ...
**Affiliation**  The Genome Analysis Centre
**Contact**       robert.davey@tgac.ac.uk
**URL**          <https://github.com/collaborative-open-plant-omics/COPO.git>
**License**      Common Public Attribution License Version 1.0 (CPAL)
--------------   -------------------------------------------

The aim of open science is to make scientific research accessible to
an inquiring public. This involves mechanisms for preserving and
publishing research objects such as data, methods, software and manuscripts in
an efficient and timely manner thus facilitating experimental reproducibility and transparency.

Existing mechanisms for enabling open science in plant research within the ``omics'' fields, are limited by: (i) complicated and time-consuming procedures for repository
deposition; (ii) a lack of interoperability between
disparate information sources and mechanisms; (iii) sub-optimal search and retrieval
facilities across data repositories.

COPO (Collaborative Open Plant Omics) is an information
aggregation and publishing platform, designed to help plant scientists publish
and share research outputs and ease access to services across disparate sources of information. COPO is based on
Django (www.djangoproject.com), a high-level Python
web framework that offers rapid development and pragmatic design. In
particular, the system uses a web
front-end and a set of APIs (Application Programming
Interfaces) to facilitate the aggregation of disparate research
objects into logical profiles which represent a body of research. A
profile can contain for example, sequence data, source codes, pdf files, image data or posters and presentations,
all of which are fully described with associated meta
data. The system acts as a brokering service,
providing a useable interface to different repositories offloading the burden of data deposition from scientists. COPO seamlessly allows deposition of research objects to services
such as the European Nucleotide Archive (www.ebi.ac.uk/ena) and will interface with others such as GigaScience (www.gigasciencejournal.com), f1000 (www.f1000research.com) and Slideshare (www.slideshare.net) as well as grid based data infrastructures such as iRODS
(www.irods.org). Accessions to deposited objects will be stored in a COPO profile to be indexed and publicly searchable. DOIs (Digital Object Identifiers) will be minted, mapping to COPO profiles providing a permanent digital identity to be referenced around the Internet. COPO will take advantage of ISATools/ISATab (www.isa-tools.org) to provide technical continuity between services and researchers.

Using APIs and virtualised resources, COPO will integrate other existing services such as the Galaxy
(www.galaxyproject.org) and iPlant (www.iplantcollaborative.org) analytical platforms; figshare (www.figshare.com), Research Objects (www.researchobject.org), Wolfram Data Framework (www.wolfram.com/data-framework/)(???) and
GigaScience platforms thus providing access to disparate and
geographically distributed resources through a single point. For example, by hooking into locally hosted instances of
iPlant and Galaxy using data and workflows stored in COPO profiles, experimental results may be
easily reproduced and verified, or comparative studies may be
conducted with alternative data.

The availability of a plethora richly labeled research objects means that semantic inferences can be made, providing user customised suggestions for workflows and datasets. Such inferences are domain agnostic, with the potential for researchers to discover useful results from other fields. 

We believe that the ongoing development of COPO will contribute to state-of-the-art open science by enforcing community-accepted standards for data representation; facilitating submission to persistent archival resources for data publication and citation; enabling seamless transition from data to analysis services and improving discoverability via contextualised ontological inference. 


