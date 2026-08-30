<!-- regenerate: off -->

# Composing Application-Layer Action Evidence with Remote Attestation Procedures

This is the working area for the individual Internet-Draft, "Composing Application-Layer Action Evidence with Remote Attestation Procedures".

* [Editor's Copy](https://tyche-institute.github.io/draft-sokolov-rats-aep-composition/#go.draft-sokolov-rats-aep-composition.html)
* [Datatracker Page](https://datatracker.ietf.org/doc/draft-sokolov-rats-aep-composition)
* [Individual Draft](https://datatracker.ietf.org/doc/html/draft-sokolov-rats-aep-composition)
* [Compare Editor's Copy to Individual Draft](https://tyche-institute.github.io/draft-sokolov-rats-aep-composition/#go.draft-sokolov-rats-aep-composition.diff)


## Contributing

See the
[guidelines for contributions](https://github.com/tyche-institute/draft-sokolov-rats-aep-composition/blob/main/CONTRIBUTING.md).

The contributing file also has tips on how to make contributions, if you
don't already know how to do that.

## Command Line Usage

Formatted text and HTML versions of the draft can be built using `make`.

```sh
$ make
```

Command line usage requires that you have the necessary software installed.  See
[the instructions](https://github.com/martinthomson/i-d-template/blob/main/doc/SETUP.md).

## Current editor baseline

The `main` branch incorporates the changes prepared for revision `-06`
(30 August 2026). Relative to `-05`, it:

- distinguishes an AEP Record carried as `application/vnd.aep+zip` from an EAT
  carrying the AEP Evidence Claims-Set under an RFC 9782 EAT media type;
- describes the experiment's record-specific PCR Reference Value as a bounded
  test constraint and gives the pre-AEP state plus event-log replay deployment
  pattern; and
- requires `eat_nonce` comparison for a future complete profile that claims
  same-window freshness.

Section 16 is unchanged from `-05`. The broader chain-anchoring proposal is not
folded wholesale into this baseline; focused pull requests against
[`draft-sokolov-rats-aep-composition.xml`](draft-sokolov-rats-aep-composition.xml)
are welcome.
