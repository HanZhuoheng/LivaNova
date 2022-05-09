# LivaNova

LivaNova is a global medical technology company that creates breakthrough treatments for conditions affecting the head and heart. The main focus of this project is drug-resistant epilepsy (DRE) patients, who have a disorder in which nerve cell activity in the brain is disturbed, causing seizures.

With the common understanding that different regions and different hospitals can have different number of DRE patients, the overall objective for this project is to use public data resources to estimate the number of drug-resistant epilepsy (DRE) patients in the specified area by two dimensions: hospital (where people seek treatment for) and zip code (where people live) for the company to save cost of paying external data providers and optimize selling VNS devices to targeted hospitals treating DRE patients based on feasible recommendations

## Datasets

### Zip Code

CDC used national data sources including the 2015 National Health Interview Survey (NHIS) for adults (aged ≥18 years), the 2011–2012 National Survey of Children’s Health (NSCH), and the 2015 Current Population Survey data, describing 2014 income levels, to estimate prevalent cases of active epilepsy, overall and by state, to provide information for state public health planning. This data will need to be scraped from the website: 

https://www.cdc.gov/mmwr/volumes/66/wr/mm6631a1.htm

US Census Bureau - population by zip code, age bracket

### Hospital

Staffed Hospital Beds

This data was made public during COVID to track ICU beds by hospital over time. This data can be found from the website:

https://healthdata.gov/Hospital/COVID-19-Reported-Patient-Impact-and-Hospital-Capa/anag-cw7u/data

CMS Discharges

CMS gives the number of discharges per DRG code (e.g., 100-101 are for seizures) by hospital and zip

https://data.cms.gov/provider-summary-by-type-of-service/medicare-inpatient-hospitals/medicare-inpatient-hospitals-by-provider-and-service

CEC

The NAEC accredits hospitals as CEC centers if they meet certain criteria designating them as a top epilepsy center. Many DRE epilepsy patients travel to CECs to receive advanced care. This data can be found from the website:

https://www.naec-epilepsy.org/about-epilepsy-centers/find-an-epilepsy-center/all-epilepsy-center-locations/

Physicians

NPI Registry to find the number of neurologists / other types per hospital

https://www.cms.gov/Regulations-and-Guidance/Administrative-Simplification/NationalProvIdentStand/DataDissemination

CMS Doctor Physician Registry

https://data.cms.gov/provider-data/topics/doctors-clinicians

https://data.cms.gov/provider-data/sites/default/files/data_dictionaries/DOC_Data_Dictionary.pdf
