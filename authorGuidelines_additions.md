Edits to jie's main guidelines
===================

This document holds potential additions and modifications [to these JIE author guidelines](http://jie.yale.edu/jie-style-guide-accepted-manuscripts), based on [Hertwich et al. 2018](https://doi.org/10.1111/jiec.12738).


New section: Database citation
------------------------------

All databases used in the article should be directly cited. Database
citation must provide sufficient information to unambiguously identify
the specific database used. Whenever applicable, this citation should
provide database version number and any other disambiguating
identifiers, the year of publication, the date of access, and the
location at which it was accessed. This location can be *either* a URL (preferably based on a digital object identifier, DOI) or a software in which the database is embedded. Please use only static URLs, preferably with persistent identifiers or DOIs. 

This database information should be arranged to follow the APA citation style for web pages:
> Authors. (year-of-database-publication). *Title-including-version-number-and-other-disambiguation-identifiers.* Retrieved [date-of-retrieval] from [location-which-is-either-url-or-software]

### Examples

*Pull requests for additional use cases as the ones below are welcome.*

Please also consider suggested citations by the data provider, e.g. https://www.ecoinvent.org/support/faqs/first-time-users/how-do-i-cite-ecoinvent.html

**Example 1:** EXIOBASE Database

> EXIOBASE Consortium. (2014). *EXIOBASE, version 2.2.2, product-by-product, industry-technology-assumption coefficients, for year 2007*. Retrieved November 11, 2018, from https://www.exiobase.eu/index.php/data-download/exiobase2-year-2007-full-data-set/79-mriot-pxp-ita-coefficient-version2-2-2.

**Example 2:** Ecoinvent dataset as implemented in LCA software

> Ecoinvent Centre. (2016). *Ecoinvent database, version 3.3, cut-off system model*. Retrieved February 1, 2018, from Simapro Software version 8.4.

In *addition* to the direct database citation, the authors are free to
cite a scientific publication or a report that accompanies the database.
This can be necessary to comply with the citation requirements and
license agreement of the database provider. However this complementary
citation does *not* replace a direct citation of the database, which
remains mandatory to clearly identify the version of the database used.

**Example 3:** Complementary citation for EXIOBASE:

Wood, R., Stadler, K., Bulavskaya, T., Lutter, S., Giljum, S., de Koning, A., … Tukker, A. (2014). Global Sustainability Accounting—Developing EXIOBASE for Multi-Regional Footprint Analysis. *Sustainability*, 7(1), 138–163. https://doi.org/10.3390/su7010138

**Example 4:** of complementary citation for ecoinvent:

See also: https://www.ecoinvent.org/support/faqs/first-time-users/how-do-i-cite-ecoinvent.html

Wernet, G., Bauer, C., Steubing, B., Reinhard, J., Moreno-ruiz, E., & Weidema, B. (2016). The ecoinvent database version 3 (part I): overview and methodology. The International Journal of Life Cycle Assessment, 3(9), 1218–1230. https://doi.org/10.1007/s11367-016-1087-8


Addition to existing sections: 10. Artwork, figure and tables
-------------------------------------------------------------

**Headline: Underlying data**

All data that is graphically represented in figures must also be
published in a numerical, tabular format to ensure unambiguous
interpretation and ease of data reuse. This procedure facilitates the
unambiguous inspection and usage of quantitative information contained
in all key results presented as figures and graphs, without requiring
the visual extraction or approximation. A file format that ensures that
the numerical data can be readily recognized by both software and humans
should be chosen, such as comma-separated-value (CSV) files or a
spreadsheet (e.g., .xlsx or .ods files).

In the same manner, large tables --- more than 50 numerical
data points --- in the manuscript should also be provided in a numerical
format to avoid the inefficient and error-prone process of manually
copying large amounts of data from the article.

Authors are free to fulfill this requirement by submitting the data
files as a supporting information (SI) to the article or by publishing
the dataset in a repository and citing it (see section on data
publication). In either case the relationship between manuscript figure or article must be explained in the data file, e.g. "Data used for plotting Figure 4".


New section: Optional Data publication rewarded by Data Openness Badges
-----------------------------------------------------------------------

\[Could be after 12. Suporting Information\]

Except for data that is directly represented in the figures and tables
of the manuscript (See 10. Artwork, figures and tables), there is no
mandatory publication of data in support of research articles submitted
to the *Journal of Industrial Ecology*.

However, authors are strongly encouraged to openly publish the primary
data and system models that underpins their analysis, to increase the
transparency, reusability, and impact of their research. Such *complete
or partial* publication of system descriptions may entitle the article
to a **data openness badge** of recognition. This flexible badge system
rewards both the extent of data *contribution* and the formatting of
this data for increased interoperability and *accessibility* (see
definitions and criteria for the four levels at www.\*\*jie.com\*).

![Data openness badge v1.0](fig/DTTF_badge_v6.png)

These data should be published in a scientific repository (e.g.,
Figshare, Zenodo) and cited with their DOI in the article; although
exceptions may be made for exceptionally small data sets, which could be
published in SI.

This voluntary publication of the article's system description in a
dataset only concerns **primary data and system descriptions**, i.e.,
the novel parts of the author's system description. Data that is reused
from previous studies or from databases should be unambiguously cited
and linked to in the system description, but not “re-published” (see
section “Database citation”).

Please refer to the [Data Openness badge](opennessBadge_guidelines.md) for more details. 