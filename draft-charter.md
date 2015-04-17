# CBOR Object Signing and Encryption (COSE)

## Charter for Working Group

Concise Binary Object Representation (CBOR, RFC 7049) is a concise
binary format for the serialization of data structured to an extended
version of the JSON data model.  One motivation for CBOR was to make
this data model more amenable to constrained nodes and constrained
node networks (RFC 7228).

The JOSE working group recently completed producing representations
for cryptographic keys, message authentication (MACs), encryption,
and digital signatures, using JSON representation. This working group
will reuse the work done by JOSE, adapting it to the capabilities of
CBOR. This will rely on the JOSE registries, which, where this
provides additional efficiency, will be expanded with additional
information.

The resulting formats will not be cryptographically convertible from
or to JOSE formats.  This lack of a need for bit-for-bit compabitility
which will enable some simplification in the adaptation process.

Criteria that should be considered on making decisions in changing from
a JSON to a CBOR encoding are: 

- Keeping the current JOSE paradigms and formatting where feasible.

- Minimizing message size, code size and computational complexity should 
be considered (for the constrained environments where we expect to use this).

- Improving security

- Providing new functionality that uses of JOSE did not require, but are 
required for the new use cases.

Issues dealing with key management and binding of keys to identities are out 
of scope for the working group.

The Working group will coordinate its progress with the ACE, DICE and CORE
working groups to ensure that we are fulfilling the needs of these constituencies.
Other groups may be added to this list as the set of use cases is expanded.

The WG will have two deliverables:

- a standards-track specification covering the same cryptographic
formats from JOSE, with optimizations for constrained device processing, expressed in CBOR;
- registration for algorithms (such as AES-CCM-8) that are appropriate
for constrained environments.

The Working Group will use a wiki to track desired use cases for its work,
but does not intend to publish this as an RFC.

## Milestones

* WG formation date + 1 month: Submit COSE specification as a WG item

* WG formation date + 1 month: Submit COSE constrained-appropriate algorithms as a WG
  item

* WG formation date + 6 months: Submit COSE specification to the IESG, for publication as
  a Proposed Standard

* WG formation date + 6 months: Submit COSE constrained-appropriate algorithms to the
  IESG, for publication as a Proposed Standard

