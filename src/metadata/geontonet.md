---
layout: ontology_detail
id: geontonet
title: GeOnto Network
jobs:
  - id: https://travis-ci.org/BDI-UFRGS/geontonetwork
    type: travis-ci
build:
  checkout: git clone https://github.com/BDI-UFRGS/geontonetwork.git
  system: git
  path: "."
contact:
  email: 
  label: 
  github: 
description: GeOnto Network is an ontology...
domain: stuff
homepage: https://github.com/BDI-UFRGS/geontonetwork
products:
  - id: geontonet.owl
    name: "GeOnto Network main release in OWL format"
  - id: geontonet.obo
    name: "GeOnto Network additional release in OBO format"
  - id: geontonet.json
    name: "GeOnto Network additional release in OBOJSon format"
  - id: geontonet/geontonet-base.owl
    name: "GeOnto Network main release in OWL format"
  - id: geontonet/geontonet-base.obo
    name: "GeOnto Network additional release in OBO format"
  - id: geontonet/geontonet-base.json
    name: "GeOnto Network additional release in OBOJSon format"
dependencies:
- id: geocore
- id: geores
- id: geospr

tracker: https://github.com/BDI-UFRGS/geontonetwork/issues
license:
  url: http://creativecommons.org/licenses/by/3.0/
  label: CC-BY
activity_status: active
---

Enter a detailed description of your ontology here. You can use arbitrary markdown and HTML.
You can also embed images too.

