# AEON Target Submission Tutorials for NOIRLab Facilities

by Tomás Ahumada (tomas.ahumada at noirlab dot edu)
This repository contains tutorials, example scripts, and Jupyter Notebooks for **programmatically** submitting astronomical targets to the [AEON (Astronomical Event Observatory Network)](https://lco.global/aeon/) queue using the API. These guides are specifically tailored for observing with NOIRLab facilities, including **DECam** and **NEWFIRM**.

> ** Note on Manual Submission**
> This repository focuses on automated and bulk submissions via the programmatic API. If you only have a few targets to submit, you do not need to use these scripts. You can still submit targets individually and manually using the LCO Observation Portal's web interface at:
> **[https://observe.lco.global/create](https://observe.lco.global/create)**

---

##  Prerequisites

Before running any of the tutorials, you must have the following:

1. **An LCO API Token:** Required to authenticate with the LCO Observation Portal (which schedules AEON time). You can find this in your LCO portal profile.
2. **An Active Program ID:** You must have an approved NOIRLab observing program that has been allocated AEON time.
3. **Python 3.8+:** The examples in this repository rely on Python.

##  Setup and Installation

**1. Clone the repository**
```bash
git clone [https://github.com/your-organization/aeon-target-submission.git](https://github.com/your-organization/aeon-target-submission.git)
cd aeon-target-submission
