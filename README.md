This repository has 2 * .csv files and 1 * .xlsx file.

**finalca.csv** is list of companies that had class action cased based on the criteria of the paper.

  ['companyid', 'transcriptid', 'mostimportantdateutc',
       'mostimportanttimeutc', 'keydeveventtypename', 'companyname',
       'transcriptcollectiontypename', 'transcriptpresentationtypename',
       'transcriptcreationdate_utc', 'audiolengthsec', 'isdelayed_flag',
       'transcriptcomponenttypename', 'transcriptpersonid',
       'transcriptpersonname', 'speakertypename', 'componenttextpreview',
       'word_count', 'componenttext', 'decile_at', 'classaction',
       'sic_firstdigit', 'filingname', 'filingdate'],

**finalnonca.csv** is list of companies that DID NOT have class action based on the criteria of the paper.

  ['companyid', 'transcriptid', 'mostimportantdateutc',
       'mostimportanttimeutc', 'keydeveventtypename', 'companyname',
       'transcriptcollectiontypename', 'transcriptpresentationtypename',
       'transcriptcreationdate_utc', 'audiolengthsec', 'isdelayed_flag',
       'transcriptcomponenttypename', 'transcriptpersonid',
       'transcriptpersonname', 'speakertypename', 'componenttextpreview',
       'word_count', 'componenttext', 'decile_at', 'classaction',
       'sic_firstdigit', 'filingname', 'filingdate'],

**Both sets combined to make a master list, they have equal distribution**

**ap.xlsx** has two sheets that encapsulate the 'Fundamentals' and 'Analysts' attributes of the companyies.
