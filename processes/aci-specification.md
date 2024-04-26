# ACI Specification

## Applicability

This document applies to the ACI Specification <https://github.com/ACI-Specification.git>

## Non-destructive Actions

The following Non-destructive Actions may be performed with respect to the ACI Specification by the Maintenance Team:
* Making or Merging a change to any Well-known subclass specification,
* Reverting such a change.


## Reversible Actions

Reversible Actions may be Performed by the Maintenance Team after a Review and Comment period of at least 7 days. 

The following actions are deemed reversible:
* Merging a change to any draft version of the hardware interface specification not subject to any freeze,
* Merging a permitted change to any draft version of the hardware interface specification subject to a freeze,
* Merging a change to the software interface specification

Beginning the Review and Comment Period for an action listed above, and taking the action once it has completed, may be performed by any Member of the Maintenance Team.

## Freezes

Draft Versions of the ACI Hardware Interface Specification may be subjected to various types of Freezes against certain types of Proposals. 

The following actions to make changes to an Unpublished Version, and extensions/technical documents in an Unpublished Version, may be taken following a Review and Comment Period of at least 28 days, followed by a Balloting Period of at least 14 days:
* Initiating a Freeze on a Draft Version,
* Merging a Proposed Change to a Draft Version that is not deemed a Permitted Change.

### Feature Freezes

Feature Freezes may be put into effect on an unpublished Version of the ACI Hardware Interface Specification which is subject to an Encoding Freeze.

Feature Freezes further restrict changes to an version being prepared, to allow the version to be implemented, and implementations to be tested. 
No changes are permitted to any extension or technical document subject to a Feature Freeze, except to fix a major bug in the specification.

## Stabilization of a Version

A draft version of the hardware interface specification subject to a Feature Freeze may be stabilized and published by the Maintenance Team, following Review and Comment period of at least 50 days, and a Balloting period of at least 30 days with a threshold of 60%. Once a version is stabilized, no changes may be made to the extensions or the version of any technical document published, except for issuing a Defect Report to fix a Major Bug.

Stabilization of a version also affects new Extensions and Technical Documents, as well as new versions of published Technical Documents. Such changes, regardless of version or applicable freezes, are subject to the Stability Policy as documented in the Specification.

Stabilization of a Version is irreversible by design. There is no process to reverse publication of a version.

## Defect Reports

A Defect Report may be filed against a published version to fix a Major Bug by the Maintenance Team. Approval of a Defect Report shall be subject to a Review and Comment period of at least 50 days, and a Balloting period of at least 30 days. 

## Major Bugs

Certain types of issues are deemed Major Bugs in the specification, these are:
* Defects in the specification, that prevent implementation of that specification or make it unreasonably difficult to do so, 
* Defects that present substantial security issues to implementations or software,
* Holes in the specification, where a given operation is not prescribed any explicit behaviour by the specification,
* Unclear wording, where multiple conflicting interperations of the specification reasonably exist or could reasonably exist.



