# Alma
Possible place to run an Alma API from although I'm not sure I can do that from Github.

I have a list of Alma MMSIDs for which I'd like to retrieve their full MARC or MARCXML records using the GET/almaws/v1/bibs API (https://developers.exlibrisgroup.com/alma/apis/bibs/GET/gwPcGly021q2Z+qBbnVJzw==/af2fb69d-64f4-42bc-bb05-d8a0ae56936e).

Background: As DWL's policy is to offer a thesis mainly in electronic version, we need to suppress their bib records from discovery. Most of our thesis are still unsuppressed i.e. their print version can be requested from retrieval. Although there's a minority of theses with an embargo (full or partial), RobM requested a list of unsuppressed items. In order to identify those that should remain discoverable. Ideally, that list should include the associated award; this is entered in MARC21 field 509 with is neither indexed nor available in Alma Analytics. As Ex Libris offer an API to retrieve bib data, it might be easiest to get to the values in 509 through this.
