# Part 3

## How's your technical skills?

Data analysis/science requires dealing with data at scale. This will more often than not require programming to automate specific tasks or implement real-time analysis etc.

Using any language you deem fit, provide the working for the following questions:

**Question 1 (Not so bad)**

Write a function or series of functions that takes in two unsorted lists and outputs a sorted list that is their union.

# Python program to merge and sort two list
def Merge(list1, list2):
	final_list = list1 + list2
	final_list.sort()
	return(final_list)

# Driver Code
list1 = [25, 18, 9, 41, 26, 31]
list2 = [25, 45, 3, 32, 15, 20]
print(Merge(list1, list2))

**Question 2 (The good stuff)**

Our users have requested a feature that will allow them to only enter games that open and close within their chosen timeframe. For instance, they may only want to enter games that start and finish betwen 1pm and 5.30pm on a Sunday afternoon.

Write a function that takes the start and end timestamp, a list of games and returns all the games that start and finish within that timeframe. An example signature and the `games` structure is below.


Step 1. Define function in python
Step 2. Import datetime and Re 
Step 3. Compute number of minutes as time_from - time_to
Step 4. Condition : if time_from >= start_time and td_mins < mins display all game ids

def get_games_for_timeframe (time_from, time_to, available_games) 

from datetime import datetime

fmt = '%Y-%m-%d %H:%M:%S'
time_from = datetime.strptime('2016-04-06 21:26:27', fmt)
time_to = datetime.strptime('2016-04-07 09:06:02', fmt)

if time_from > time_to:
    td = time_from - time_to
else:
    td = time_to - time_from
td_mins = int(round(td.total_seconds() / 60))


if time_from >= start_time and td_mins < mins

print(id)

else

print(games not available)

```
// Example signature
fn get_games_for_timeframe (time_from, time_to, available_games)
```

```
// Example data
games = [
    {
        'id': 1,
        'start_time': '2018-02-01 12:30:00',
        'mins': 90
    },
    {
        'id': 24,
        'start_time': '2018-02-01 14:45:00',
        'mins': 75
    },
    {
        'id': 32,
        'start_time': '2018-02-01 15:00:00',
        'mins': 30
    }
]
```
