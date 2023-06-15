A/B Testing Project
We recently joined a new company operating an international online store, and we have taken on an important analytical task left incomplete by our predecessor. They had initiated an A/B test called recommender_system_test to evaluate the impact of an improved recommendation system.

The objective of this A/B test was to measure improvements in user conversion within 14 days of sign-up, specifically focusing on product page views, product cart views, and purchases. Our goal was to achieve a minimum 10% increase in conversion at each stage of the funnel: product_page → product_cart → purchase. The test was conducted from 2020-12-07 to 2021-01-01, with new user enrollment closing on 2020-12-21. We targeted 15% of new users from the EU region, and the expected number of test participants was 6000.

Our project's objective is to ensure the test was properly executed, analyze the results thoroughly, and provide valuable recommendations for future tests.

Description of the data
Structure of ab_project_marketing_events_us.csv:

name — the name of the marketing event
regions — regions where the ad campaign will be held
start_dt — campaign start date
finish_dt — campaign end date
Structure of final_ab_new_users_upd.csv:

user_id
first_date — sign-up date
region
device — device used to sign up
Structure of final_ab_events_upd.csv:

user_id
event_dt — event date and time
event_name — event type name
details — additional data on the event (for instance, the order total in USD for purchase events)
Structure of final_ab_participants_upd.csv:

user_id
ab_test — test name
group — the test group the user belonged to
