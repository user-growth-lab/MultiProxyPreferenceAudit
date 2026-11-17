# MultiProxyPreferenceAudit

Public reproducibility materials for **Auditing Multi-Proxy Explanations of Web User Preferences: Identification Boundaries and Abstention** (WSDM 2027).

**Authors:** Yu Zhang, Zhihan Wang, Yuhang Lu, and Shuai Li.  
**Corresponding author:** Zhihan Wang.  
**Paper DOI:** <https://doi.org/10.1145/3862322.3863442>

## Download the complete code package

- [Fixed release v1.0.0](https://github.com/user-growth-lab/MultiProxyPreferenceAudit/releases/tag/v1.0.0)
- [Complete 40-file package: MultiProxyPreferenceAudit-v1.0.0.zip](https://github.com/user-growth-lab/MultiProxyPreferenceAudit/releases/download/v1.0.0/MultiProxyPreferenceAudit-v1.0.0.zip)

The complete code is provided as the named release asset above. This repository branch is a landing page; GitHub's automatically generated **Source code** archives contain this landing page, not the complete experimental package. Download the named asset, extract it, and enter its `MultiProxyPreferenceAudit/` directory.

ZIP SHA-256:

```text
001e621d9c294f38d6040f2f5c7d876b12cd645170fcb5cbea60d6a70868b359
```

Verify the extracted package with Python's standard library:

```sh
PYTHONDONTWRITEBYTECODE=1 python3 verify_repository.py
```

See the package README for installation, the 28 controlled-benchmark tests, and registered rerun commands. Its 40-file manifest was verified before release. Thirty-four scientific files remain byte-identical to the approved review snapshot; six documentation and metadata files identify the public release.

## Contents and evidence boundary

The package includes controlled-benchmark code, tests, configuration, frozen discovery/confirmation/sensitivity outputs, the unchanged review-stage technical appendix, and selected Amazon aggregate results. The controlled benchmark is rerunnable. The Amazon material is aggregate-only and **does not support exact end-to-end regeneration** of the Amazon study; the observable comparator is not latent-preference ground truth.

Raw review data, user-level records and derivatives, prompts, model responses, fitted private state, model weights, the main manuscript, private Git history, and internal review/approval records are excluded. See `DATA_ACCESS_AND_RELEASE_BOUNDARY.md` inside the package.

Original code and documentation retain the **MIT License**. Third-party materials retain their own terms, detailed in the package's `THIRD_PARTY_NOTICES.md`. The main paper's ACM CC BY 4.0 publication license is separate.
