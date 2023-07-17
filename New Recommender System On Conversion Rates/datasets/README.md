# Marketing Events Dataset
The `marketing_events` dataset recovers data about the calendar of marketing events for 2020. Here's the content: 
- `name` — the name of the marketing event
- `regions` — regions where the ad campaign will be held
- `start_dt` — campaign start date
- `finish_dt` — campaign end date

# New Users Dataset
The `new_users` dataset records all users who signed up in the online store from December 7 to 23, 2020. Here's the structure:
- `user_id`/
- `first_date` — sign-up date
- `region`
- `device` — a device used to sign up

# User Activities (events) Dataset
The `events` dataset record all events of the new users from December 7, 2020, to January 1, 2021. Here's the structure:
- `user_id`
- `event_dt` — event date and time
- `event_name` — event type name
- `details` — additional data on the event (for instance, the order total in USD for `purchase` events)

# AB Participants Dataset
The `ab_participants` table contains list of users joined as test participants.
- `user_id`
- `ab_test` — test name
- `group` — the test group the user belonged to
