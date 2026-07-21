_xpk-c_
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
Of course, XPK is a recent package manager with a practically non existent ecosystem, so the methodology and philosophy of "no trust" will mature over time, creating a more efficent method.

Requirements for merge
=====
- At least 1 maintainer reviews.

- At least 2 valid maintainer signatures.

- Packages must build reproducibly, this helps guarantee that a package was not tampered with and will also open up user repos 

- Every package manifest is deterministic, and has a few comments unless its overly simple.

(although, currently only sundowner will do maintance without further assistance)

Star history
============
## Star History
<a href="https://www.star-history.com/?repos=fischblob-lol%2Fxpk&type=date&legend=bottom-right">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=fischblob-lol/xpk-c&type=date&theme=dark&legend=bottom-right&sealed_token=JByaEYclA6Eohd-SAgoM5MR2IE8P5tkyuFdSG_6kUQuL_ZzTYGBztUvJjrvYaNNhbAblF-h1Ql3Vsu6aiehxiz3crISQrI9G1DLOelPyiCVeJgCfkUOHVyWcw0oIeAogioWJT2j9jI4u_ZChZSSgX3f3IcTQaBjFPCHGZNg0uyszYp3GNaAK6oZVA3_0" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=fischblob-lol/xpk-c&type=date&legend=bottom-right&sealed_token=JByaEYclA6Eohd-SAgoM5MR2IE8P5tkyuFdSG_6kUQuL_ZzTYGBztUvJjrvYaNNhbAblF-h1Ql3Vsu6aiehxiz3crISQrI9G1DLOelPyiCVeJgCfkUOHVyWcw0oIeAogioWJT2j9jI4u_ZChZSSgX3f3IcTQaBjFPCHGZNg0uyszYp3GNaAK6oZVA3_0" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=fischblob-lol/xpk-c&type=date&legend=bottom-right&sealed_token=JByaEYclA6Eohd-SAgoM5MR2IE8P5tkyuFdSG_6kUQuL_ZzTYGBztUvJjrvYaNNhbAblF-h1Ql3Vsu6aiehxiz3crISQrI9G1DLOelPyiCVeJgCfkUOHVyWcw0oIeAogioWJT2j9jI4u_ZChZSSgX3f3IcTQaBjFPCHGZNg0uyszYp3GNaAK6oZVA3_0" />
 </picture>
</a>

