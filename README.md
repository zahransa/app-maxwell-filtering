<h1 align="center">app-maxwell-filtering</h1>

<p align="center">
  Placeholder App holding only an MNE-Python example script for Maxwell filtering (tSSS with movement compensation) of MEG data; it has no main script, inputs or outputs and cannot run.
</p>

<p align="center">
  <a href="https://github.com/brainlife/abcd-spec"><img src="https://img.shields.io/badge/ABCD_Spec-v1.1-green.svg" alt="ABCD Spec v1.1"></a>
  <a href="https://doi.org/10.25663/brainlife.app.660"><img src="https://img.shields.io/badge/Brainlife-brainlife.app.660-blue.svg" alt="Run on brainlife.io"></a>
</p>

## At a glance

<!-- brainlife-app:begin (generated from the App manifest; edit the manifest, not this block) -->

> **Placeholder App holding only an MNE-Python example script for Maxwell filtering (tSSS with movement compensation) of MEG data; it has no main script, inputs or outputs and cannot run.**

The repository contains a single script, 03-maxwell_filtering.py, copied from an MNE-Python group study example that Maxwell-filters the ds117 dataset with tSSS and movement compensation and low-pass filters at 40 Hz, using paths from a local library.config module. There is no main file and no inputs, outputs or parameters are registered, so the App cannot be executed on brainlife.io.

| | |
|---|---|
| **Run it** | [doi.org/10.25663/brainlife.app.660](https://doi.org/10.25663/brainlife.app.660) |

<!-- brainlife-app:end -->

## Running the App

### On brainlife.io

Open the App at [doi.org/10.25663/brainlife.app.660](https://doi.org/10.25663/brainlife.app.660), choose the input datasets from your project and press **Execute**.

### Locally

You need [`jq`](https://jqlang.github.io/jq/).

1. Clone this repository.
2. Create `config.json` with the paths to your inputs and the parameters:

   ```json
   {}
   ```

3. Run `./main`.

## Citing

If you use this App, please cite it, the software it builds on and brainlife.io:

- app-maxwell-filtering. brainlife.io App. [doi:10.25663/brainlife.app.660](https://doi.org/10.25663/brainlife.app.660)
- Gramfort et al. MEG and EEG data analysis with MNE-Python. *Frontiers in Neuroscience* 7 (2013). [doi:10.3389/fnins.2013.00267](https://doi.org/10.3389/fnins.2013.00267)
- Hayashi S, Caron BA, Heinsfeld AS, et al. brainlife.io: a decentralized and open-source cloud platform to support neuroscience research. *Nature Methods* 21:809–813 (2024). [doi:10.1038/s41592-024-02237-2](https://doi.org/10.1038/s41592-024-02237-2)
- Avesani P, McPherson B, Hayashi S, et al. The open diffusion data derivatives, brain data upcycling via integrated publishing of derivatives and reproducible open cloud services. *Scientific Data* 6:69 (2019). [doi:10.1038/s41597-019-0073-y](https://doi.org/10.1038/s41597-019-0073-y)

## Authors

Maintained by [@zahransa](https://github.com/zahransa).
