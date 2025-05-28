# RADAR SW

## 1. Pushed the changes without testing

| Field               | Value                                                               |
| ------------------- | ------------------------------------------------------------------- |
| **ID**              | TD-001                                                              |
| **Date Identified** | 2025-04-14                                                          |
| **Module**          | `Communication`                                                   |
| **Type**            | Code and Testing Debt                                               |
| **Description**     | Enabled new feature of BswM in the module, built bsw component but not the complete repo, no developer test done    |
| **Cause**           | Tight timeline                                  |
| **Impact**          | Break the complete repo, nobody was able to build complete SW |
| **Priority**        | High                                                                |
| **Effort**          | \~4 hours (refactor and developer test)                               |
| **Owner**           | SW Developer                                                       |
| **Status**          | Done                                                         |
| **Dependencies**    | No dependency                                     |
| **Notes**           | Need to change the code due to cmake access problem    |


## 2. Feature developed without Unit test

| Field               | Value                                                               |
| ------------------- | ------------------------------------------------------------------- |
| **ID**              | TD-002                                                              |
| **Date Identified** | 2024-10-23                                                          |
| **Module**          | `Communication`                                                   |
| **Type**            | Testing Debt                                               |
| **Description**     | Develop new feature of SD reset when data is missing for 500ms from partner ECU. |
| **Cause**           | Customer Expected as DevDrop to test on Vehicle                                  |
| **Impact**          | Unit Test Gap in the coverage matrix |
| **Priority**        | Low                                                                |
| **Effort**          | \~8 hours (UT design and execution)                               |
| **Owner**           | SW Developer                                                       |
| **Status**          | Done                                                         |
| **Dependencies**    | No dependency                                     |
| **Notes**           | Need to add new testcases for new feature    |
