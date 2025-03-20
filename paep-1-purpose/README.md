# What is a “PAEP”?

PAEP is the acronym for a Python Australia Enhancement Proposal. This model is based on the "Enhancement Proposal" models used by the [PSF](https://github.com/python/peps/) and [DSF](https://github.com/django/deps).

A PAEP is a document or small group of artefacts in this repository intended to contain the concise, specific rationale and technical specifications for governance, standards, processes, governance and information for Python Australia.

This format is to:
* encourage transparency
* allow input and ideas to be explored
* formalise consensus gathering

Each PAEP will be designated a positive integer number in consecutive order, per the PAEP register.

## Proposed PAEP metadata

```
PAEP number: `int` (per PAEP register)
Title: short text

Team: person/people
Shepherd: person/people

Created: `date`
Resolved: `date` | None

State: `state`

Requires: `PAEP` | None
Replaces: `PAEP` | None
Superceded-by: `PAEP` | None
```

`state` is process PEAP state, see section: PEAP states.

The PAEP shepherd is responsible for building consensus within the community and documenting dissenting opinions.

## Proposed PAEP states

**Open**
* Proposed
* Draft
* In process
	* Provisional
	* Final

**Not Open**
* Active
* Rejected
* Withdrawn
* Deferred
* Replaces
* Superceded-by


Not all PAEPs will be accepted. There is no prescribed timeline for PAEP processing.
