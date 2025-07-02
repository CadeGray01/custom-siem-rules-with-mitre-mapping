# Detection Rules Repository

This repository is structured to support the development, testing, and mapping of custom detection rules for security operations. It includes:

- `rules/`: Custom detection rules in Sigma YAML or Splunk SPL format.
- `test-logs/`: Example logs used to test and validate detection rules.
- `validation-results/`: Results of detection rule validation against test logs.
- `mitre-attack-mapping/`: Mappings of detection rules to MITRE ATT&CK tactics and techniques.

## Usage
- Add new detection rules to the `rules/` directory.
- Place relevant test logs in `test-logs/`.
- Store validation results in `validation-results/`.
- Document MITRE ATT&CK mappings in `mitre-attack-mapping/`. 