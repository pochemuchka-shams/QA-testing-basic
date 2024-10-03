# Test Case Design for Equivalence Partitioning and Boundary Value Analysis

**Name:** Tareq Shams  
**Course Name:** DIPTI- STQA-2ND BATCH  
**Course Instructor:** Mr. Mohammad Akter Ul Alam Suvro  
**Date:** 02/10/2024  

## Test Case Design for Equivalence Partitioning

| Test Case ID | Test Case Name                   | Field         | Input Type                                      | Steps                                                                                  | Expected Result  |
|--------------|----------------------------------|---------------|------------------------------------------------|----------------------------------------------------------------------------------------|------------------|
| 1            | Course Name Valid Selection      | Course Name   | Valid (Math-1, English-1)                      | 1. Open Form <br> 2. Select ‘Math-1’ from dropdown. <br> 3. Submit                     | Successful       |
| 2            | Course Name Invalid Selection    | Course Name   | Invalid (not in dropdown)                      | 1. Open Form <br> 2. Enter other value eg. ‘GED-1’ <br> 3. Submit                      | Error            |
| 3            | Attendance Range Valid           | Attendance    | Valid (0-8)                                    | 1. Enter value 4 <br> 2. Submit                                                        | Successful       |
| 4            | Attendance Range Invalid         | Attendance    | Invalid (negative value or greater than 8)     | 1. Enter value -1 <br> 2. Submit                                                       | Error            |
| 5            | Presentation Range Valid         | Presentation  | Valid (0-12)                                   | 1. Enter 8 <br> 2. Submit                                                              | Successful       |
| 6            | Presentation Range Invalid       | Presentation  | Invalid (negative value or greater than 12)    | 1. Enter 16 <br> 2. Submit                                                             | Error            |
| 7            | Quiz Range Valid                 | Quiz          | Valid (0-10)                                   | 1. Enter 2 <br> 2. Submit                                                              | Successful       |
| 8            | Quiz Range Invalid               | Quiz          | Invalid (negative value or greater than 10)    | 1. Enter 25 <br> 2. Submit                                                             | Error            |
| 9            | Mid Range Valid                  | Mid           | Valid (0-30)                                   | 1. Enter 17 <br> 2. Submit                                                             | Successful       |
| 10           | Mid Range Invalid                | Mid           | Invalid (negative value or greater than 30)    | 1. Enter -9 <br> 2. Submit                                                             | Error            |
| 11           | Final Range Valid                | Final         | Valid (0-40)                                   | 1. Enter 39 <br> 2. Submit                                                             | Successful       |
| 12           | Final Range Invalid              | Final         | Invalid (negative value or greater than 40)    | 1. Enter 43 <br> 2. Submit                                                             | Error            |

---

## Test Case Design for Boundary Value Analysis

| Test Case ID | Field        | Boundary Condition           | Test Data  | Expected Result |
|--------------|--------------|------------------------------|------------|-----------------|
| 1            | Attendance    | Lower Boundary               | 0          | Successful      |
| 2            | Attendance    | Just Below Lower Boundary    | -1         | Error           |
| 3            | Attendance    | Upper Boundary               | 8          | Successful      |
| 4            | Attendance    | Just Above Upper Boundary    | 9          | Error           |
| 5            | Presentation  | Lower Boundary               | 0          | Successful      |
| 6            | Presentation  | Just Below Lower Boundary    | -1         | Error           |
| 7            | Presentation  | Upper Boundary               | 12         | Successful      |
| 8            | Presentation  | Just Above Upper Boundary    | 13         | Error           |
| 9            | Quiz          | Lower Boundary               | 0          | Successful      |
| 10           | Quiz          | Just Below Lower Boundary    | -1         | Error           |
| 11           | Quiz          | Upper Boundary               | 10         | Successful      |
| 12           | Quiz          | Just Above Upper Boundary    | 11         | Error           |
| 13           | Mid           | Lower Boundary               | 0          | Successful      |
| 14           | Mid           | Just Below Lower Boundary    | -1         | Error           |
| 15           | Mid           | Upper Boundary               | 30         | Successful      |
| 16           | Mid           | Just Above Upper Boundary    | 31         | Error           |
| 17           | Final         | Lower Boundary               | 0          | Successful      |
| 18           | Final         | Just Below Lower Boundary    | -1         | Error           |
| 19           | Final         | Upper Boundary               | 40         | Successful      |
| 20           | Final         | Just Above Upper Boundary    | 41         | Error           |

---

## Image Format Information

- **Format**: Portable Network Graphic (PNG)
- **Bits Per Pixel**: 32
- **Color**: Truecolor with alpha
- **Dimensions**: 713 x 844
- **Interlaced**: Yes
- **XResolution**: 96
- **YResolution**: 96
