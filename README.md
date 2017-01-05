# timetrackio-i18n
Below is very brief explanation of new timetrackio features compared with aTimeLogger (UNFINISHED)
## Tags
New field appeared for activity - tags. User can set tags from predefined list or enter new. 
![alt text](https://raw.githubusercontent.com/zaplitny/timetrackio-i18n/master/images/image7.PNG?raw=true "Image with tags")
## Pomodoro
### Setup
Go to Settings / Pomodoro.
Most of fields are self explanatory. "Strict" pomodoro mode does not enable Break button before pomodoro duration reached
### Work in pomodoro mode
To start pomodoro enable it, go to "Activities" tab (or Today widget) and press on one of Work types - alert will appear asking if you want to start activity in default or pomodoro mode

![alt text](https://raw.githubusercontent.com/zaplitny/timetrackio-i18n/master/images/image1.PNG?raw=true "Pomodoro ask")

When started you'll see pomodoro timer and 2 buttons: Break and Reset. Pressing on Reset will restart current pomodoro immediately (e.g you were interrupted)

![alt text](https://raw.githubusercontent.com/zaplitny/timetrackio-i18n/master/images/image2.PNG?raw=true "Pomodoro work")

Pressing on Break will show you Break types and after pressing on type break starts. 
After break you can resume previous activity or start new one

![alt text](https://raw.githubusercontent.com/zaplitny/timetrackio-i18n/master/images/image3.PNG?raw=true "Pomodoro break")
### View stats
When pomodoro enabled new menu appears on More tab - "Pomodoro"
![alt text](https://raw.githubusercontent.com/zaplitny/timetrackio-i18n/master/images/image4.PNG?raw=true "Pomodoro break")
## New goal types
### Occurrence
N times a day/week/month
### Total (early version)
Setting total tracked time duration will motivate user to track time more often
## Places and geo notifications (early version)
User can create places he often visits and get notifications when he enters or leaves them. The only limitation is that accuracy is not too high as it's battery draining operation.
Place can be created from More / Places. It includes the following fields: name, exit types, enter types, notify on exit, notify on enter. Let's say user created 'House' place with notify on exit/enter checked, 'Walk' type as exit type and 'Being at home' as enter type. Then if user leaves house location he'll get notification suggesting to 'Start Walk' and when he enters house he'll get notification suggesting 'Start Being at Home'

Forgot to mention another limitation - geo notification is iOS 10 specific feature but later I'm going to implement it for iOS9 too
## Reports
### Charts


### User filters
If compare with aTimeLogger predefined filters appeared: Today, Yesterday, This Week, etc. But user can also create his own filters for quick access where types, tags and period type defined. To create custom filter press '+' on 'Reports' screen
## Watch Complications

## Useful tips
### Insert between 2 intervals
Swipe from right to left on cell on History tab and select first (green) choice - edit activity screen will appear with interval time between
### Statistics calculation setting
When activities intersect you get Activity1+ActivityB. You can override this behavior now (you can change it in Settings)
### Warning on intersection
If you save activity with interval that intersects another activity warning with suggestions will be shown (you can enable it in Settings)

## Coming later
### Calendar integration 
### Tags statistics and management (now you can only filter by tags)
### Custom field (e.g freelance rate)
### More themes
