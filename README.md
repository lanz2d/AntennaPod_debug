# AntennaPod_debug
#6598 Unable to Get to the Episodes List Container Using TalkBack Gesture
Steps to reproduce
With TalkBack turned on, go to Subscriptions>XYZ-Podcast>
Swipe right with four fingers to get to the next container on the screen
Instead of TalkBack focusing on the first item in the episode list container, like it does on the subscriptions page (focuses on the first item in the grid), TalkBack skips to the media player bar at the bottom
Expected behaviour
When the gesture to go to the next container was performed on the podcast page, TalkBack should have focus on the first item in the episode list.

Current behaviour
No response

Logs
No response


#6692 TalkBack Announces Items in the Action Menu for "Multi select" Twice
Steps to reproduce
With TalkBack turned on, go to "Subscriptions" screen or any other screen where you can select multiple items, and double tap and hold on an item, then double tap on "Multi select"
Find the unlabeled actions button at the end, and double tap on it
TalkBack's focus should be on the last item in the menu, swipe left and you'll hear the same action repeated the second time. For example, if the focus was on the "Delete" button, swiping left again will make TalkBack announce "Delete" again
Expected behaviour
When making multiple selections with TalkBack turned on, the "actions" button should have been announced as "actions button".
In the actions menu, each item should be announced only once by TalkBack, not twice.

Current behaviour
No response

Logs
No response
