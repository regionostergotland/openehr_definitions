# openehr_definitions
A repository intended for local openEHR assets like operational templates and stored AQL queries.

# Tentative naming conventions for the /template directory
In the subdirectory "templates" we (currently) store templates in a flat list with disciplined file-naming using the form `templatename.versionpattern.filetype` examples follow. We choose to use the version pattern described in https://www.openehr.org/releases/AM/latest/docs/Identification/Identification.html#_version_numbering also for templates

A possible template timeline example for ADL1.4 based files
* `prostate-surgery-decision.1.2.7.oet` 
* `prostate-surgery-decision.1.2.7.opt` operational template (another file format) that can be commited either at the same time as the .oet file that it is based on or later
* `prostate-surgery-decision.1.2.8-alpha.oet` several uploads/commits to this Git repository can be done using the same alpha version file name, they are identified using GITs built in versioning instead of changing file name (comparable to "build number" in the identification spec above)   
* `prostate-surgery-decision.1.2.8-rc1.oet` 
* `prostate-surgery-decision.1.2.8.oet` 
* `prostate-surgery-decision.1.2.8.opt` 

To be determined (TBD) later: shall chosen language (e.g. sw for swedish) be included in OPT file names of ADL1.4-based files?

A possible template timeline example  for ADL2 based files
* ...TBD...

# Tentative naming conventions for the /query directory
TBD

# Archetypes
We hope to be able to only use the international CKM http://www.openehr.org/ckm/ or the Swedish incubator in that CKM for archetype work, but might later add a directory here too for possible local editing collaboration needs

# Decision support rules (CDS)
We might later add a directory here for CDS rule files too if no other collaboration space is found more suitable
