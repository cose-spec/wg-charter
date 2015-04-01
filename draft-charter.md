# CBOR Object Signing and Encryption (COSE)

## Charter for Working Group

Concise Binary Object Representation (CBOR, RFC 7049) is a concise
binary format for the serialization of data structured to an extended
version of the JSON data model.  One motivation for CBOR was to make
this data model more amenable to constrained nodes and constrained
node networks (RFC 7228).

The JOSE working group recently completed producing representations
for message authentication (MACs), encryption, and digital signatures,
using JSON representation.  This working group will reuse the work
done by JOSE, adapting it to the capabilities of CBOR.  This will rely
on the JOSE registries, which, where this provides additional
efficiency, will be expanded with additional information.

The resulting formats will not be cryptographically convertible from
or to JOSE formats.  This lack of a need for bit-for-bit compabitility
which will enable some simplification in the adaptation process.

The deliverable of the WG is a single Standards-Track specification
covering all of the functions achieved by JOSE, CBOR Object Signing
and Encryption (COSE).  In addition, a number of algorithms will be
registered that are appropriate for constrained environments (such as
AES-CCM-8).

## Milestones

* March 2015: Submit COSE specification as a WG item

* April 2015: Submit COSE constrained-appropriate algorithms as a WG
  item

* June 2015: Submit COSE specification to the IESG, for publication as
  a Proposed Standard

* July 2015: Submit COSE constrained-appropriate algorithms to the
  IESG, for publication as a Proposed Standard

