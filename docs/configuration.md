# Configuration

The Meterian Security SCA plugin's configuration can be found in the `File > Settings... > Tools` menu.

Global settings are under `File > Settings... > Tools > Meterian Security SCA Settings` .

Project settings are under `File > Settings... > Tools > Meterian Security SCA Settings > Project Preferences`

## Global Settings

| Label | Default | Description |
|-------|---------|-------------|
| Grace Time in seconds | 60 | Grace time between the last manifest change and the start of the analysis |
| Highlight problems at severity | Warning | Define the maximum level applicable to problems |
| Minimum level of notifications shown | Info | Filter out notifications from Meterian below this severity |

## Project Settings

| Label | Default | Description |
|-------|---------|-------------|
| Disable plugin for current project | false | Enables/Disables the plugin for the current project |
| CVSS Threshold | 3.5 | Vulnerabilities with a CVSS score below this value won't be flagged |
| EPSS Threshold | 0.01 | Vulnerabilities with an EPSS score below this value won't be flagged |
| Severity Threshold | LOW | Vulnerabilities below this level won't be flagged |

