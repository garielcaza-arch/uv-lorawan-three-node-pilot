# UV-LoRaWAN Three-Node Field Pilot

Dataset supporting the paper *Time-Resolved UV Index Monitoring over LoRaWAN: A Three-Node Field Pilot in a High-Altitude Urban Area*.

The dataset contains the 18 reported aggregate observations from three sensing nodes across six time bands.

## Nodes
- UV1: LTR390UV
- UV2: LTR390UV
- UV3: AS7331

## Variables
- `node`: sensing-node identifier
- `sensor`: UV sensor model
- `time_band`: reported measurement interval
- `uvi`: reported ultraviolet index
- `irradiance`: reported irradiance value
- `irradiance_unit`: unit reported in the source table

The values are transcribed from Table 3.1 of the thesis and correspond to the six reported time bands for each node. No credentials, API keys, passwords, or network secrets are included.
