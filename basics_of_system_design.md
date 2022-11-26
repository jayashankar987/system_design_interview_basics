### An Interviewer will ask one liner every time to design 
#### say : Design Realtime Live View for a Hotel (How many are actually watcing that Hotel)

#### [IMP] First 30 seconds gather more information:
* Ask the interviewer if he is expecting the design only for Mobile, Tablet, TV, Wear or Auto.

  `NOTE: Do not assume interviewer will know about API, or all below points, 
   This is the reason most of them loose lead in interviews`

* If Mobile: should it be supporting for portrait / landscape
* Should it Support Multi Language
* Should it Support RTL
* Is it user specific (premium / free user)
* Auth Token to identify if expired and does it support refresh token or Logout (Error Handling)
* Explain the architecture you are going to follow MVI, MVVM, MVP which best suites based on the requirement
* Understand if there is any service requirements, APIs and Touch base of what is needed
* What is the API, can I get exposure to API (Rest?, json)
    GET https://host/current_live (parameters expected)
* How much data needs to be stored, does it need Clean service (WorkManager to clear old data)
* Does it need pagination
* Check if Mobile is on wifi / mobile network and then identify polling frequency
* Should it support offline and online both?
* What Database and schema say (Room, SQLDelight, ObjectBox, Realm)
* [Bonus]: How are we going to collect data (Analytics) for how the feature is performing