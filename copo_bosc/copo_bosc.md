--------------   -------------------------------------------
**Title**        Aiding the journey from data to publication in the plant sciences
**Author**       _Presenting Author_, Author Two, Author Three ...
**Affiliation**  <http://www.tgac.ac.uk/>
**Contact**       robert.davey@tgac.ac.uk
**URL**          <https://github.com/collaborative-open-plant-omics/COPO.git>
**License**      Name of your [open source license] (and link if non-standard)
--------------   -------------------------------------------

The aim of open science is to make scientific research accessible to
an inquiring public. This often involves mechanisms for preserving and
publishing research artefacts such as data, methods, and software in
an efficient and timely manner.

Existing mechanisms for enabling open science in plant research,
particularly within the genomics field but also high-throughput
transcriptomics, proteomics and metabolomics, are limited in a number
of ways: (i) complicated and time-consuming procedures for repository
deposition; (ii) digital gap or lack of interoperability between
disparate information sources; (iii) sub-optimal search and retrieval
facilities across data repositories.

We present COPO (Collaborative Open Plant Omics), an information
aggregation and publishing platform, to help plant scientists publish
and share research outputs, but also to ease access to important
services across disparate sources of information. COPO is based on
Django (https://www.djangoproject.com), a high-level Python
Web framework that offers rapid development and pragmatic design. In
particular, the system uses a Web
front-end and a set of APIs (Application Programming
Interfaces) to facilitate the aggregation of disparate research
objects into logical profiles that represent a body of research. A
profile can contain, for example, a sequence of data, source codes,
and pdf files, all of which are well described with associated meta
data. In the first instance, the system acts as a brokering service,
providing a useable interface to different repositories in order to
offload the burden of data deposition from scientists. Research
objects (e.g., sequence data) can be submitted seamlessly to services
such as EBI (http://www.ebi.ac.uk) data repositories and iRODS
(http://irods.org), and accessions to these objects, which correspond
to a profile, are persisted in COPO. Using these accessions (e.g.,
DOIs (Digital Object Identifiers)), a resolution component can then route
user queries to the original objects.

By using high quality and stable APIs and virtualised resources, COPO
has the potential of tying together other existing services such as: the
ISATools metadata suite (http://www.isa-tools.org); Galaxy
(http://galaxyproject.org), iPlant
(http://www.iplantcollaborative.org) analytical platforms; figshare
(http://figshare.com), Research Object, Scientific Data and
Gigascience (http://www.gigasciencejournal.com) platforms. This
provides much flexibility and ease of access to disparate and
geographically distributed resources through a single point of
access. For instance, by hooking into locally hosted instances of
iPlant and Galaxy using profile workflows, experimental results may be
easily reproduced and verified, or comparative studies may be
conducted with alternative data.

We believe that the ongoing development of COPO will contribute to the
state-of-the-art in enabling open science, particularly by offering the following
utility:

\begin{itemize}
\item enforcing community-accepted standards for data representation
\item facilitate submission to persistent archival resources, for data
  publication and citation
\item enable seamless transition from data to analysis services
\item facilitate discoverability through aggregated provenance (meta
  data) and suitable publication markup to link citable resources
\end{itemize}

