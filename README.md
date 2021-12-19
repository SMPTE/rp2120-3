# SMPTE ST 2120-3, Extensible Time Label — Profiles

## General

This document lists the registered TLX Profiles, each specifying constraints for TLX labels, including item and attribute presence
and values.

_This repository is *public*._

Please consult [CONTRIBUTING.md](./CONTRIBUTING.md), [CONFIDENTIALITY.md](./CONFIDENTIALITY.md), [LICENSE.md](./LICENSE.md) and
[PATENTS.md](./PATENTS.md) for important notices.

Your feedback is welcome at https://github.com/SMPTE/rp2120-3/issues or at [32nf-chair](mailto:32nf-chair@smpte.org).

## Public Committee Draft (PCD) Notice

The following elements are made available for a public review period ending no earlier than {YYYY-MM-DD}, and no later than
{YYYY-MM-DD}:

* [RP 2120-3](./32NF-PCD-RP-2120-3-TLX-Profiles-2021-12-15.pdf)
* [rp-2120-3-tlx-profiles-2021.json]()

## ST 2120 Extensible Time Label (TLX) Suite Intro

The SMPTE ST 2120 Extensible Time Label (TLX) suite of engineering documents specifies a protocol for data collection and
distribution with the intended primary purpose of labeling media units with time and related data.

A TLX label comprises one or more unordered TLX “Items”. Each TLX item is an unordered collection of name-value pairs, representing
“Attributes”, which represent the associated metadata for a particular parameter. The extensible design allows that any new TLX item
or attribute can be defined. TLX implementations are encouraged to preserve TLX items and attributes that are not recognized, to
better support downstream processes might make use of such items and attributes.

TLX can provide a label for every media unit, and each label can be globally unique. The design of TLX overcomes the limitations
most commonly encountered when using SMPTE ST 12 timecode.
