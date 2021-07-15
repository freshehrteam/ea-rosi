# SNEE Advance Care planning

openEHR models for the SNEE Advance Care planning project, incorporating ReSPECT, End of life plan, Advance care planning and About me.

You can also view the templates...

- [About Me](https://tools.openehr.org/designer/#/viewer/shared/Pz9zaGFyZWRJZD0xJDk3YjRhZTY3YmU5ZjRlMmQ4MDg5YTZjMmMwZTBlNjQw)
- [Anticipatory Care Information](https://tools.openehr.org/designer/#/viewer/shared/Pz9zaGFyZWRJZD0xJDkyYzcyYjhkOWMzNTRiZWE4YjJjNWE1Njg0YTBkOTFi)
- [End of Life Care plan](https://tools.openehr.org/designer/#/viewer/shared/Pz9zaGFyZWRJZD0xJDM0ZWQ5Y2YzZjU0MDQ0NTU4MDVjNTdmMDliZGZhZDli)
- [ReSPECT](https://tools.openehr.org/designer/#/viewer/shared/Pz9zaGFyZWRJZD0xJDdlZDc0YjdmNTlhYTRkZTZhNGVlNWZiZTczNjNlYjc3)

All artefacts are CC-BY-SA 4.0 licensed and will also be available from the [Apperta CKM](https://ckm.apperta.org/ckm/projects/1051.61.57)


## Data model coverage
		
### About me		
		Document type
		Author
		Start time
		
	About me	
		What is most important to me
		People who are important to me
		How I communicate and how to communicate with me
		Please do and please don't
		My health
		How and when to support me
		Also worth knowing about me
		
	Events timeline	
		Event time
		Event description
		
	Communication	
		Status
		Notes
		Preferred language
		Intepreter needs
		  Interpreter needed
		  Interpreter not needed
		
	Lasting power of attorney	
		Type
		Ref number
		Certificate location
		Certificate attachment
		Representative details
		
		
## Advance care Planning composition	
		
	Communication	
		Status
		Notes
		Preferred language
		Interpreter needs
		
	Lasting pwer of attorney	
		Type
		Ref number
		Certificate location
		Certificate attachment
		Repsresentative details
		
	Advance decision to refuse treatment	
		Status
		Description
		Location
		Attachment
		
	Advance statement	
		Status
		Description
		Location
		Attachment
		
	GP Allergies	
		Causative agent
		Date 
		Manifestation
		
		
	Specific preferences	
		Spiritual and cultural needs
		Wishes after death
		Dependents and pets
		Other
		
	Living arrangements	
		Usual residence
		Household composition
		Other person in household
		
	Risk and abilities	
		Able to summon help?
		Able to recognise risk?
		Cognition
		Vision
		Hearing
		Mobility
		
### End of Life Care Plan composition	
		
	Plan management	Plan status
		Date started
		Date closed
		Reason closed
		Consent status
		Mental capacity
		Place of death
		
	CPR decision	
		Clinical focus
		CPR Recommendation
		Date of CPR decision
		CPR documentation
		Documentation attachment
		Patient awareneess
		Family awareness
		Comment on awareness
		
	Primary diagnosis	
		Diagnosis
		Description
		
	Prognosis	
		GSF scale
		Patient awareness
		Awreness notes
		
	Karnofsky scale	
	Clinical Frailty scale	
		
	Co-morbidities	
	Other relevant clinical issues	
		
	Preferred place of care /death	
		
	Just-in-time medications	
		Status
		Description
		On oxygen?
		Specific medicaiton
		
		Authority to administer meds
		Date authorised
		
	Emergency contacts	
		Name
		Role/relationships
		Tel number
		Other details
		
	Funding	
		DS1500 status
		Fast-track funding status
		
		
### ReSPECT composition	
		
	Shared understanding of condition	
	Details of other planning documents	
	Has Legal Welfare proxy?  	
		
	What matters to me?	
	Clinical focus	
	Clinical guidance	
	CPR recommendation	
		
	Mental capacity	
	Who involved in making the plan	
	Clinician 'signatures'	
		Clinician name
		GMC/NMC/HCPC
		Grade/speciality
		Date reviewed
	Emergency contacts	
		Name
		Role/relationships
		Tel number
		Other details
		
	Review	
		Clinican name
		GMC/NMC/HCPC
		Grade/speciality
		Date reviewed
