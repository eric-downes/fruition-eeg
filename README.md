# Fruition EEG

Goal: To analyze [this data](https://osf.io/srfnz/) and understand something about Fruitions.
Questions?  Ask marcin .dot. kowrygo .at. ebenefactors .dot. org.

Daniel's fruitions often precede an eye-blink and he has provided some of these for controls.  
We'll likely focus on the second before such eye-blinks, especially T-minus .25 sec.

## Work Stages

1. Clean & Annotate Data:
  - At least 3 people providing annotation backed by visual sanity-checks that the data marked by Daniel in audio recordings is usable
  - Use Pull Requests to merge data annotation joins
  - Deliverable 1: Data we feel confident using for the actual hard part
  - Deliverable 2: Test a few automated schemes (construct ROC/AUC) such as
    - generic outlier detection
    - spectrogram-based (alpha drop)
    - eye-blink detection based on provided
    - ???

2. Data conversion & ETL
  - Collect/provide python scripts & use examples for converting data into a standard format
  - pydantic classes to automate basic tasks such as
    - If Deliverable 1.2: filtering out crap, finding eye-blinks,
    - fft--time-domain interconversion
    - routine spectrum analysis
  - Deliverable 1: conversion tools
  - Deliverable 2: data representation classes using a standard format on the backend
 
- Fruition analysis
  - TBD!
