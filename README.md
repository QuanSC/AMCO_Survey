# AMCO Member Survey 2022–2026

Interactive data dashboard for the Academic Medical Center Optometrists (AMCO) SIG member survey, a repeated cross-sectional survey conducted in 2022, 2024, and 2026. Findings were shared with members at the AMCO SIG meeting during Academy 2026 Anaheim.

**Live site:** [QuanSC.github.io/AMCO_Survey](https://quansc.github.io/AMCO_Survey/)

## What this is

A self-contained single-page web app presenting three survey cycles (2022, 2024, 2026) on the working conditions, compensation, academic roles, and professional identity of optometrists employed at U.S. Academic Medical Centers. No server, no build step, no dependencies: just one HTML file.

The page has two sections:

1. **Summary Dashboard.** Narrative findings with headline stats, trend charts, and key takeaways from all three cycles. Quick to scan and mobile-friendly.
2. **Per-Cycle Explorer.** A filterable tool for comparing 2022 and 2024 results by region and tenure against 2026 aggregate figures, across four topic tabs: Compensation, Research, Identity, and OMD Relations.

## Key findings (2022–2026)

- **Compensation rose:** the >$200K band more than doubled, from 16.3% (2022) to 40.4% (2026). Figures are nominal (not inflation-adjusted).
- **Protected research time declined:** respondents reporting ≥26% research FTE fell from 13.3% (n = 6 of 45) in 2022 to about 4% in 2026.
- **Collegial equality with OMDs dipped:** "equals" fell from 69% (2024) to 57% (2026), below the 2022 baseline.
- **Professional advancement as a motivator for working at an AMC rose** (ranked motivator score, 35.4 in 2022 → 47.4 in 2026), even as structural support for promotion declined.
- **Teaching engagement is high:** 73% lecture OMD residents, and 92% attend Grand Rounds.

Because different people responded in each cycle, these are changes across respondent groups, not within the same individuals. Small subgroup sizes mean some shifts reflect only a few respondents; interpret directionally.

## Data

| Cycle | N (screened AMC) | Method |
|---|---|---|
| 2022 | 45 | SurveyMonkey, AMCO SIG listserv |
| 2024 | 63 | SurveyMonkey, AMCO SIG listserv |
| 2026 | 56 | SurveyMonkey, AMCO SIG listserv |

## Data and privacy

These results come from AMCO SIG member surveys conducted for organizational purposes. All published data are **aggregated and de-identified**; no individual respondent records are included in this site.

- 2022 and 2024 results are stored as **pre-computed counts** for each cycle × region × tenure combination.
- **Groups with fewer than 5 respondents are suppressed**, including at the level of individual questions.
- **Secondary suppression** is applied so that suppressed groups cannot be recovered by subtracting visible groups from totals.
- Region and tenure breakdowns are not cross-tabulated against each other (e.g., the regional mix is hidden when a tenure filter is applied).
- 2026 figures are aggregate summary values.

Questions about the data: scquan@bsd.uchicago.edu

## Credits

- **Survey design:** Thomas Stokkermans, OD, PhD · Case Western Reserve University / UH Eye Institute (2022, 2024); Steven C. Quan, OD, FAAO (2026)
- **Data collection and analysis:** Steven C. Quan, OD, FAAO · University of Chicago Medicine
- **Dashboard development:** Steven C. Quan, OD, FAAO

**Contact:** [scquan@bsd.uchicago.edu](mailto:scquan@bsd.uchicago.edu)

## Citation and use

Preliminary findings. Not for citation without permission. Living document.

If you use or adapt this work, please credit the AMCO SIG Member Survey and contact the author.

AMCO SIG · American Academy of Optometry · 2026
