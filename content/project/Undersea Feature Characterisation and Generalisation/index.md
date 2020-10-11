---
title: An Ontologies and Agents Based Approach for Undersea Feature Characterisation and Generalisation
summary: Construction of a nautical chart follows very specific rules. An undersea feature is a subjective individuation of a part of the seafloor. Landform recognition is a difficult task because its definition usually relies on a qualitative and fuzzy description. This project aims to define ontologies of the submarine relief and nautical chart. Then, the ontologies are applied to generalisation of nautical chart. In the first part of the research, an ontology is defined to organise geographical and cartographic knowledge for undersea feature representation and nautical chart generalisation. In the second part, a generalisation process based on the ontology is designed relying on a multi-agent system.
tags:
- Ontology
- Cartography
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption:
  focal_point: Smart

links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---
A nautical chart is a kind of map used to describe the seafloor morphology and the shoreline of adjacent lands. One of its main purposes is to guaranty safety of maritime navigation. As a consequence, construction of a nautical chart follows very specific rules. The cartographer has to select and highlight undersea features according to their relevance to navigation. In an automated process, the system must be able to identify and classify these features from the terrain model.

An undersea feature is a subjective individuation of a part of the seafloor. Landform recognition is a difficult task because its definition usually relies on a qualitative and fuzzy description. Achieving automatic recognition of landforms requires a formal definition of the landforms properties and their modelling. In the maritime domain, the International Hydrographic Organisation published a standard terminology of undersea feature names which formalises a set of definitions mainly for naming features and communication purpose. This terminology is here used as a starting point for the automatic classification of the features from a terrain model.

In order to integrate knowledge about the submarine relief and its representation on the chart, this research aims to define ontologies of the submarine relief and nautical chart. Then, the ontologies are applied to generalisation of nautical chart. It includes two main parts. In the first part of the research, an ontology is defined to organise geographical and cartographic knowledge for undersea feature representation and nautical chart generalisation. First, a domain ontology of the submarine relief introduces the di↵erent concepts of undersea features with their geometric and topological properties. This ontology is required for the classification of features. Second, a representation ontology is presented, which describes how bathymetric entities are portrayed on the map. Third, a generalisation process ontology defines constraints and operations in nautical chart generalisation. In the second part, a generalisation process based on the ontology is designed relying on a multi-agent system. Four kinds of agents (isobath, sounding, feature and group of features) are defined to manage cartographic objects on the chart. A database model was generated from the ontology. The bathymetric data and the ontology are stored in a triplestore database, and are connected to an interface in Java and C++ to automatically classify the undersea features extracted from the bathymetry, and evaluate the cartographic constraints. At first, geometrical properties describing the feature shape are computed from soundings and isobaths and are used for feature classification. Then, conflicts are evaluated in a MAS and generalisation plans are provided.
