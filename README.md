# Stake DAO Security Audits

## 📋 Overview

This repository serves as a centralized, transparent archive of all security audits performed on Stake DAO's ecosystem. All audit reports are organized by product and follow a consistent naming convention for easy reference.

## 🛡️ Audit Reports

### Staking v2 (Only Boost v2)

| Auditor                                           | Date           | Report                                                                                                          |
| ------------------------------------------------- | -------------- | --------------------------------------------------------------------------------------------------------------- |
| [Omniscia](https://omniscia.io/)                  | May 2025       | [`2025-05-01_omniscia_staking_v2.pdf`](staking-v2/2025-05-01_omniscia_staking_v2.pdf)                           |
| [Trust Security](https://www.trust-security.xyz/) | April 2025     | [`2025-04-01_trust_security_staking_v2.pdf`](staking-v2/2025-04-01_trust_security_staking_v2.pdf)               |
| [Pashov Audit Group](https://www.pashov.net/)     | August 2025    | [`2025-08-08_pashov_staking_v2_morpho_support.pdf`](staking-v2/2025-08-08_pashov_staking_v2_morpho_support.pdf) |
| [Omniscia](https://omniscia.io/)                  | September 2025 | [`2025-09-03_omniscia_staking_v2.pdf`](staking-v2/2025-09-03_omniscia_staking_v2.pdf)                           |

### OnlyBoost

| Auditor                                           | Date          | Report                                                                                               |
| ------------------------------------------------- | ------------- | ---------------------------------------------------------------------------------------------------- |
| [Trust Security](https://www.trust-security.xyz/) | February 2024 | [`2024-02-15_trust_security_onlyboost_v2.pdf`](onlyboost/2024-02-15_trust_security_onlyboost_v2.pdf) |
| [Trust Security](https://www.trust-security.xyz/) | February 2024 | [`2024-02-01_trust_security_onlyboost_v1.pdf`](onlyboost/2024-02-01_trust_security_onlyboost_v1.pdf) |
| [Zach Obront](https://github.com/zobront)         | November 2023 | [`2023-11-22_zachobront_onlyboost.md`](onlyboost/2023-11-22_zachobront_onlyboost.md)                 |

### Votemarket

#### V2

| Auditor                                           | Date           | Report                                                                                                     |
| ------------------------------------------------- | -------------- | ---------------------------------------------------------------------------------------------------------- |
| [Pashov Audit Group](https://www.pashov.net/)     | October 2024   | [`2024-10-01_pashov_laposte.pdf`](votemarket/v2/laposte/2024-10-01_pashov_laposte.pdf)                     |
| [Trust Security](https://www.trust-security.xyz/) | September 2024 | [`2024-09-01_trust_security_votemarket_v2.pdf`](votemarket/v2/2024-09-01_trust_security_votemarket_v2.pdf) |

#### V1

| Auditor                                     | Date         | Report                                                                                                   |
| ------------------------------------------- | ------------ | -------------------------------------------------------------------------------------------------------- |
| [ChainSecurity](https://chainsecurity.com/) | January 2023 | [`2023-01-01_chainsecurity_votemarket_v1.pdf`](votemarket/v1/2023-01-01_chainsecurity_votemarket_v1.pdf) |

### vlSDT

| Auditor                                           | Date       | Report                                                                                   |
| ------------------------------------------------- | ---------- | ---------------------------------------------------------------------------------------- |
| [Trust Security](https://www.trust-security.xyz/) | March 2026 | [`2026_03_26_trust_security_vlsdt.pdf`](vlsdt/2026_03_26_trust_security_vlsdt.pdf)       |

### Miscellaneous

| Auditor                                           | Date          | Report                                                                                                      | Product            |
| ------------------------------------------------- | ------------- | ----------------------------------------------------------------------------------------------------------- | ------------------ |
| [ChainSecurity](https://chainsecurity.com/)       | October 2022  | [`2022-10-01_chainsecurity_liquid_lockers.pdf`](misc/2022-10-01_chainsecurity_liquid_lockers.pdf)           | Liquid Lockers     |
| [ChainSecurity](https://chainsecurity.com/)       | February 2022 | [`2022-02-01_chainsecurity_vesdt_fxs_locker.pdf`](misc/2022-02-01_chainsecurity_vesdt_fxs_locker.pdf)       | veSDT & FXS Locker |
| [Omniscia](https://omniscia.io/)                  | March 2025    | [`2025-03-11_omniscia_zerolend_liquid_locker.pdf`](misc/2025-03-11_omniscia_zerolend_liquid_locker.pdf)     | Liquid Lockers     |
| [Trust Security](https://www.trust-security.xyz/) | August 2025   | [`2025-08-27_trust_security_misc_curve_oracles.pdf`](misc/2025-08-27_trust_security_misc_curve_oracles.pdf) | Curve Oracles      |

## 📁 Repository Structure

```
audits/
├── staking-v2/           # Staking v2 strategy audits
├── onlyboost/            # OnlyBoost strategy audits
├── votemarket/           # Votemarket platform audits
│   ├── v1/
│   └── v2/
│       └── laposte/      # LaPoste module audit
├── vlsdt/                # vlSDT token audits
├── misc/                 # veSDT token, liquid lockers, oracles...
└── README.md
```

## 📄 Naming Convention

All audit files follow a standardized naming pattern for easy identification:

```
YYYY-MM-DD_auditor_product_version.ext
```

**Examples:**

- `2024-09-01_trust_security_votemarket_v2.pdf`
- `2023-11-22_zachobront_onlyboost.md`

## 🔍 Security Partners

Stake DAO works with industry-leading security firms to ensure the safety of our protocols:

- **[ChainSecurity](https://chainsecurity.com/)** - Swiss blockchain security experts
- **[Omniscia](https://omniscia.io/)** - Decentralized security firm
- **[Trust Security](https://www.trust-security.xyz/)** - Smart contract auditing specialists
- **[Pashov Audit Group](https://www.pashov.net/)** - Elite security researchers
- **[Zach Obront](https://github.com/zobront)** - Independent security researcher

## 🔗 Links

- **Website:** [stakedao.org](https://stakedao.org)
- **Documentation:** [docs.stakedao.org](https://docs.stakedao.org)
- **GitHub:** [github.com/stake-dao](https://github.com/stake-dao)

## 📄 Disclaimer

These audit reports are provided for transparency and informational purposes. While audits help identify potential vulnerabilities, they do not guarantee the absence of bugs or vulnerabilities. Users should conduct their own research and risk assessment.
