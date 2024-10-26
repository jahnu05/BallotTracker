# Election Database Management System

## Commands

### 1. Insert (Administrator)
- Insert Voter: `insertVoter()`
- Log Event: `createEvent()`
- Create New Station: `insertStation()`
- Log Party: `insertParty()`
- Log Candidate: `insertCandidate()`
- Insert Campaign Finance: `insertCampaignFinance()`
- Insert Election Official: `insertOfficial()`
- Insert Historical Election Data: `insertHistoricalElectionData()`
- Insert Records: `insertRecords()`
- Insert Candidate into ballot: `insertCandidateToList()`

### 2. Delete (Administrator)
- Delete Voter: `deleteVoter()`
- Delete Event: `deleteEvent()`
- Delete Station: `deleteStation()`
- Delete Party: `deleteParty()`
- Delete Candidate: `deleteCandidate()`
- Delete Election Official: `deleteOfficial()`

### 3. Update (Administrator)
- Update Voter: `updateVoter()`
- Update Event: `updateEvent()`
- Update Station: `updateStation()`
- Update Party: `updateParty()`
- Update Candidate: `updateCandidate()`
- Update Election Official: `updateOfficial()`
- Update Historical Election Data: `updateHistoricalElectionData()`
- Update Voter Status: `updateVoterstatus()`
- Update Demographic Data: `updateDemographicData()`

### 4. Sort (Administrator, User)
- Sort Voters by Age: `sortVoter()`
- Sort Voters by Income: `sortVotersOnIncome()`

### 5. Get Poll Percentage Based on Social Tendencies (Administrator, User)
- Get Poll Percentage by Age: `Get_PP_By_Age()`
- Get Poll Percentage by Gender: `Get_PP_By_Gender()`
- Get Poll Percentage by Income: `Get_PP_By_Income()`

### 6. Aggregate (Administrator, User)
- Total voters participated in an event: `totalvoters()`
- Average of campaign fund: `avgfund()`

### 7. Project (Administrator, User)
- Voter Contact Details: `voterContactInfo()`
- Candidates Information: `candidatesInfo()`
- Voter Polling Stations: `voterPollingStations()`

### 8. Search (Administrator, User)
- Polling station assigned for a Voter: `station_for_voter()`
- Details of a Voter: `voter_by_id()`
- Candidate representing a Party: `candidate_by_party()`
- Polling Station based on Address: `station_by_address()`

### 9. Add Access Key (Administrator)
Administrators can add access to other Administrators with a unique access key.

### 10. Get Report (Administrator, User)
- Generate Report: `Generate_election_Report()` - Analyzing the relation between Election result and Campaign Finance.
