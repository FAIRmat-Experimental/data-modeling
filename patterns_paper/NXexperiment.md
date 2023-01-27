
```yaml
(NXexperiment):
	(NXentry):
		title:
		start_time(NX_DATE_TIME):
			doc: Start datetime of the measurement.
		end_time(NX_DATE_TIME):
			exists: recommended
			doc: Stop datetime of the measurement
		definition:
		(NXuser):
			name:
				doc: Name of the user
			affiliation:
				exists: recommended
				doc: |
					Name of the affiliation of the user at the
					point in time when 
					the experiment was performed.
			address:
				exists: recommended
				doc: |
					Full address of the user's affiliation,
					i.e. street, street number, zip, city, country
			email:
				doc: Email address of the user.
			digital_id(NX_CHAR):
				exists: recommended
				doc: Digital id of the operatore, e.g. orcid.
		(NXsample):
			sample_id(NX_CHAR):
				doc: A unique sample id
		(NXmeasurement):
		(NXinstrument):
		data(NXdata):
```

#area-b #nexus #general-patterns 