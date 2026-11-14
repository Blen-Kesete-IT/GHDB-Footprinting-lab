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
