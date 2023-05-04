# vATIS NavData

This repository contains the navdata (airports and navaids) files used by [vATIS](https://github.com/vatis-project/vatis).

## How do I submit a navdata change?
Updates to the navdata files should be made directly by submitting a [pull request](https://github.com/vatis-project/navdata/pulls). 
The navdata files hosted in this GitHub project are in `yaml` format to make it easier for contributions. Approved changes will be merged and automatically converted to `json` file format for use by vATIS.

### Data Format
The `airports.yaml` file contains data for airports. An airport is composed of four properties: `ID`, `Name`, `Lat` (Latitude) and `Lon` (Longitude).

```yaml
- ID: KLAX
  Name: LOS ANGELES INTERNATIONAL AIRPORT
  Lat: 33.942495
  Lon: -118.40807
```

The `navaids.yaml` file contains navaid (VOR/VORTAC) data. A navaid is composed of two properties: `ID` and `Name`. 

```yaml
- ID: LAX
  Name: LOS ANGELES
```
