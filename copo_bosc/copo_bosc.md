--------------   -------------------------------------------
**Title**        Aiding the journey from data to publication in the plant sciences
**Author**       _Presenting Author_, Author Two, Author Three ...
**Affiliation**  <http://www.tgac.ac.uk/>
**Contact**       robert.davey@tgac.ac.uk
**URL**          <https://github.com/collaborative-open-plant-omics/COPO.git>
**License**      Name of your [open source license] (and link if non-standard)
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
Django (https://www.djangoproject.com), a high-level Python
web framework that offers rapid development and pragmatic design. In
particular, the system uses a Web
front-end and a set of APIs (Application Programming
Interfaces) to facilitate the aggregation of disparate research
objects into logical profiles which represent a body of research. A
profile can contain for example, sequence data, source codes, pdf files, image data, posters, presentations etc. 
all of which are fully described with associated meta
data. The system acts as a brokering service,
providing a useable interface to different repositories to
offload the burden of data deposition from scientists. COPO seamlessly allows deposition of research objects to services
such as the European Nucleotide Archive (http://www.ebi.ac.uk/ena) and will interface with others such as GigaScience (http://www.gigasciencejournal.com), f1000 (http://f1000.com) and Slideshare (http://www.slideshare.net) as well as grid based data infrastructures such as iRODS
(http://irods.org). Accessions to deposited objects will be stored in a COPO profile and will be indexed and publicly searchable. DOIs (Digital Object Identifiers) will be minted mapping to COPO profiles providing a permanent digital identity to be referenced around the internet. COPO will take advantage of ISATools/ISATab (http://www.isa-tools.org) to provide technical continuity between services and researchers.

Using APIs and virtualised resources, COPO will integrate other existing services such as the Galaxy
(http://galaxyproject.org) and iPlant
(http://www.iplantcollaborative.org) analytical platforms; figshare
(http://figshare.com), Research Objects (http://www.researchobject.org), Wolfram Data Framework (https://www.wolfram.com/data-framework/)(???) and
GigaScience platforms thus providing access to disparate and
geographically distributed resources through a single point. For example, by hooking into locally hosted instances of
iPlant and Galaxy using workflows and data, stored in COPO profiles, experimental results may be
easily reproduced and verified, or comparative studies may be
conducted with alternative data.

The availability of a plethora richly labeled research objects means that ontological inferences can be made providing user customised suggestions for workflows and datasets. Such inferences are domain agnostic, therefore researchers may learn about results from different fields which they may not have seen otherwise.

We believe that the ongoing development of COPO will contribute to
state-of-the-art open science by enforcing community-accepted standards for data representation; facilitating submission to persistent archival resources for data publication and citation; enabling seamless transition from data to analysis services and facilitating discoverability through aggregated provenance and customised ontological inference. 


