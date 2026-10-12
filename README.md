# Data (not included in this repository)

| Resource | Where to get it | Used for |
|---|---|---|
| CICIDS2017 (CSV files, "MachineLearningCVE") | Canadian Institute for Cybersecurity: https://www.unb.ca/cic/datasets/ids-2017.html | Part 1: primary dataset |
| CTU-13 scenarios 42, 43 and 44 (`.binetflow`) | Stratosphere Laboratory, CTU Prague, Malware Capture Facility Project: https://www.stratosphereips.org/datasets-ctu13 | Parts 1 and 2: real public-IP validation |
| MaxMind GeoLite2-City database (`GeoLite2-City.mmdb`) | https://dev.maxmind.com/geoip/geolite2-free-geolocation-data (free account required; redistribution not permitted) | IP geolocation and cross-border status |

Part 2 downloads the three CTU-13 files automatically from the Malware Capture Facility Project server into `/content` when they are missing:

- Scenario 42: `https://mcfp.felk.cvut.cz/publicDatasets/CTU-Malware-Capture-Botnet-42/capture20110810.binetflow.2format`
- Scenario 43: `https://mcfp.felk.cvut.cz/publicDatasets/CTU-Malware-Capture-Botnet-43/capture20110811.binetflow.2format`
- Scenario 44: `https://mcfp.felk.cvut.cz/publicDatasets/CTU-Malware-Capture-Botnet-44/capture20110812.binetflow.2format`

Suggested Google Drive layout used by the notebooks:

```
MyDrive/
  CICIDS2017/            <- CICIDS2017 CSV files and GeoLite2-City.mmdb
```
