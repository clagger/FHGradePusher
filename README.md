# FHGradePusher
pushes new grades from FH Joanneums Actions page to a specific Pushbullet Channel or device

Prerequisites:
- empty grades.csv file in same folder as the script
- FH Joanneum Account
- Pushbullet Account (and app for mobile push notifications)

How to configure:
- Configure USERNAME, PASSWORD, DATA_URL, API_KEY and CHANNEL variables
- let script run in a scheduler on a server or raspberry pi (e.g. cronjob with */10 * * * * python3 ~/grade_parser.py)
