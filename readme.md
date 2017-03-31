# REAXML database fields

## Fields

- uniqueid
- category - eg: Unit
- address - street address inc number
- suburb
- postcode
- state
- rentvalue - dollar figure with decimals (we can remove decimals)
- rentdisplay - yes/no for displaying rental value
- rentperiod - always weekly according to realestate.com.au, seems to be a waste of space
- headline - all caps ejaculation (above description)
- description - normal description
- dateavailable - date, we can do what we want for format
- inspectiontimes - typed times eg: 20-Mar-2017 05:00pm to 05:15pm
- images - 800x518px src files, typically around 6-9 of them
- agentname
- agentphone - possible multiple phone numbers, agency + mobile
- agentemail
- bedrooms
- bathrooms
- carparks
- airconditioning - boolean
- pool - boolean
- features - collection of features, see below
- pets - boolean
- furnished - boolean
- smokers - boolean
- updated - timestamp from when we added it to MODX


## Features

### Numbered

- bedrooms
- bathrooms
- ensuite
- toilet
- livingArea
- garages
- carports

### Boolean

- remoteGararge
- secureParking
- study
- dishwasher
- builtInRobes
- gym
- workshop
- rumpusRoom
- floorboards
- broadband
- payTV
- intercom
- airConditioning
- splitsystemAircon
- ductedCooling
- pool
- poolAboveGround
- poolInGround
- spa
- insideSpa
- outsideSpa
- tennisCourt
- balcony
- deck
- courtyard
- outdoorEnt
- shed
- fullyFenced
- alarmSystem

### Text

- otherFeatures
