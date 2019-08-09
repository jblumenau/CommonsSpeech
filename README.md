The House of Commons Speeches Database, 1979 – 2019
===================================================

This repository holds links to and explanations of a database of
speeches delivered in the UK House of Commons between 3rd May 1979 and
25th July 2019. This data was compiled as an output of ESRC grant number
ES/N016297/1.

Download
--------

You can download the data as an XXXX file from this permanent hosting
site.

Overview
--------

The dataset consists of individual utterances made in the UK House of
Commons between 1979 and 2019. It also includes separate `csv` files
with some meta data for Members of Parliament during this period.

Codebook
--------

The following files and variables are included in the database.

### `speeches_19XX.csv`

These files include all speeches made in the House of Commons in the
space of a calandar year. In each file, the following variables are
included:

<table>
<colgroup>
<col style="width: 23%" />
<col style="width: 59%" />
<col style="width: 17%" />
</colgroup>
<thead>
<tr class="header">
<th style="text-align: left;">Variable Name</th>
<th style="text-align: left;">Description</th>
<th>Source</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;"><code>speech_id</code></td>
<td style="text-align: left;">Unique ID for speech</td>
<td></td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>person_id</code></td>
<td style="text-align: left;">The MP’s unique identifier (corresponds to IDs used in <a href="https://www.theyworkforyou.com/api/docs/getPerson">TheyWorkForYou</a>)</td>
<td>TheyWorkForYou/mySociety</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>mnis_person_id</code></td>
<td style="text-align: left;">The MP’s unique identifier</td>
<td></td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>name</code></td>
<td style="text-align: left;"></td>
<td></td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>debate_id</code></td>
<td style="text-align: left;"></td>
<td></td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>subdebate_id</code></td>
<td style="text-align: left;"></td>
<td></td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>debate_title</code></td>
<td style="text-align: left;"></td>
<td></td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>body</code></td>
<td style="text-align: left;">Text of speech</td>
<td></td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>date</code></td>
<td style="text-align: left;">Date</td>
<td></td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>hpos</code></td>
<td style="text-align: left;"></td>
<td></td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>gender</code></td>
<td style="text-align: left;"></td>
<td></td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>days_in_house</code></td>
<td style="text-align: left;"></td>
<td></td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>party</code></td>
<td style="text-align: left;"></td>
<td></td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>party_short</code></td>
<td style="text-align: left;"></td>
<td></td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>date_of_birth</code></td>
<td style="text-align: left;"></td>
<td></td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>n_words</code></td>
<td style="text-align: left;"></td>
<td></td>
</tr>
</tbody>
</table>

### `mps.csv`

A dataset of all MPs to have served in the Commons from 1979-2019.

<table>
<thead>
<tr class="header">
<th style="text-align: left;">Variable Name</th>
<th style="text-align: left;">Description</th>
<th>Source</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;"><code>speech_id</code></td>
<td style="text-align: left;">Unique ID for speech</td>
<td></td>
</tr>
</tbody>
</table>

### `mps.csv`
