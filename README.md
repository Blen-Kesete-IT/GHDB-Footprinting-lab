# GHDB Footprinting Lab

This Week 2 project documents how search engines can index camera web interfaces and what defenders can learn from those results.

## Lab Overview

| Component | Configuration |
|---|---|
| Module | Week 2, Project Module 2 |
| Reference | Google Hacking Database (GHDB) |
| Evidence | Assignment worksheet and screenshots |
| Scope | Review of supplied evidence |

## Objectives

- Identify what a search index can reveal about a web interface.
- Record visible evidence and distinguish it from assumptions about access.
- Explain how administrators can reduce unintended exposure.

## Result Validation

The worksheet contains ten references. The supplied webcamXP 5 screenshot shows a multi-view page displaying several camera images while the interface reports a signed-out session. The evidence establishes what was visible at capture time. The authentication configuration and current availability remain unverified.

## What I Learned

A search result shows what a search engine indexed. A screenshot records what the interface displayed at a specific time. Administrators can use access controls to protect restricted views and review search visibility on domains they manage.

## Evidence

| Artifact | Observation |
|---|---|
| Findings worksheet | Ten references were recorded |
| GHDB screenshot | Shows an entry about indexed camera interfaces |
| Webcam interface screenshot | Shows several images in multi-view while signed out |
| User-supplied Insecam listing | The page could not be retrieved for review. Its contents, live status, and relationship to the webcamXP screenshot are unverified. |

### Screenshot evidence

**GHDB entry metadata**

![Cropped GHDB entry showing its ID, author, and publication date](evidence/ghdb-entry.jpg)

**webcamXP multi-view interface**

![Cropped webcamXP interface showing the navigation and signed-out status](evidence/webcam-interface.jpg)

## Skills Demonstrated

- Interpreting search-index evidence
- Documenting observations and verification limits
- Summarizing unintended exposure for a defensive review

## Course Credit

Thanks to NetworkWalks for the lab guidance.


## Footprinting findings: 10 student-observed camera listings

**Method:** The student reported opening ten Insecam listing links and observing camera feeds during the lab. This is a record of student-reported observations, not independent live verification. The listing IDs below are not camera IP addresses. The listing URLs below were supplied for this assignment; they are clickable references to listing pages, not validated device IP addresses. Credentials, precise locations, and identifying footage are not included.

| No. | Listing reference | Finding | Credentials | Feed screenshot |
|---|---|---|---|---|
| 1 | [Insecam listing 1012712](http://www.insecam.org/en/view/1012712/) | Student reported viewing feed; not independently verified | Not supplied | Not supplied |
| 2 | [Insecam listing 1012784](http://www.insecam.org/en/view/1012784/) | Student reported viewing feed; not independently verified | Not supplied | Not supplied |
| 3 | [Insecam listing 1012770](http://www.insecam.org/en/view/1012770/) | Student reported viewing feed; not independently verified | Not supplied | Not supplied |
| 4 | [Insecam listing 1012776](http://www.insecam.org/en/view/1012776/) | Student reported viewing feed; not independently verified | Not supplied | Not supplied |
| 5 | [Insecam listing 1012769](http://www.insecam.org/en/view/1012769/) | Student reported viewing feed; not independently verified | Not supplied | Not supplied |
| 6 | [Insecam listing 1012766](http://www.insecam.org/en/view/1012766/) | Student reported viewing feed; not independently verified | Not supplied | Not supplied |
| 7 | [Insecam listing 1012760](http://www.insecam.org/en/view/1012760/) | Student reported viewing feed; not independently verified | Not supplied | Not supplied |
| 8 | [Insecam listing 1012752](http://www.insecam.org/en/view/1012752/) | Student reported viewing feed; not independently verified | Not supplied | Not supplied |
| 9 | [Insecam listing 1012735](http://www.insecam.org/en/view/1012735/) | Student reported viewing feed; not independently verified | Not supplied | Not supplied |
| 10 | [Insecam listing 1012730](http://www.insecam.org/en/view/1012730/) | Student reported viewing feed; not independently verified | Not supplied | Not supplied |

**Search query discussed in the lab:** `site:insecam.org/en/view/ "IP camera"`. This is a general query, not a verified official GHDB entry or proof it located each camera. GHDB reference: https://www.exploit-db.com/google-hacking-database.

### Evidence and screenshot status

The [GHDB screenshot](evidence/ghdb-entry.jpg) and [webcam screenshot](evidence/webcam-interface.jpg) document earlier lab observations, not all ten camera listings. Individual feed screenshots have not been provided. Any publicly shared evidence should be redacted to protect privacy.

### Findings and interpretation

- **Finding:** Ten camera listing references were recorded and the student reports that feeds were visible when visited.
- **Exposure risk:** Publicly viewable cameras can disclose sensitive scenes, operational context or personal information.
- **Verification limit:** Current accessibility, device addresses, authorization, authentication configuration and vulnerability status were not validated.
- **Defensive recommendation:** Camera owners should require authentication, restrict network exposure, disable unnecessary public streaming and review search indexing of interfaces they control.
