# Assignment 1 — Data Profiling (EDA): Apartment Rentals in Kuala Lumpur & Selangor

## Group Members
* **MUHAMMAD AIMAN FAIQ BIN EMRAN** — A211494
* **MUHAMMAD FIRDAUS BIN SUHAIMI** — A211437
* **MUHAMMAD IZZAT AMIR BIN MOHD ZAKI** — A211680
* **MANVEER SINGH A/L RAVINDER SINGH** — A211153

---

## Scenario
A student union wants to publish a "fair rent guide" so students and young graduates moving to the Klang Valley can spot overpriced listings. We profile and clean ~20,000 mudah.my rental ads so they can reliably answer:

1. Typical monthly rent by area and property type.
2. How size (rent per sq ft) and furnishing change rent.
3. Whether units near rail transit cost more.

The data is messy (rent and size stored as text, blanks and "-", 0 rent, 100,000,000 sq ft units, future completion years, reposted ads), has some PII risk (ad IDs and contact details in titles), and is unbalanced across areas and unit types.

---

## Data Source
* **Dataset Name:** Rental Pricing Dataset, Malaysia
* **Publisher:** Kaggle (Ariel Wijaya) — [Kaggle Dataset Link](https://www.kaggle.com/datasets/ariewijaya/rent-pricing-kuala-lumpur-malaysi)
* **Original Source:** Apartment/condo rental ads scraped from mudah.my (KL & Selangor)
* **Date Accessed:** 2026-10-15
* **Licence:** As stated on the Kaggle dataset page

---

## How to Run

```bash
git clone <this-repo-url>
cd kl-rental-data-profiling
pip install -r requirements.txt
