## requirements
pip3 install cloudscraper readchar requests pwinput

## activate venv
source venv/bin/activate

## to run
python3 ./example.py

## the session.json file
watch out!
I trashed it and had to reinstall from skratch

## fetcher package
its working and returning heartrate data on Feb 8th
it imports util which has all the magic in it from the example.py file
the whole thing needs to be straightened out into reasonable file structure


## logging in 
I had to hand type email and password

in the fetcher package I copied over the session.json file 
as pwinput was complaining about me entering the password.

I think this will breakdown when the session file gets invalidated.
