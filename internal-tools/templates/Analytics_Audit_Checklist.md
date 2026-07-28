# Analytics Audit Checklist

*Use this checklist at project kickoff to assess the current state of a client's analytics setup.*

---

## GA4 Setup

- [ ] GA4 property is created and linked to the website
- [ ] Measurement ID is installed correctly (via GTM or direct embed)
- [ ] Data stream is active and receiving real-time data
- [ ] Internal traffic filter is applied (exclude office/developer IPs)
- [ ] Cross-domain tracking configured (if applicable)
- [ ] Data retention set to 14 months (default is 2 months)

---

## Conversion Events

- [ ] Key conversions identified (form submissions, purchases, signups)
- [ ] Conversion events marked in GA4 event settings
- [ ] Thank-you pages or confirmation events verified as triggers
- [ ] Goal values assigned where applicable

---

## UTM Parameters

- [ ] UTM parameters in use for paid campaigns (source, medium, campaign)
- [ ] UTM naming convention is consistent across all channels
- [ ] No UTMs on internal links (causes session fragmentation)
- [ ] Campaign URLs tested through GA4 Realtime reports

---

## Google Tag Manager

- [ ] GTM container is installed on all pages (including confirmation/thank-you pages)
- [ ] Tags organized with clear naming convention
- [ ] No duplicate GA4 tags firing
- [ ] GTM Preview mode used to verify tags fire correctly

---

## E-Commerce Tracking (if applicable)

- [ ] E-commerce feature enabled in GA4
- [ ] Purchase events sending revenue, transaction ID, and item data
- [ ] Cart abandonment steps tracked

---

## Funnels & Goals

- [ ] Funnel exploration set up for key conversion paths
- [ ] Drop-off points identified
- [ ] Audience segments created for retargeting (if applicable)

---

## Filters & Views

- [ ] Bot filtering enabled
- [ ] Location/country exclusions applied if needed
- [ ] Custom channel groupings match business model

---

## Ads Integrations

- [ ] Google Ads linked to GA4 property
- [ ] Auto-tagging enabled in Google Ads
- [ ] Meta Ads pixel verified (if applicable)
- [ ] Conversion import from GA4 → Google Ads confirmed

---

## Reporting & Dashboards

- [ ] Looker Studio dashboard connected to GA4
- [ ] Key metrics populated correctly in reports
- [ ] Date comparisons configured (MoM, YoY)
- [ ] Scheduled email reports set up for client (if applicable)

---

## Audit Notes

| Issue | Severity | Recommended Fix |
|---|---|---|
| | | |
| | | |
