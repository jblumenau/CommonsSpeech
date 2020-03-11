The House of Commons Speech Database, 1979 – 2019
=================================================

This repository holds links to and explanations of a database of
speeches delivered in the UK House of Commons between 3rd May 1979 and
5th November 2019. This data was compiled as an output of ESRC grant
number ES/N016297/1.

The dataset consists of individual utterances made in the UK House of
Commons between 1979 and 2019. You can download the data as a series of
`.csv` files from this permanent hosting site.

Data sources
------------

-   Speech data comes from TheyWorkForYou.com
-   Data on roles that MPs held in government, opposition, and in
    committee comes from the [Members Name Data
    Platform](http://data.parliament.uk/membersdataplatform/memberquery.aspx)
    and the [Parliamentary Data Platform](https://beta.parliament.uk/)
    as accessed via the [pdpy](https://github.com/olihawkins/pdpy)
    package
-   Data on election results comes from
    [www.electoralcalculus.co.uk](http://www.electoralcalculus.co.uk)

Codebook
--------

Each file in the data include all speeches made in the House of Commons
in the space of a calandar year. In each file, the following variables
are included:

<table>
<colgroup>
<col style="width: 28%" />
<col style="width: 71%" />
</colgroup>
<thead>
<tr class="header">
<th style="text-align: left;">Variable Name</th>
<th style="text-align: left;">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;"><code>person_id</code></td>
<td style="text-align: left;">The MP’s unique identifier (corresponds to IDs used in <a href="https://www.theyworkforyou.com/api/docs/getPerson">TheyWorkForYou</a>)</td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>mnis_person_id</code></td>
<td style="text-align: left;">An alternative MP identifier (corresponds to IDs used in the <a href="http://data.parliament.uk/membersdataplatform/memberquery.aspx">Members Name Information Service</a>)</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>member_id</code></td>
<td style="text-align: left;">A unique identifier for each MP’s term in parliament (may be multiple <code>member_id</code>s for each <code>person_id</code>)</td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>name</code></td>
<td style="text-align: left;">Name of the MP</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>constituency</code></td>
<td style="text-align: left;">Constituency of the MP</td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>entered_house</code></td>
<td style="text-align: left;">Date on which the MP entered the House of Commons</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>left_house</code></td>
<td style="text-align: left;">Date on which the MP left the House of Commons</td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>date_of_birth</code></td>
<td style="text-align: left;">Birthday of the MP</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>age_years</code></td>
<td style="text-align: left;">Age of the MP in years</td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>gender</code></td>
<td style="text-align: left;">Gender of the MP</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>house_start</code></td>
<td style="text-align: left;">DELETE</td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>days_in_house</code></td>
<td style="text-align: left;">Number of days that the MP had been an MP at the time of giving the speech</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>party</code></td>
<td style="text-align: left;">Party of the MP</td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>party_short</code></td>
<td style="text-align: left;">Party of the MP (recoded)</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>government_party_mp</code></td>
<td style="text-align: left;">Indicator for whether the MP was a member of a current governing party</td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>epobject_id</code></td>
<td style="text-align: left;">Unique identifier for speech</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>section_id</code></td>
<td style="text-align: left;">Debate identifier</td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>subsection_id</code></td>
<td style="text-align: left;">Sub-debate identifier</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>hpos</code></td>
<td style="text-align: left;">Position in debate of speech</td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>hdate</code></td>
<td style="text-align: left;">Date of speech</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>htime</code></td>
<td style="text-align: left;">DELETE</td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>yearmon</code></td>
<td style="text-align: left;">DELETE</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>year</code></td>
<td style="text-align: left;">DELETE</td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>parliamentary_term</code></td>
<td style="text-align: left;">DELETE</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>session</code></td>
<td style="text-align: left;">DELETE</td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>source_url</code></td>
<td style="text-align: left;">DELETE</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>colnum</code></td>
<td style="text-align: left;">DELETE</td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>body</code></td>
<td style="text-align: left;">Text of speech</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>parent</code></td>
<td style="text-align: left;">Title of debate</td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>question_time</code></td>
<td style="text-align: left;">Indicator for whether the debate is a Question Time session</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>n_words</code></td>
<td style="text-align: left;">Number of words in speech</td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>government_role_X</code></td>
<td style="text-align: left;">Whether the MP currently holds a government role (and whether the role requires attending cabinet/is paid or unpaid). MPs sometimes hold more than one role, hence the indexing.</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>attends_cabinet</code></td>
<td style="text-align: left;">Indicator for whether an MP currently holds a government role that requires them to attend cabinet</td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>government_ministerial_position_X</code></td>
<td style="text-align: left;">Name of the government role held by the MP indicated in <code>government_role_X</code>.</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>holds_government_position</code></td>
<td style="text-align: left;">Indicator for whether an MP currently holds any government role</td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>opposition_role_X</code></td>
<td style="text-align: left;">Whether the MP currently holds an opposition role (and whether the role requires attending shadow cabinet/is paid or unpaid). MPs sometimes hold more than one role, hence the indexing</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>opposition_ministerial_position_X</code></td>
<td style="text-align: left;">Name of the opposition role held by the MP indicated in <code>opposition_role_X</code>.</td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>holds_opposition_position</code></td>
<td style="text-align: left;">Indicator for whether an MP currently holds any opposition role</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>committee_name_X</code></td>
<td style="text-align: left;">Name of the committee (if any) on which the MP currently serves. MPs sometimes hold more than one committee position, hence the indexing.</td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>committee_type_X</code></td>
<td style="text-align: left;">Type of committee indicated in <code>committee_name_X</code></td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>has_committee_assignment</code></td>
<td style="text-align: left;">Indicator for whether an MP currently holds any committee assignment</td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>committee_type_assignment</code></td>
<td style="text-align: left;">DELETE</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>committee_chair_nameX</code></td>
<td style="text-align: left;">Name of the committee (if any) on which the MP is currently Chair. MPs sometimes Chair more than one committee, hence the indexing.</td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>committee_chair_type_X</code></td>
<td style="text-align: left;">Type of the committee indicated in <code>committee_chair_nameX</code></td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>is_committee_chair</code></td>
<td style="text-align: left;">Indicator for whether the MP is currently Chair of a committee</td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>committee_chair_type_assignment</code></td>
<td style="text-align: left;">DELETE</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>speaker_role</code></td>
<td style="text-align: left;">The type of speaker role held by an MP (if any)</td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>is_speaker</code></td>
<td style="text-align: left;">Indicator for whether the MP currently holds one of the Speaker or Deputy Speaker roles in the Commons</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>votes_XXX</code></td>
<td style="text-align: left;">The number of votes won by the relevant party at the last election in the relevant MP’s constituency (does not include by-election results)</td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>pct_XXX</code></td>
<td style="text-align: left;">The percentage of the vote won by the relevant party at the last election in the relevant MP’s constituency (does not include by-election results)</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>margin</code></td>
<td style="text-align: left;">DELETE</td>
</tr>
</tbody>
</table>
