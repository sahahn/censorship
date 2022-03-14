# Visualizing Censorship Legislation
## Tracking Legislative Restrictions on the Freedom to Read, Learn, and Teach

Welcome! Here you can explore educational gag order bills and the various forms of censorship the bills have covered since the beginning of 2021 to present day.
More information and background about this wave of legistlation can be found through a series by [PEN America](https://pen.org/report/educational-gag-orders/).

## The Data

On this website we provide a number of interactive visualizations related to the number of bills passed, presented, or denied in each state, the subject of the bills, as well as references to the bills themselves. The underlying data being visualized here is made avaliable and still being actively updated by PEN America (the public spreedsheet itself can be found [here](https://docs.google.com/spreadsheets/d/1Tj5WQVBmB6SQg-zP_M8uZsQQGH09TxmBY73v23zpyr0/edit#gid=107383712)). As this dataset is being actively updated (adding new bills, changing the status of bills, ect...) we have designed this website to update itself weekly based on the latest most up to date version of the data (see github actions script [here](https://github.com/sahahn/censorship/blob/master/.github/workflows/update_maps.yml)).

### Bill Explorer

Use this map to explore the total number of bills each state has passed, is considering, or has denied. To view the bills themselves, click on the state pin and click on the bill you’d like to explore.

{% include bill_explorer.html %}

### By Target

Use this map to explore the bill censorship target topics or groups. This map allows you to view the number of bills overall, the bills that target censorship of K12 groups, college groups, state contractors or institutions. The map also allows you to view the bill breakdown of bills that target gender/sexuality, religion, or race/ethnicity. If a bill relates to multiple of these categories, it is shown in duplicate under the categories it relates to (i.e. bills that aim to censor K12 schools and mention content about gender and sexuality, that bill will show up when you select K12 and the Gender / Sexuality buttons).

{% include bill_targets.html %}

### By Status

Use this map to explore the number of bills in each state by bill status. You can select to view the bills that are currently pending, the number that have been denied or died, and the number of bills that are currently signed into law since the start of 2021.

{% include bills_by_status.html %}

### By Year

Use these maps to explore bill censorship target topics or groups in each state by bill year. These maps allows you to view the number of bills for the specified map year, the bills that target censorship of K12 groups, college groups, state contractors or institutions in the specified map year. The maps also allows you to view the bill breakdown of bills that target gender/sexuality, religion, or race/ethnicity for the specified year. If a bill relates to multiple of these categories, it is shown in duplicate under the categories it relates to (i.e. bills that aim to censor K12 schools and mention content about gender and sexuality, that bill will show up when you select K12 and the Gender / Sexuality buttons).

{% include bill_targets_2022.html %}
{% include bill_targets_2021.html %}

Use these maps to explore the number of bills in each state by bill status for the specified map year. You can select to view the bills that are currently pending, the number that have been denied or died, and the number of bills that are currently signed into law for the specified map year.

{% include bills_by_status_2021.html %}
{% include bills_by_status_2022.html %}

### By Status and Target

Use these maps to explore the bill censorship target topics or groups, categorized by the status of the bills. These maps allows you to view the number of bills for the specified bill status category, the bills that target censorship of K12 groups, college groups, state contractors or institutions in the specified bill status category. The maps also allow you to view the bill breakdown of bills that target gender/sexuality, religion, or race/ethnicity for the specified year. If a bill relates to multiple of these categories, it is shown in duplicate under the categories it relates to (i.e. bills that aim to censor K12 schools and mention content about gender and sexuality, that bill will show up when you select K12 and the Gender / Sexuality buttons)

{% include pending_bill_targets.html %}
{% include signed_bill_targets.html %}
{% include dead_bill_targets.html %}


### About Us

We are a group of students at UVM: Bryn Loftness, Nana Nimako & Sage Hahn. This project was completed as a part of the Data Lab w/ Laurent Hébert-Dufresne. 


![logo](https://raw.githubusercontent.com/sahahn/censorship/master/group_logo.png)
