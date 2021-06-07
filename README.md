# Contact-Tracing

## Problem Definition
Explore and extrapolate any relationship between social distancing and clinical risk. Medical literature and science of spread of communicable diseases provides support for social distancing regulations designed to help minimise the spread of Covid-19 viruses. Tracking compliance in the population has recently become subject to socially controllable,uncontrollable and legal factors.The ubiquitous nature of the users mobile behaviour suggest that contact tracing via hand held devices might be a non invasive method for guiding compliance. This project attempts to answer some questions about relationships between social distancing and clinical risk by aggregating ICU patient data synthesized from real life scenarios combined with randomized geolocation and simulated cellular RF/Air interface parameters from the mobile devices. Lets see what we might find!


## Input
Input: Mimic iv dataset, ontologies: ICD9,ICD10,SNOMED,LOINC,CPT codes, SAPS score, National Early Warning System (NEWS) Score,provider , Simulated RF Air interface parameters (mobile rssi txpower,downlink rxlev,aggregate dataset made up of structured and unstructured data comprising several features engineered from the two intersecting domains.


## Algorithm
Algorithm: R,feature engineering,Multinomial regression, NLP,tokenization, word2vec, link budget analysis,postgress database


## Outout
Output: Classification of patient/users based on the risk level
Statistical significant variables and comfounding factors.
Relationship and pattern  visuals.
