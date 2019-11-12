Homelessness Across the U.S.
============================

Data work for UMD's Howard Center for Investigative Journalism, fall 2019.

*Created by Roxanne Ready (<http://roxanneready.com>)*

*Reporter: Roxanne Ready*

Project goal
------------

This work was completed for UMD's Howard Center for Investigative Journalism as part of a large, collaborative project about the criminalization of homelessness in Baltimore and across the U.S.

Project notes
-------------

### Staff involved

-   Kathy Best, Howard Center Director
-   Marty Kaiser, Howard Distinguished Visiting Fellow
-   Sean Mussenden, Data Bureau Chief
-   Deb Nelson, project lead
-   Roxanne Ready, data journalist
-   Theresa Diffendal, data journalist
-   Investigative journalism class, fall 2019

### Data sources

<table>
<colgroup>
<col width="24%" />
<col width="19%" />
<col width="55%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Data</th>
<th align="left">Source</th>
<th align="left">URL</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">Point in Time (PIT) homelessness count</td>
<td align="left">Dept. of Housing and Development</td>
<td align="left"><a href="https://www.hudexchange.info/programs/coc/coc-homeless-populations-and-subpopulations-reports/" class="uri">https://www.hudexchange.info/programs/coc/coc-homeless-populations-and-subpopulations-reports/</a></td>
</tr>
<tr class="even">
<td align="left">Community of Care (CoC) cluster analysis</td>
<td align="left">Zillow</td>
<td align="left"><a href="https://www.zillow.com/research/data/" class="uri">https://www.zillow.com/research/data/</a></td>
</tr>
<tr class="odd">
<td align="left">CoC-to-tract crosswalk</td>
<td align="left">Tom Byrne</td>
<td align="left"><a href="https://github.com/tomhbyrne/HUD-CoC-Geography-Crosswalk" class="uri">https://github.com/tomhbyrne/HUD-CoC-Geography-Crosswalk</a></td>
</tr>
<tr class="even">
<td align="left">Baltimore court data</td>
<td align="left">scraped by CNS</td>
<td align="left"><a href="http://casesearch.courts.state.md.us/casesearch/" class="uri">http://casesearch.courts.state.md.us/casesearch/</a></td>
</tr>
</tbody>
</table>

Technical
---------

PIT, cluster and crosswalk are available in this repo. Baltimore court data is too large to store here and is stored on Amazon Web Servers. Please contact the project manager for permission to access the dataset, then run `baltimore-court-data.Rmd` using your AWS username and password.

An outline of the basic project structure is available at <https://github.com/associatedpress/cookiecutter-r-project>

### Project setup instructions

After cloning the git repo:

Open `homelessness-across-us.Rproj` in RStudio.

Data notes
----------

This data was intended for use by field reporters to narrow their initial reporting, but due to limitations in the data (especially data over time), **findings should not be included in final articles**. Limitations are discussed in more detail in the respective analyses files.
