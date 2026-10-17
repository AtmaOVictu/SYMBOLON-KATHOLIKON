# The absolute test — three utterances, three verdicts

## Why absolute

The judging path contains no model: only comparison against sealed, verbatim citations. Same bytes in — same verdict out, for anyone, every run, offline. A test of a model can never be absolute (models drift, Δ>0); a test of the scale can be.

The test is falsifiable by design: if any of the three known cases below returns a wrong verdict, the scale is broken — and anyone can demonstrate it. A test that cannot fail is decoration.

## The calibration triangle

1. **⊢ — known-true.** Claim: `lúknja je odprtina`. Sealed entry: SSKJ², lúknja = odprtina, verbatim. Must pass.
2. **× — known-false.** Claim: `lúka je odprtina`. Sealed entry: SSKJ², lúka = pristanišče (harbor), verbatim. Must fall. This is the recorded seed fall of the regime — the mark was applied before the entry, caught in its own seed, named, corrected with the scar kept.
3. **⚠ — known-open.** A claim with no entry. Must stay marked, never hidden. The mark is the honesty; the silence is the failure.

## How to run it yourself (offline, no account)

1. Download the [verification-before-assertion](https://github.com/AtmaOVictu/verification-before-assertion) repository as a ZIP — or carry it on a USB stick.
2. Run `python test_vba.py` — the triangle runs inside the test suite, zero dependencies; CI runs it on every push.
3. Check any ⊢ yourself at the source (fran.si for the Slovenian entries): the citation is verbatim, or the entry falls.

## Independence

Swap in your own dictionary ([PREDLOGA.md](PREDLOGA.md)) and the verdicts become yours: the scale weighs whatever you put on it — no hidden dependence on our data.

Bring your own dictionary. Run it offline. Keep the verdict.

## The honest limit

The generation layer — a model producing definitions cold — is not bit-reproducible; it is sealed evidence (protocol and outputs archived). The absolute test judges the judge, not the generator. The scale does not weigh itself: the life of this seat is measured by the return of a third hand.
