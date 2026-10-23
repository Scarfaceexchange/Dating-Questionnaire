# Are We a Match?

A dating compatibility questionnaire. Any answer outside the accepted set ends it with
"We are incompatible. Good luck and God bless." Passing every question asks for a first-date
day and then shows Rashann's name and number.

- Questions, accepted answers, phone number and notification channel are in the settings block
  near the top of the script in `index.html`.
- The intro tells each person their answers are sent to Rashann. Each finish (pass or fail)
  sends a push notification through [ntfy](https://ntfy.sh) to the channel in `NTFY_TOPIC`.
- Served with GitHub Pages from the `main` branch.
