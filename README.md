xpk-c
====

The official core repository for xpk.

Packages in this repository considered the highest trust packages in the ecosystem.
Before a package may be added or updated, every active xpk maintainer must
- review the change 
- sign the commit using a verified cryptographic key

If a maintainer's key has expired or been revoked, that maintainer is no longer
considered an active signer. The remaining active maintainers must still
unanimously sign the commit.

Why?
====

This policy ensures that no single maintainer can unilaterally introduce
changes into the highest trust repository. Every change requires unanimous
approval from all currently trusted maintainers, providing strong protection
against compromised accounts, malicious maintainers, and accidental mistakes.

As the maintainer set changes over time, the required signatures adapt
automatically by considering only currently valid, trusted signing keys.

Caveats
=====
of course, xpk is a recent package manager with a practically non existent ecosystem, so the methodology and philosophy of "no trust" will mature over time, creating a more efficent method



Requirements for merge
=====
- At least 1 maintainer reviews.
- At least 2 valid maintainer signatures.
- Packages must build reproducibly.
- CI must pass.
- Every package manifest is deterministic, and has a few comments unless its overly simple.