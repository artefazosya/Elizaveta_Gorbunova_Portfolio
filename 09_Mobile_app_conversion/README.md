# Mobile app conversion

This project was completed during `Yandex.Practicum Data Analysis` professional program. 

The project is dedicated to the following themes:
- `Making Business Decisions Based on Data`
- `How to tell a story using Data`
- `Data collection and storage`
- `Business Analytics`

**Key points**: sales funnel, conversion, A/B test, user behaviour.

**Libraries used**: pandas, plotly, seaborn, scipy.

## Project's goal<a id='goal'></a>

We work at a startup that **sells food products**. 
We need to investigate **user behavior** for the **company’s app** and provide recommendations on **conversion and results of tha A/B test**.

### We are going to:
1. Study the sales funnel:
    - Find out how users reach the purchase stage. 
    - How many users actually make it to this stage? 
    - How many get stuck at previous stages? Which stages in particular?
2. Look at the results of an A/A/B test:
    - The designers would like to change the fonts for the entire app, but the managers are afraid the users might find the new design intimidating. They decide to make a decision based on the results of an A/A/B test. The users are split into three groups: two control groups get the old fonts and one test group gets the new ones.     
3. Find out which set of fonts produces better results.

### We have the following data:
Each log entry is a user action or an event.
- `EventName` — event name
- `DeviceIDHash` — unique user identifier
- `EventTimestamp` — event time
- `ExpId` — experiment number: 246 and 247 are the control groups, 248 is the test group