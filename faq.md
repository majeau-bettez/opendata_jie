FAQ on Publication criteria - Data citation
=============================================

### How should I cite a database in JIE?

Databases should be directly cited stating explicitly and unambiguously the version used. Solely citing a report or a publication describing a database is insufficient. The JIE citation style for databases follows the overall structure of APA webpage citation:
> Authors. (year-of-database-publication). *Title-including-version-number-and-other-disambiguation-identifiers.* Retrieved [date-of-retrieval] from [location-which-is-either-url-or-software]

### The authors of a dataset require that I cite their article if my study relies on their dataset. Should I cite this article AND the dataset separately?

Yes. You should cite both.

### Do I have to cite individual data points, or individual processes, from a database?

No. In most cases, that would be impractical, and therefore only the citation of the dataset is required. However, JIE strongly encourages linking to individual data points in system descriptions, notably by referring to them using their complete name, identification numbers (IDs) and Unique Universal IDs (UUIDs).

### What do you mean by database “location”?

“Location” points to the source of the database, as accessed by the researcher. This information will typically be the URL of a website or the name and version of a software that ships with the prepackaged database.

### When I obtain a dataset pre-packaged in a software, why must I specify the software name and version?

Software developers may alter a dataset to adapt it to their software structure, therefore citing the software name and version is necessary.

### Is JIE creating yet another citation style for databases? Aren't there enough?

The citation guidelines do not represent a new citation style for databases. Instead, the citation guideline merely adapts the citation of online material to reflect two particularities: 1) disambiguation identifiers may be required beyond version numbers to reflect different variants of a database, like different aggregation levels, allocation methods, and constructs; and (2) databases may be distributed as prepackaged (and modified) in software, rather than exist strictly online.


FAQ on Publication criteria – Data in figures and tables
========================================================

### In a nutshell, what do I have to do?

The quantitative data in your article's figures should also be published in a numerical format (like a spreadsheet) to precisely and easily communicate the values of the different data points.

### Why do I have to do this?

This measure aims to facilitate reuse of published data and results. Although figures are essential to communicate results, extracting data for reuse from these figures necessarily implies a visual evaluation, which can be laborious and imprecise. By providing the same data in numerical, machine readable format, these barriers and uncertainties are removed.

### Some of the data that led to a figure is proprietary, I cannot share it. Does this mean I cannot meet this publication requirement?

Not at all. This is not a problem. The only data that must be tabulated is the data that is directly represented _in_ the figure.

### What file formats are acceptable to publish the data in my figures?

A file format that ensures that the numerical data can be readily recognized by both software and humans should be chosen. Examples include comma-separated-value (CSV) files, Microsoft Office Open XML spreadsheet (XLSX files), OpenDocument spreadsheet (ODS files), and JSON files.

### What file formats are NOT acceptable to publish the data in my figures?

File formats that do not allow for efficient distinction between numerical and non-numerical values, or data and table structures, are excluded. This includes PDF files, Microsoft Word files, OpenDocument text (odt) files. Also, files that are not based on plain text files (or zipped plain text files) are not sufficiently human readable and require specialized software to inspect; therefore xls, xlsb, and other proprietary binary formats are excluded.


### What table is considered big enough to require that the data be provided in spreadsheet?

Beyond 50 data points, JIE considers that extracting numerical data from a PDF table becomes a barrier to data reuse. To maximize impact, you are asked to share this same table in a format that is more machine readable to facilitate numerical computation (spreadsheet, csv, etc.)

### Does this apply to tables and figures SI?

No. It is encouraged - not required - for tables and figures in SI.

### There is some sensitive data _in_ the figure, so I feel I cannot publish it in numerical format.

Any data in a figure can be extracted with enough effort. It is simple to print a figure on a poster-size piece of paper and use a fine ruler to measure with good precision heights of bars, slopes, etc. Highly sensitive data do not belong in result figures.

### Where should I publish this data?

For the data directly present in figures, authors are free to publish this as part of the supporting information (SI). Alternatively, the authors may choose to publish these data in a trusted data repository, which will assign a digital object identifier (DOI) to the data set, such that it can be cited in the article.

Data Openness Badge
===================



### What does it mean to be awarded a badge?

The Data Openness Badge rewards articles that go above and beyond common practice to ensure that their data and system descriptions will be useful to the community, through careful publication of well documented and formatted data.

### How can I be awarded a badge? How will the process go?

Authors will be able to request a data openness badge upon submission of their manuscript, and reviewers will be asked to verify its applicability. The final approval will rest with the associate editor and the editorial office. The position of Data Editor has also been initiated to accompany the process.


### Does a Data Openness Badge certify that a study is reproducible?

The data openness badge focuses on contribution and reusability of data and system descriptions. It does not address the manipulation steps and calculations that link these system descriptions to final results, and as such it does not ensure that a study could be easily reproduced in detail. JIE is considering the introduction of such a “procedural transparency badge”.

### Are there two different badges, or just one with two dimensions?

There is only one badge system, which takes into account two dimensions: the contribution of data; and the formatting and accessibility of this data. For each dimension, there are two levels: gold and silver; both go far beyond minimal publication requirements and common practice. This gives a total of four variants: Gold contribution – gold accessibility, gold contribution – silver accessibility, silver contribution – gold accessibility, and silver contribution – silver accessibility.


Data Contribution
-----------------

### I would like to contribute my data for reuse, but my study partly relies on a commercial/licensed database. Can I still get gold? How?

