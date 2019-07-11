A directory to store versioned mindmaps used for requirements gathering etc. You may need to download Xmind to view/explore/edit them https://www.xmind.net/

Some of the directory current content highlighted below, we try to update regularly when exploration expands.

___PROJECT: MODELING DATA FROM PERSONAL HEALTH DEVICES AND APPS___

__Background:__
A project in collaboration between https://www.regionostergotland.se/ and https://liu.se/ 

Student project report (in Swedish) http://urn.kb.se/resolve?urn=urn%3Anbn%3Ase%3Aliu%3Adiva-157977 with first prototype source code available at [...coming soon...]

The application pulls data from Google Fitness (that is available on both Android and iOS) and imports it to an openEHR platform. Currently the source code and openEHR models are updated as a summer project at Region Östergötland (using our software dev departments internal legacy versioning tools - TFS...) The updated version will be released as Open Source too, likely on GitHub again.

__Mindmaps__ (Please note that the link-symbols in the mindmaps that lead to sources, API descriptions etc)
 * [Platforms](https://github.com/regionostergotland/openehr_definitions/blob/master/mindmaps/platforms.xmind) exploration of data (mostly physical activity) gathered by different presonal health platforms (Google Fitness, Apple Health, Samsung Health, Withings, Garmin, Polar, Strava, MyFitnessPal etc.)
  * [Sleep](https://github.com/regionostergotland/openehr_definitions/blob/master/mindmaps/sleep.xmind) Data about sleep in various platforms
 * [Activities](https://github.com/regionostergotland/openehr_definitions/blob/master/mindmaps/activities.xmind) Aggregation/mashup of activity datapoints from different health platforms. Useful as background for modeling.
 * [PhysicalActivityInvestigation](https://github.com/regionostergotland/openehr_definitions/blob/master/mindmaps/PhysicalActivityInvestigation.xmind) some previous example gathering and modeling thoughts, now in part superseeded by recent archetype modeling

__Current modeling (July 2019+)__

Discussions are mostly happening in https://openehrclinical.slack.com/ in the channel #physical-activity, and the openEHR archetypes are being versioned mainly in https://github.com/regionostergotland/CKM-mirror/tree/master/local/physical_activity (and sometimes in other directories in the same repository where the tools happen to place them). If you are logged in at GitHub and go to https://ehrscape.marand.si/designerv2/#/ and just press login (as the pre-filled "test" user) at and then scroll down to the repository "Region Östergtlands fork of CKM-mirror"... then you might find the archetypes being modelled.

A snapshot of discussions with a pseudo code instance structure using clusters is available in the file [mindmaps/physical-activity-slack-discussion-1.PNG](https://raw.githubusercontent.com/regionostergotland/openehr_definitions/master/mindmaps/physical-activity-slack-discussion-1.PNG)

When a first draft is finished (Late June?) there will be a proper international review round of the archetypes and broader discussions in the community and tools at https://ckm.openehr.org/ckm/

___PROJECT: ...___
