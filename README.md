# OGC CoverageJSON

This GitHub repository contains documents to produce an OGC Community Standard for CoverageJSON.

A daily build of the candidate Community Standard is available [here](https://opengeospatial.github.io/ogcna-auto-review/21-069.html).

CoverageJSON has a [JSON Schema](https://covjson.org/schema/dev/coveragejson.json) which can be used in the CoverageJSON [Community Playground/Sandbox](https://covjson.org/playground/)
The starting point for the standard was the [work by Jon Blower and Maik Riechert of Reading University](https://covjson.org/), under the auspices of the EU Framework 7 MELODIES project in 2015, and other usage by NASA, NCAR and others.

As there had been little development, though plenty of use, of CoverageJSON since the end of the EU project, and there was no clear governance framework, some key supporters of the format agreed to ask OGC to adopt CoverageJSON, unchanged, as an OGC Community Standard.

After any adoption, it is proposed that the commonalities and differences with other OGC coverage payload formats, such as CIS-JSON, GeoTiff and NetCDF, be investigated with view to producing a developmental roadmap for CoverageJSON, to be pursued within the OGC governance framework.

The Business Justification for this plan finished a formal Public Comment period on 25 July 2021 and responses to the received comments were processed at an OGC GoToMeeting session on 28 July 2021. All were agreed to be closed apart from one, which needed more information for a considered meaningful response. Further information was requested from the original commentator.

After more information, the supporters formally processed all the public comments, which were raised as labelled Issues on this repo, and all eventually closed. The Business Justification was presented to the OGC Technical Committee on 20 September 2021, which, with no objections to unanimous consent, agreed to formally vote on commencing the work. The electronic vote commenced on 28 September 2021 and finished on the 12 November 2021.

The OGC Technical Committee vote was 20 YES votes, 14 ABSTAIN and 5 NO votes, and quorum was readily achieved. So the work proceeded, under the auspices of the Coverages Standards Working Group. The various comments from the votes have been published, addressed and closed, in this repo as labelled Issues.

At the December 2021 meeting of the OGC Technical Committee, the following plan was agreed and progress as of June 2022 is shown:

### Objectives
* Publish existing community specification (V0.2) as OGC Community Standard in March 2022
* Convergence with ISO 19123-1 and ISO19123-2 CIS would be a goal
* Continued community support and performance would also be a goal, for the use case of download useful data to a browser

### Tasks
* Respond to vote comments (**DONE**)
* Adopt OGC Standards Document structure for Specification (**DONE**) see [OGC21-069 in Pending folder](https://portal.ogc.org/files/?artifact_id=99371&version=1)
* Minor, informative improvements to specification as originally specified at https://covjson.org/ : 
    * Add text to explain relation to ISO standards (**DONE**)
    * Add some top level, Dublin Core-like, metadata (**NOT DONE** - use Extension mechanism)
    * Produce a full JSON Schema (**DONE**, see [public repo](https://github.com/covjson/covjson-validator) )
    * Tighten specification of support for WKT for CRSs (**DONE**)
    * Alt-Range is not well understood or used, consider removal (**DONE**)
* Adopt CoverageJSON as OGC Community Standard (Target 2022-03, revised June 2022, passed OAB Review July, addressed comments from final public RFC, passed Technical Committee approval vote 25 Nov 2022 (27 YES, 10 Abstain, 0 No). Awaiting Planning Committee approval.
* Produce detailed CoverageJSON, CIS JSON, GeoTIFF, and CF-NetCDF3 comparison document via WCS SWG
    * Keen volunteers identified! 
    * Text in GitHub (**DONE**)
    * Create Conceptual model (Top level model diagram incorporated into candidate Sep 2022)
* Request and propose further improvements to CoverageJSON specification:
    * Support for multiple time axes (Tagged V1.1)
    * Support for JSON representation of CRSs, as in PROJJSON (Tagged V1.2)
    * Other backward compatible improvements (V1.x)
    * Support for JSON-LD V1.1 to allow links from deeply nested objects (not clear if backward compatible)
    * Support binary nD arrays of data (probably not needed because gZip very effective)	
    * Identify and plan V2.x

## Status

See the [Wiki](https://github.com/opengeospatial/CoverageJSON/wiki) for details of progress, minutes of meetings, etc, and [Issues](https://github.com/opengeospatial/CoverageJSON/issues).

The specification was reviewed by the OGC Architecture Board and approved for release for Public Comment after some minor editorial changes. The only Public Comments were largely editorial and were incorporated. Now submitted to the OGC Technical Committee for approval as an OGC Community Standard.

The specification is backwards compatible with the original specification, but with some little-used sections removed, some vague sections clarified, and a complete JSON schema added and made available through the [Playground/Sandbox](https://covjson.org/playground). A [more detailed overview](https://github.com/opengeospatial/CoverageJSON/wiki/Change-List-OGC-V1.0.0) of the changes is also available. 

Any contributor to this repo should understand that any contributions, if accepted by the OGC Membership, shall be incorporated into OGC standards documents and that all copyright and intellectual property shall be vested in the University of Reading.
