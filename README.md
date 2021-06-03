# Contact-Tracing
Explore and extrapolate any relationship between social distancing and clinical risk. Medical literature and science of spread of communicable diseases provides support for social distancing regulation to help minimise the spread of Covid-19 viruses. Tracking compliance in the population has recently become subject to socially controllable,uncontrollable and legal factors.The  The ubiquitous nature of the user`s mobile behaviour suggest that contact tracing via hand held devices might be a non invasive method of guiding compliance. This project attempts to answer the some questions about relationships between social distancing and clinical risk by aggregating ICU patient data synthesized from real life scenarios combined with randomized geolocation and simulated cellular RF AIR interface parameters of the mobile devices. Let`s see what we might find!

Input: Mimic iv dataset, ontologies: ICD9,ICD10,SNOMED,LOINC,CPT codes, SAPS score, National Early Warning System (NEWS) Score,provider , Simulated RF Air interface parameters (mobile rssi txpower,downlink rxlev,aggregate dataset made up of structured and unstructured data comprising several features engineered from the two intersecting domains.

Algorithm: R,feature engineering,Multinomial regression, NLP,tokenization, word2vec, link budget analysis,postgress database

Output: Classification of patient/users based on the risk level
Statistical significant variables and comfounding factors.
Relationship and pattern  visuals.
