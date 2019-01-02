# bebanjo-tasks
**Movida // YouView Metadata Exporter // Summary of New Client Requirements**

**Purpose:** This repo contains issues created for the (hypothetical) expansion of the Movida YouView Metadata Exporter for Len's interview with BeBanjo. The purpose of these issues is to summarize the client's requirements for the dev team and denote which new features need to be implemented in order to satisfy client requirements.

**Summary:** The client is launching a new service that showcases foreign language TV content (e.g. episodic Scandinavian crime drama) and requires additional metadata to be stored in Movida and then published to YouView for this content. The content will be presented in its original language with subtitles (none of their existing content is subtitled). These features are not supported in the current implementation of our YouView Metadata Exporter. Below, please see the features we'll need to implement per client requirements.

**New Features**
1. Audio Track Language- spec doc 6.7 (Production Language)
    1. Store in Movida.
    1. Publish to YouView.
        1. Will display on Action Panel in Details tab
        1. Will display on Brand and Series roll-up pages in synopsis.
1. Subtitle Details - spec doc 8.2 (Accessibility/Subtitles)
    1. Store in Movida.
    1. Publish to YouView.
        1. Will display on Action Panel - Summary and Details tabs
1. Where the content was produced - spec doc 6.9 (Production Location)
    1. Store in Movida.
    1. Publish to YouView.
        1. Not displayed in UI.
    
*Note: Proper XML format/structure for each new feature will be noted in its respective issue and reference made to the spec doc provided by YouView.

Please contact Len Forgione with any questions or requests for clarification: @lenforge or lenforgione@gmail.com.
