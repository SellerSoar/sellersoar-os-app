# SellerSoar OS

The web front end of the SellerSoar OS: tasks that people and agents work on together.

This repository holds application code only. It contains no client data. Everything the app shows
is read from the database after a team member signs in, and row-level security refuses anyone who
is not on the team list. The key in `index.html` is a publishable key, designed to be public.
