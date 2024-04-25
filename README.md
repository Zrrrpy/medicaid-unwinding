# medicaid-unwinding

## Tl;dr
The [Coverage Gap Analysis file](https://github.com/Zrrrpy/medicaid-unwinding/blob/main/coverage_gap_analysis.ipynb) contains all inputs and outputs of a data analysis on possible health coverage gaps experienced during the period of Medicaid Unwinding. As of 4/25/24, the data collection period for this analysis is April 2023 through December 2023. 

## What is Medicaid Unwinding?
Medicaid Unwinding is the period following the end of the Public Health Emergency (PHE) during which states resume redetermining enrollees' Medicaid eiligibility. This usually happens annually, but [the Continuous Care provision in the Families First Coronavirus Response Act](https://www.kff.org/medicaid/issue-brief/10-things-to-know-about-the-unwinding-of-the-medicaid-continuous-enrollment-provision/#:~:text=At%20the%20start%20of%20the,exchange%20for%20enhanced%20federal%20funding.) mandated that states pause annual redeterminations during the PHE. During this time, Medicaid enrollments consequently increased – leaving millions of people to be redetermined beginning in March, 2023. 

## What is the impact of Medicaid Unwinding?
[The Department of Health and Human Services predicted](https://aspe.hhs.gov/sites/default/files/documents/dc73e82abf7fc26b6a8e5cc52ae42d48/aspe-end-mcaid-continuous-coverage.pdf) that 15 million people would lose Medicaid as a part of this process, many for "procedural" reasons (i.e. the state did not have an enrollee's updated contact information, so couldn't send them a notice requesting they update their information). To date, 20.3 million people have lost Medicaid since March of 2023, and the Unwinding period is not yet over. 

## What is Medicaid expansion?
Medicaid expansion refers to whether or not a state has expanded its Medicaid eligibility criteria. Currently, [all states but ten](https://www.kff.org/affordable-care-act/issue-brief/status-of-state-medicaid-expansion-decisions-interactive-map/) have expanded Medicaid eligibility criteria to include more people with incomes slightly above the Federal Poverty Level.

## What's the relationship between Medicaid expansion and Medicaid Unwinding?
It has been anticipated that more people may find themselves in a "coverage gap", i.e. a period in which an individual does not have any health coverage, in states that _have not_ expanded Medicaid than it states that have.

## What's in this repo?
This repo contains a .ipynb file in which: 
- data from this period is extracted as it's released
- data is cleaned and transformed
- data is analyzed

## What's being analyzed?
The primary question this work seeks to answer is what role a state's Medicaid expansion status plays in the number of possible coverage gaps that appear to be occuring at a state level. 

### Hypotheses
H<sub>1</sub> Coverage gaps in states that have not expanded Medicaid eligibility > coverage gaps in states which have expanded Medicaid eligibility.
H<sub>0</sub> Coverage gaps in states that have not expanded Medicaid eligibility ≤ coverage gaps in states that have expanded Medicaid eligibility.

### Why do you say "possible"?
This analysis does not crosswalk data against new enrollments in coverage outside of Medicaid and Qualifying Health Plans (QHP a.k.a. marketplace coverage or obamacare). It is possible that in states where coverage gaps appear to be occurring, people are actually transitioning to another type of coverage, i.e. employer sponsored coverage, Cobra, a state employee health plan, Medicare, etc.
