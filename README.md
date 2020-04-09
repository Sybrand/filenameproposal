# File Name Proposal For Model Files

C_Haines_BC_South-MODEL-YYYYMMDDHHZ_YYYYMMMDD18PDT

- **C_Haines** : constant string indicating that this image contains Lower Atmosphere Severity Index information.
- **BC_South** : constant string indicating the area, Southern British Columbia, that this image relates to.
- **MODEL** : string indicating this image generated using the Global Environmental Multiscale Model. [GDPS, RDPS]
- **YYYYMMDD** : Year, month and day of the model run start.
- **HHZ**: UTC mode run start. For RDPS model: [00Z,06Z,12Z and 18Z], for GDPS model: [00Z, 12Z]
- **YYYYMMDDHHPDT** : Year, month, day and hour in Pacific Daylight Time of the forecast. For GDPS this extends to 5 days (120 hours) from the model run start. For RDPS this extends to 2 days (48 hours) from the model run start.
- **HHPDT** : Forecast hour in pacific daylight time. Forecast hour increments in one hour segments. The hours extend

## Changes:

### 2020 04 09
- Dropped T, i.e. 'C_Haines_BC_South-GDPS-20200406T00...' becomes 'C_Haines_BC_South-GDPS-2020040600...'
- Dropped minutes from forecast time, i.e. 'C_Haines_BC_South-GDPS-2020040600Z_202004061800PDT...' becomes 'C_Haines_BC_South-GDPS-2020040600Z_2020040618PDT'
