ON DECK
- [ ] handle posts with blank titles gracefully. Tumblr
- [ ] check the submitted blog url to make sure it returns a 200 - use Ajax to display this? (jacob suggested a better method)
- [ ] stop hotlinking to hacker school and save a copy of the file locally (waiting for new profile pics)
- [ ] implement South http://south.readthedocs.org/en/latest/tutorial/index.html
- [ ] migrate form fields to proper data types (e.g. URLField)
- [ ] redirect /log_in if they're already logged in
- [ ] strip newlines from blog post titles
- handle the wrong URL submitted more gracefully with ajax?
- figure out how to surface error messages from the scraper


ON DECK: PROFILES
- [ ] create profile views /profile/293
- [ ] create edit profile view /profile/edit
- [ ] have "edit" button only appear on your own profile
- [ ] expose blog field in the user profile & edit views
- [ ] make a public profile view (aka what another user sees when they view your profile)
- [ ] redirect /profile to the profile of the logged-in user

MAYBE
- [ ] add responsive layouts with bootstrap?
- [ ] Add GA and/or statsd
- [ ] Add flash messaging (this might still work in 1.5 https://groups.google.com/forum/?fromgroups=#!topic/django-users/1YtRSukvviE) Also useful https://docs.djangoproject.com/en/dev/ref/contrib/messages/

DONE
- [T] Fix "Welcome Firstname!" bug - template processors are probably the issues here
- [T] Redirect /login to /log_in
- [T] Link to users' Hacker School profiles
- [T] Fix 500 error by adding ALLOWED_HOSTS
- [T] figure out how to handle USER, HOST, AWS_STORAGE_BUCKET_NAME in settings.py

