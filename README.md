# tube-delay-dynamics-heartbeat

Public collector health JSON for the [Tube Delay Dynamics](https://github.com/arnavpopley/tube-delay-dynamics) site.

This repository contains **no TfL prediction rows and no API keys**. `status.json` is overwritten by the Oracle collector over SSH using a write-only deploy key. Anyone with that key can spoof the dashboard card; they cannot read or change the research dataset.
