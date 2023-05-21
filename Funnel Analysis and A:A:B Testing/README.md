# Funnel Analysis and A/A/B Testing

Working at a startup that sells food products, we need to investigate user behavior for the company's app.
The designers would like to change the fonts for the entire app, but the managers are afraid the users might find the new design intimidating. They decide to make a decision based on the results of an A/A/B test.
First, we study the sales funnel, find out how users reach the purchase stage, how many users actually make it to this stage, how many get stuck at previous stages and which stages in particular.
Then, we look at the results of an A/A/B test: The users are split into three groups: two control groups get the old fonts and one test group gets the new ones.
The goal of this project is to find out which set of fonts produces better results.

Description of the data:

logs_exp_us table contains log entries, each of them is a user action or an event.
- EventName — event name
- DeviceIDHash — unique user identifier
- EventTimestamp — event time
- ExpId — experiment number: 246 and 247 are the control groups, 248 is the test group
