* Mdnotes File Name: [[kimballDataWarehouseToolkit2013]]

# Extracted Annotations (2021-03-25)

> "One of the most important assets of any organization is its information. This asset is almost always used for two purposes: operational record keeping and analytical decision making." ([Kimball&Ross 2013:38](zotero://open-pdf/library/items/6Z2USF66?page=38))

> "The DW/BI system must present information consistently. The data in the DW/BI system must be credible. Data must be carefully assembled from a variety of sources, cleansed, quality assured, and released only when it is fi t for user consumption" ([Kimball&Ross 2013:39](zotero://open-pdf/library/items/6Z2USF66?page=39))

> "Normalized 3NF structures are immensely useful in operational processing because an update or insert transaction touches the database in only one place. Normalized models, however, are too complicated for BI queries" ([Kimball&Ross 2013:44](zotero://open-pdf/library/items/6Z2USF66?page=44))

> "The fact table in a dimensional model stores the performance measurements resulting from an organization's business process events." ([Kimball&Ross 2013:46](zotero://open-pdf/library/items/6Z2USF66?page=46))

> "The term fact represents a business measure" ([Kimball&Ross 2013:46](zotero://open-pdf/library/items/6Z2USF66?page=46))

> "Each row in a fact table corresponds to a measurement event" ([Kimball&Ross 2013:46](zotero://open-pdf/library/items/6Z2USF66?page=46))

> "The most useful facts are numeric and additive" ([Kimball&Ross 2013:47](zotero://open-pdf/library/items/6Z2USF66?page=47))

> "dimension tables often have many columns or attributes. It is not uncommon for a dimension table to have 50 to 100 attributes" ([Kimball&Ross 2013:49](zotero://open-pdf/library/items/6Z2USF66?page=49))

> "Dimension tables tend to have fewer rows than fact tables" ([Kimball&Ross 2013:49](zotero://open-pdf/library/items/6Z2USF66?page=49))

> "Dimension attributes serve as the primary source of query constraints, groupings, and report labels." ([Kimball&Ross 2013:49](zotero://open-pdf/library/items/6Z2USF66?page=49))

> "Dimension table attributes play a vital role in the DW/BI system. Because they are the source of virtually all constraints and report labels" ([Kimball&Ross 2013:49](zotero://open-pdf/library/items/6Z2USF66?page=49))

> "Attributes should consist of real words rather than cryptic abbreviations" ([Kimball&Ross 2013:49](zotero://open-pdf/library/items/6Z2USF66?page=49))

> "When triaging operational source data, it is sometimes unclear whether a numeric data element is a fact or dimension attribute. You often make the decision by asking whether the column is a measurement that takes on lots of values and participates in calculations (making it a fact) or is a discretely valued description that is more or less constant and participates in constraints and row labels (making it a dimensional attribute)." ([Kimball&Ross 2013:50](zotero://open-pdf/library/items/6Z2USF66?page=50))

*The designer’s dilemma of whether a numeric quantity is a fact or adimension attribute is rarely a difficult decision. Continuously valued numeric observations are almost always facts; discrete numeric observations drawn from a small list are almost always dimension attributes. ([note on p.50](zotero://open-pdf/library/items/6Z2USF66?page=50))*

 

> "Instead of third normal form, dimension tables typically are highly denormalized" ([Kimball&Ross 2013:51](zotero://open-pdf/library/items/6Z2USF66?page=51))

> "Because dimension tables typically are geometrically smaller than fact tables, improving storage effi ciency by normalizing or snowfl aking has virtually no impact on the overall database size. You should almost always trade off dimension table space for simplicity and accessibility." ([Kimball&Ross 2013:51](zotero://open-pdf/library/items/6Z2USF66?page=51))

> "Each business process is represented by a dimensional model that consists of a fact table containing the event's numeric measurements surrounded by a halo of dimension tables that contain the textual context that was true at the moment the event occurred" ([Kimball&Ross 2013:52](zotero://open-pdf/library/items/6Z2USF66?page=52))

> "Another way to think about the complementary nature of fact and dimension tables is to see them translated into a report. Dimension attributes supply the report filters and labeling, whereas the fact tables supply the report's numeric values" ([Kimball&Ross 2013:53](zotero://open-pdf/library/items/6Z2USF66?page=53))

