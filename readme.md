[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6257660.svg)](https://doi.org/10.5281/zenodo.6257660)

# European Registry of Materials

The European Registry of Materials is a simple registry with the sole purpose to mint material
identifiers to be used by research projects throughout the life cycle of their project
([fairsharing.org entry](https://fairsharing.org/bsg-s001384/)). The
identifier is nothing more than that identifier, and not by default linked to any information.
Think of it as a pre-registration of the intention to study the material.

Once the identifier is created by a research project, the idea is that it is used throughout the
whole study, from the design to the final reporting. It is meant to be used as unique, persistant
identifier to be used in descriptions of experimental designs, in (open) notebooks, in reports,
in project milestones and deliverables, and in journal articles.

More information and use cases can be found in this
[preprint](https://chemrxiv.org/engage/chemrxiv/article-details/60e6e05a338e92a5cd08ff69).

## The identifier

The identifier can be used in two ways. For regular writing, it can be used as in its compact
form. For semantic web approaches, the full IRI can be used. Both will be considered equivalent
and refer to the same identifier. The identifier is described by the CHEMINF ontology term 
CHEMINF_000569 and part of the eNanoMapper ontology (version 6).

## The associated information

To encourage wide adoption, the information that the registry will provide is kept to a minimum.
This registry is not a database.

### Required information

The only required information to provide during a registry is a name or label. This label can be
anything. It can be a anonymized label, a descriptive label, or a more rich description.
Importantly, the label itself has no meaning. Moreover, the label does not have to be unique.

### Optional information

The following bits of information are welcome but not required (in random order):

* parent ERM identifier (identifier of the material that this material was derived from): identifier or IRI or Compact identifier
* unique chemical composition
* batch and/or lot number
* an ontological classification (could be suggested based on the chemical composition?)
* a webpage
* a provider, contact, or project name

Keep in mind that provided data is provided to the registry under the [CCZero license](license.md).

## Providing data

[This document](register.md) explains how to register new materials.


## Acknowledgement

This registry is supported by [NanoCommons](https://www.nanocommons.eu/).
NanoCommons has received funding from European Union
Horizon 2020 Programme (H2020) under grant agreement nº [731032](https://cordis.europa.eu/project/rcn/212586/en).

![](https://licensebuttons.net/p/zero/1.0/88x31.png)
