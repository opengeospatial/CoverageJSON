PART A

1. Evaluator: [CONTACT INFORMATION]

2. Submission: CoverageJSON as an OGC Community Standard (OGC 21-040r2)

Comment: 
- It is more than surprising that this public RFC takes place without prior motion nor discussion in the Coverages WG
- CoverageJSON does not support coverages, this has been stated by several experts independently in detail. The announcement is publishing a false statement.

PART B

1. Requirement: General

2. Implementation Specification Section number: All

3. Criticality: [Major, Minor, Editorial, etc.] critical

4. Comments/justifications for changes: either make it support coverages as per standard, or rename it to not continue any reference coverages

This single comment was split into 3 separate issues: PC01 #4, PC02 #5, PC03 #6

## Issue PC01 #4
Comment, 25 June 2021:

    It is more than surprising that this public RFC takes place without prior motion nor discussion in the Coverages WG

Response, 28 Jul 2021:

Standardisation of CoverageJSON was presented and agreed at the 2019 Leuven TC, and the WCS SWG offered to host the work, rather than establish a separate SWG. When the Coverages SWG was re-chartered in 2020 for the API work, the standardisation of CoverageJSON was retained in the work plan of the SWG. The current focus of the Coverages SWG is developing the API-Coverages, and correcting CIS for consistency. The SWG seemed unlikely to tackle the CoverageJSON work item for serveral months or longer. In 2021, the OGC Staff suggested a way forward  CoverageJSON as an OGC Community Standard. This was proposed and agreed at 2021-06 TC Plenary after an internal comment period.

Therefore, the Supporters reject unanimously the comment on the grounds that there has been prior motion and discussion.
 
@chris-little closed this 31 August 2021

## Issue PC02 #5
Comment 25 June 2021:

`CoverageJSON does not support coverages, this has been stated by several experts independently in detail.`

Response, 28 Jul 2021: 

1. The Supporters would like sight of the evidence. Other experts (Scott Simmons, Jon Blower, Joan Maso, etc) think it does support coverages, and have stated so in OGC forums.
    
1. CoverageJSON is a data format, not functions as defined by the ISO19123 standards, but it does support the items needed for a coverage function such as an explicit domain set, and implicit range set returned as a defined data record.

1. It is not clear that CoverageJSON is better or worse than other data formats supporting coverages, such as GeoTiff and NetCDF. That is why the Business Justification proposes a plan of work to investigate this in detail and propose CoverageJSON developments.

1. CoverageJSON can support both discrete and continuous coverages, in the sense of ISO19123 as well as features.

1. CoverageJSON was explicitly invented to support a general definition of a coverage (i.e. a function mapping from a domain to a range) in consultation with coverage experts.

1. The Supporters agreed unanimously to obtain the detailed expert statements for further consideration.

No detailed expert statements were received, but an email comment between two geospatial experts, @ogcscotts and Peter Parslow, dated 2021-08-11: `Both CoverageJSON and CIS JSON are valid implementations of the Abstract spec, but there are some differences`

### Removed: Further discussion on another topic (round-trip testing), to be carried forward for future development work, so proposed closing this specific issue next week, once people have had time to consider.

Closed as no further correspondance received.
@chris-little closed this 16 Oct 2021 

## Issue PC03 #6
Comment, 25 June 2021:

`either make it support coverages as per standard, or rename it to not continue any reference coverages`

Response, 28 Jul 2021:

CoverageJSON is a de facto community, open source, format that is being proposed as an OGC Community Standard. Renaming would serve no benefit to the user communities, and OGC Members, and the Supporters, do not have the power to rename.

There are no benefits to community users in changing, at this stage, the successful, widely used, community implementations. We are proposing that any changes be considered for future work, within the OGC. This gives the community the benefit of a focal point for future developments.

CoverageJSON is a data format, not a set of functions as defined by the ISO19123 standards, but it does support the items needed for coverage functions such as an explicit domain set, and implicit range set returned as a defined data record. CoverageJSON can support both discrete and continuous coverages, in the sense of ISO19123.

It is not clear that CoverageJSON is better or worse than other data formats supporting coverages, such as GeoTiff and NetCDF. That is why the Business Justification proposes a plan of work to investigate this in detail and propose CoverageJSON developments within the OGC standards framework.

The Supporters unanimously reject this comment on the grounds that outside of OGC, there is no power to change the specification or rename it, but this is possible within OGC.

The Supporters are responsible for their software investments and to their users. There is no intention to bypass the Coverages SWG. ... Once the CoverageJSON document is an OGC document, some Coverage SWG members have agreed to work on a detailed comparison (Discussion Paper) and this should produce some well-founded recomendations for the way forward. 

The group had agreed that your original issue above was addressed and could be closed.
@chris-little closed this 16 Oct 2021 

co
