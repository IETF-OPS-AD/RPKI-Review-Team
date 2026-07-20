# Proposal for an Experimental RPKI Review Team

## Background

The Resource Public Key Infrastructure (RPKI) (RFC6480) supports Secure Inter-Domain Routing (SIDR), its primary applications being Origin Validation of BGP announcements and BGPsec. The SIDR Operations Working Group (SIDROPS WG) is responsible for the maintenance of all SIDR components except BGPsec. Specifically, SIDROPS WG is responsible for maintenance of the core RPKI specifications. In the meantime, several RPKI-related extensions leveraging the RPKI's hierarchical authorization scheme are (being) proposed in other WGs: BMWG, IDR, GROW, OPSAWG, REGEXT, SAVNET, etc. Some coordination is needed to make sure that these extensions are compliant with the core specifications maintained in SIDROPS. In addition, there also is a need to provide guidance for authors and reviewers of RPKI-related extensions to ensure consistency and leverage best design practices and operational guidance.

To that aim, a new experimental review team (TBD) is set for an initial duration of 2 years.

## Missions

* Socialize the team within relevant IETF WGs.
* Proactively identify and review RPKI-related I-Ds.
* Perform reviews upon request of WG Chairs and ADs. Early reviews (i.e., before WGLC) are recommended.
* Document guidance for authors and reviewers of RPKI-related extensions. The guidance may be published as an RFC.
* Reviews performed by the team will focus on the following aspects:
    + Ensure consistency and prevent duplicate or conflicting extensions.
    + Identify misconceptions and inadequate assumptions about RPKI in operations.
    + Provide recommendations to make the best use of the RPKI (object naming conventions, ASN.1 syntax, etc.) and leverage best design practices and operational guidance.
    + Assess the intended authorization structure, signing/validation procedures, and security mechanisms in general.
    + Assess the deployability of a proposed extension and how it integrates with RPKI ecosystem.

## (Sample) Inventory of RPKI-related I-Ds

* TBC.

## Team Members

* TBC.
