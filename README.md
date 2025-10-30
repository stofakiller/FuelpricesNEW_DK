[![hacs_badge](https://img.shields.io/badge/HACS-Default-41BDF5.svg)](https://github.com/hacs/integration)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/J-Lindvig/Fuelprices_DK)
![GitHub all releases](https://img.shields.io/github/downloads/J-Lindvig/Fuelprices_DK/total)
![GitHub last commit](https://img.shields.io/github/last-commit/J-Lindvig/Fuelprices_DK)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/J-Lindvig/Fuelprices_DK)
[![Buy me a coffee](https://img.shields.io/static/v1.svg?label=Buy%20me%20a%20coffee&message=🥨&color=black&logo=buy%20me%20a%20coffee&logoColor=white&labelColor=6f4e37)](https://www.buymeacoffee.com/20205255)

# Fuelprices NEW DK
## Introduction
With Fuelprices_NEW DK it is possible to track fuelprices in Denmark.

## Installation
At this ealy stage, it's by adding this repository manual in HACS...

## Configuration
In the default configuration it will track the following fueltypes:
- Octane 95
- Octane 95+ (additives)
- Octane 100
- Diesel
- Diesel+ (additives)
- Electric

From these fuelcompanies:
- Circle K
- F24 (Not working yet)
- Go'On
- ingo
- OIL! tank & go (Not working yet)
- OK
- Q8
- Shell (Not working yet, and i can so far only find business/list prices)

## Configuration
```yaml
fuelprices_dk:
  # Optional entries
  # Bypass the default update interval (60 minutes)
  update_interval: 300
  companies:
  # possible values are: circlek, goon, ingo, ok and q8
    - ok
    - q8
  fueltypes:
  # Possible values are: oktan 95, oktan 95+, oktan 100, diesel, diesel+ and electric
    - oktan 95
    - diesel
    - electric
```
