# Functional Requirements

## User

### Add Observation

- Create a new observation
- Automatically assign an observation ID
- Add one or more photographs
- Record species identification, if known
- Record observation date and time
- Record observation location
- Record visited plant
- Record sex, if identifiable
- Record life stage
- Record weather conditions
- Record observed behaviour
- Record identification notes
- Record identification confidence

### View Observation

- View observation details
- View associated photographs
- View species information
- Search by scientific name
- Search by common name
- Filter observations
- Sort observations
- Edit observation
- Delete observation
- Export observation

### Image Search

- Upload image
- Search existing observations
- Return possible matches
- Display similarity/confidence

### Identification

- Confirm an identification
- Correct an identification
- Manually assign a species
- Record identification confidence

## Frontend

### Dashboard

- Display a random observation
- Display recently added or edited observations
- Display species observed around this date
- Provide links to observation details

## BACKEND

### Observations
- create observation
- get observation by ID
- list observations
- edit observation
- delete observation
- filter by species/date/location/family/sex/life stage
- sort results
### Species / Taxonomy
- store species
- associate observation with species
- search by scientific name
- search by common name
- store family/genus/order
- allow incomplete identification
  e.g- family known, species unknown
### Photographs
- receive upload
- validate file type/size
- store file
- associate photo with observation
- get photographs for an observation
- delete/replace photograph
### Image Search
- receive image
- generate embedding
- compare with existing embeddings
- sort by similarity
- return possible matches
- apply minimum similarity threshold
### Dashboard / Homepage
- get latest observation
- get random observation
- get species observed around this date
- return summary/statistics
### Export
- export observation
- optionally export filtered set
### Validation
- validate required fields
- validate dates
- validate confidence level
- prevent invalid references