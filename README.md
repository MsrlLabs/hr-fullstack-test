# hr-fullstack-test

## Full Stack Technical Test: Scrum Poker
 
 
Scenario: Imagine a team of developers in the conference room doing their sprint planning meeting.
 
### Functional Requirements
 
-	User can login with his e-mail address. no validation required.
-	User can choose a story from the following list of items, which would then become the “Active Story”. At any moment there is only one “Active Story" in the system.
    * implement chat feature
    * add KYC UI to back office
    * create FX market stop order
-	Users can assign a story point estimate to the current story from the following selection:
    * 1
    * 2
    * 3
    * 5
    * 8
    * 13
    * no_idea,
    * resign.
-	After all logged-in users have given story points to the current story, all the story points given will be revealed *without pressing browser reload* (e.g. A gave 2 points, B gave 3 points etc.) 
-	After that any user can choose a new “Active Story”.
 
### Non-Functional Requirements
 
-	*Java Spring Boot*, database optional, i.e. you can store everything in hash maps
-	*ReactJS* based frontend, additional technologies/frameworks optional
-	A README good enough that tells us how to start your app or deploy on any cloud
-	A big plus to use any push mechanism to notify frontend of changes, e.g. HTTP SSE, websockets (instead of polling http requests)
