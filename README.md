## Set status

1. Edit the `status.json` file.
2. If Learpoint is fully operational, set `fullyOperational` to `true`, otherwise `false`.
3. Set `notFullyOperationalMessage` to a number that corresponds to one of the `messages`. (You can add a new item in the `messages` if none of the existing are appropriate.
4. Commit and push.



## Add an incident

1. Edit the `incidents.json` file.
2. Add an incident item in the array.
3. Set `major` to `true` if it was a major incident. See below.
4. Commit and push.



## How to decide if incident was major

The `major` property of an incident will only affect the coloring in the calendar view on the status page. Major incidents are red and partial incidents are orange.

There are several factor to take into account:
1. Duration of incident.
2. Number of users affected.
3. Number of sub systems affected.
4. Severety of the problem.

For each incident, take all factors into account and try to make a judgement. Be conservative and use a low bar for major incidents. If you are uncertain, mark it as major.