Yes, you can still earn a gold level for data contribution despite relying on licensed database. The data openness badge does not require the authors to copy or “re-publish” data from external sources. The contribution that is rewarded is the contribution of primary data, i.e., the new system descriptions developed for the article. In these system descriptions, it is sufficient to link to the relevant data points in the licensed database such that another license holder could unambiguously identify them, for example by referring to them with their database identification numbers (ID) and complete names.

### I would like to contribute my research data, but I am not at liberty to disclose parts of my primary data and system description because of confidentiality concerns. Am I barred from getting a badge?

No, you are not barred for the data openness badge, as the silver level was designed for just such an eventuality.

### What is the difference between the gold and silver level?

The gold level places high requirements in terms of transparency: the complete system description must be published at the same level of resolution and completeness as was used by the authors to calculate their results. Such an extensive data contribution is not always possible, however, notably due to confidentiality concerns. The silver level therefore recognizes the value of contributing (non-sensitive) parts of a system description, providing useful data and process descriptions (among others) for broader use by the community.


### What kind of data should I submit? Raw data, reconciled system descriptions, or intermediate results?

This badge rewards the contribution of coherent and reusable descriptions of systems or of parts of systems. Although we recognize the importance of documenting raw observations and the subsequent data curation and harmonization steps to ensure reproducibility of research, such aspects will be addressed in a “procedural transparency” badge that is currently under development. The current data openness badge rather focuses on rewarding contributions of more readily reusable and adaptable system descriptions that result from these curation and harmonization steps. For example, such system descriptions may be structured in terms of processes, activities, agents, objects, flows, stocks, exchanges with the biophysical environment, system boundaries, and behaviors and actions.


### Must the data be submitted under a certain license?

For both gold and silver levels, the data are to be published under a free, open-content license that explicitly allows use, distribution, and production of derivative work. We encourage the use of well established and recognized licenses, such as Creative Commons’ Public Domain (CC0), Attribution (CC-BY), and Attribution ShareAlike (CC-BY-SA) licenses, or equivalent. Restrictions on commercial use (e.g., Creative Common's non-commercial clause CC-NC) are acceptable, but not restrictions on derivative work.

### Is there a template to submit data?  Is the process laborious?

The interdisciplinary nature of research in industrial ecology has so far prevented the emergence of a common data structure, let alone a common approach to system descriptions. Consequently, no template is provided, and researchers are encouraged to structure their data in the most natural way for their research activities, thereby reducing the workload associated with data publication. Practical considerations of accessibility and interoperability are addressed in the second dimension of the Data Openness badge (see Data Accessibility)

### Where should I publish my data contribution?

These data should be published in a scientific repository (e.g., Figshare, Zenodo) and cited with their DOI in the article; although exceptions may be made for exceptionally small data sets, which could be published in SI.

Data Accessibility
------------------


### What is the goal of this dimension of the Data Openness Badge ?

The broad diversity of perspectives, techniques, software tools, and data formats in industrial ecology research constitutes an obstacle to efficient re-use of data and consolidation of research results. This badge aims both to promote best practice in data publication and incentivize a convergence and greater interoperability of data formats.

### What file formats are acceptable for the data accessbility badge?

To reach the gold level, the system description should be formatted such that it is (1) both machine and human readable, and (2) directly importable in a free analysis software. For the silver level, it is sufficient to comply with requirement 1 or 2.

### What is meant by “machine readable” data format?

The data should be “machine readable” in the sense that a relevant software can readily distinguish words from numbers, recognize table structures, etc. For example, a system description in a spreadsheet is machine readable, whereas extracting quantitative data from PDF or word processing files (.docx, odt, etc.) is excessively complicated.

### What is meant by “human readable” data format?

The data should “human readable” such that it can be read and understood by humans in plain text files. Examples of such file formats include comma separated values (csv), json, and xml files. Data formats that rely on compressed (zipped) versions of these plain text formats ---notably the OpenDocument Spreadsheet format (ods files) and Microsoft's Office Open XML Workbook format (.xlsx spreadsheet files) --- are also accepted. Conversely, binary files that obfuscate the data structure and require a dedicated software to access the data are not eligible, as they constitute an obstacle to interoperability.

### What is meant by “directly importable in free analysis software”?

Data should be structured such that it can directly be imported in a free software apt to perform the relevant analysis.  The aim of this requirement is to promote well structured data that can be inspected and analyzed without financial barriers. There are many ways of satisfying this requirement. (1) Data may be structured following an open standard that can be read both by free and non-free analysis software (e.g., ecospold2 format for LCAs).  (2) Another option is to embed all calculations and analyses together with the data in a spreadsheet that can be opened in a free office suite without loss of functionality. (3) Alternatively, studies that publish free analysis software and parsers along with their data automatically fulfill this requirement.

### I made my analysis in a non-free software. Am automatically blocked from attaining gold in terms of data accessibility?

No, this is not a problem, as long as you can export your system description to an open standard format that can then be directly imported in an equivalent free analysis tool.

### I do not follow a standard data structure, and instead provide parser scripts and free code to perform the analysis. Is that acceptable?

Yes.

### Why are some spreadsheet formats acceptable (xlsx, ods) and not others (xls, xlsb)?

Some spreadsheet formats (xlsx, ods) are “open”, as they follow an open standard and rely on easily inspected plain text XML files that are merely compressed (zipped) in a single file. Other spreadsheet formats (xls and xlsb) store data in (proprietary) binary formats, greatly limiting their inspection and interoperability.
