# Python _Project_4
 
# Variable Description and Sources

## Dependent Variable

| Variable       | Unit        | Description                                                                                                  | Source                                                                                                                                           |
|----------------|-------------|--------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
| HHexpenditure  | IDR         | Total expenditure of farmer households in the form of food and non-food consumption.                         | Data taken from Book 1 IFLS: `b1_ks0`, `b1_ks1`, `b1_ks2`, `b1_ks3`, `b1_ks4`, `b1_ksr1`, `b1_ksr2`, `b1_ksr3`, `b1_ksr4`.                        |

---

## Interacted Variables

| Variable                        | Values                     | Description                                                                                                        | Source                                                 |
|---------------------------------|----------------------------|--------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------|
| Before-After Dummy              | `1`: IFLS 2014; `0`: IFLS 2007 | Before and after comparison between survey years.                                                                  |                                                        |
| Opening Access to Land (State-Led Approach) | `1`: Access change; `0`: No change | Land redistribution for whole farming households.                                                                  | Data from Book 2 IFLS: `b2_ut1`, question `ut00a`.     |
| Expanding Access to Land (State-Led Approach) | `1`: Small to large land size; `0`: No change | Land redistribution for smallholders owning land (< 0.5 ha to ≥ 0.5 ha).                                           | Data from Book 2 IFLS: `b2_ut1`, question `ut00b`.     |
| Opening Access to Land (Market-Led Approach) | `1`: Access change; `0`: No change | Land leases for landless farmer households.                                                                        | Data from Book 2 IFLS: `b2_ut1`, question `ut01b`.     |
| Expanding Access to Land (Market-Led Approach) | `1`: Narrow to broad access; `0`: No change | Land legalization for farming households owning land.                                                              | Data from Book 2 IFLS: `b2_ut`, question `ut00e`.      |

---

## Control Variables

| Variable                      | Values                      | Unit       | Description                                    |
|-------------------------------|-----------------------------|------------|------------------------------------------------|
| Gender of Head of Family      | `1`: Male; `0`: Female      | -          | Gender of the head of household.               |
| Provincial Dummy              | `1`: Javanese; `0`: Non-Javanese | -          | Regional basis.                                |
| Age of Head of Family         | -                           | Year       | Age of the head of family.                     |
| Dummy Zone                    | `1`: Urban; `0`: Rural      | -          | Area basis.                                    |
| Number of Household Members   | -                           | Amount     | Size of family members in the household.       |

---

## Notes
Control variables are used to reduce bias in the regression model, as outlined by Fredriksson (2019).
