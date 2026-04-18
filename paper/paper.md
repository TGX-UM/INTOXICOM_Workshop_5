---
title: 'INTOXICOM Workshop Report: Systems Biology Models for Toxicology'
title_short: 'INTOXIOM #5: Systems Biology Models for Toxicology'
tags:
  - toxicology
  - systems biology
  - model
authors:
  - name: Chris Evelo
    affiliation: 1
  - name: Rob Stierum
    affiliation: 2
  - name: Meike Bünger
    affiliation: 3
  - name: Marvin Martens
    affiliation: 1
  - name: Ellen Hessel
    affiliation: 4
  - name: Karine Audouze
    affiliation: 5
affiliations:
  - name: Department of Translational Genomics, NUTRIM, FHML, Maastricht University, Maastricht, NL
    index: 1
  - name: The Netherlands Organisation for Applied Scientific Research (TNO), Utrecht, NL
    index: 2
  - name: Health-RI / ELIXIR-NL, Utrecht, NL
    index: 3
  - name: RIVM, Bilthoven, NL
    index: 4
  - name: Université Paris Cité, INSERM 1124, Paris, FR 
    index: 5
date: 18 April 2026
cito-bibliography: paper.bib
event: INTOXICOM
biohackathon_name: "INTOXICOM Workshops"
biohackathon_url:   "https://elixir-europe.org/internal-projects/commissioned-services/integrating-toxicology-community"
biohackathon_location: "Athens, Greece, 2025"
group: Workshop 5
git_url: https://github.com/TGX-UM/INTOXICOM_Workshop_5
authors_short: Evelo \emph{et al.}
---

# Abstract

This report summarizes the ELIXIR Toxicology Community workshop on Systems Biology Models for Toxicology, held on 11–12 September 2025 in Athens, Greece. The workshop took place under the INTOXICOM Implementation Study workshop series (Integrating the toxicology community into ELIXIR 2024) and aimed to strengthen connections between systems biology and toxicology by bridging ELIXIR resources with systems toxicology modelling approaches used for chemical risk assessment. The workshop explored the role of qualitative and quantitative exposure–health outcome models, including (quantitative) Adverse Outcome Pathways ((q)-AOPs), AOP networks, and mechanistic toxicology models. Participants examined two use cases focused on neurotoxicity and endocrine disruption, discussing how ELIXIR tools, platforms, core data resources, and modelling environments can support them. The workshop concluded with a discussion on a roadmap for integrating ELIXIR systems biology infrastructures and tools into applied systems toxicology. This report documents the presentations, discussions, and practical results that contribute to Deliverables of INTOXICOM WP5.

# Introduction

As part of the ELIXIR Toxicology Community’s ongoing efforts to support modern, data-driven toxicology (https://elixir-europe.org/communities/toxicology), the INTOXICOM Implementation Study organized a workshop on Systems Biology Models for Toxicology. The workshop took place in Athens, Greece on 11–12 September 2025 and was preceded by a preparatory webinar.

The workshop addressed a central challenge in contemporary toxicology: how to integrate mechanistic systems biology models, multi-scale data resources, and computational tools into chemical risk assessment. Although toxicology has used mechanistic and predictive modelling approaches since the 1980s (e.g. PBPK and toxicodynamic models), the field has not yet fully leveraged the modern systems biology ecosystem available within ELIXIR Nodes.

The workshop brought together toxicologists, computational modelers, system biologists, and FAIR-oriented bioinformaticians, with the primary goals of:

* Mapping existing ELIXIR tools, services, platforms, and core data resources with potential relevance for toxicology
* Identifying systems toxicology models developed by the toxicology community that would benefit from exposure via ELIXIR infrastructures (e.g. bio.tools)
* Exploring how systems biology approaches can support qualitative and quantitative AOP development, including AOP networks
* Developing use case–driven workflows to support hazard identification and hazard potency ranking
* Constructing a roadmap for continued integration of ELIXIR infrastructure into applied systems toxicology for risk assessment

Organiser:
* Karine Audouze (FR)
* Rob Stierum (NL)

With support from:
* Marcin W. Wojewodzic (NO)
* Joost Beltman (NL)
* Chris Evelo (NL)
* ELIXIR Europe

Invited speakers :
* Holly Mortenson, US Environmental Protection Agency (EPA) & Duke University
* Ellen Hessel, RIVM, NL
* Maria Klapa, Foundation for Research & Technology - Hellas, GR
* Marvin Martens, Maastricht University

The workshop specifically targeted toxicologists with an affinity for:
* systems biology modelling
* bioinformatics
* (q)-AOP and AOP network development
* computational toxicology

# The Workshop

## Workshop Themes and Background

A modern chemical risk assessment framework requires robust and mechanistically grounded models linking chemical exposure to adverse health outcomes. Current approaches include:
* Adverse Outcome Pathways (AOPs), that is a conceptual pathway linking molecular initiating events (MIEs) to key events (KEs) that lead to adverse outcomes (AOs).
* AOP Network (AOPN), reflecting biological reality where:
    * a single stressor can lead to multiple possible outcomes
    * multiple stressors can converge on the same adverse outcome
    * toxicological responses are modulated by context, thresholds, and feedback loops
* Systems toxicology approaches that involved multi-level toxicogenomics, dynamic modelling frameworks, text mining and automatic knowledge extraction, network-based toxicology, as well as PBPK and mechanistic modelling integration.

Yet, many of these approaches still operate outside the modern systems biology tooling available within ELIXIR.

## Workshop Objectives

The workshop aimed to:
1. Identify ELIXIR systems biology tools, services, and platforms that can support toxicological modelling workflows.
2. Connect systems toxicology models with ELIXIR infrastructures, e.g. inclusion in bio.tools and connection to data standards and core data resources
3. Present two concrete use cases demonstrating how ELIXIR resources can support them.
4. Initiate a roadmap to integrate ELIXIR systems biology capabilities into toxicology.
5. Prepare for a workshop report submission to BioHackrXiv.

## Acknowledgements

...

## Funding

This workshop was funded by the ELIXIR Europe INTOXICOM grant (Grant No. NL-2023-INTOXICOM).

## References
