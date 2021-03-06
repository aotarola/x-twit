# x-twit

## Demo Walkthrough

### Non-cached version

![video walkthrough](x-twit.gif)

### Cached version

![video walkthrough](x-twit-cached.gif)

## Time Spent: 14 hours

## Stories implemented

- [x] User can sign in to Twitter using OAuth login

- [x] User can view the tweets from their home timeline

  - [x] User should be displayed the username, name, and body for each tweet
  - [x] User should be displayed the relative timestamp for each tweet "8m", "7h"
  - [x] User can view more tweets as they scroll with [infinite pagination](http://guides.codepath.com/android/Endless-Scrolling-with-AdapterViews)

- [x] User can compose a new tweet

  - [x] User can click a “Compose” icon in the Action Bar on the top right
  - [x] User can then enter a new tweet and post this to twitter
  - [x] User is taken back to home timeline with new tweet visible in timeline


## Optional stories:

- [x] **Advanced**: While composing a tweet, user can see a character counter with characters remaining for tweet out of 140
- [x] **Advanced**: Links in tweets are clickable and will launch the web browser (see [autolink](http://guides.codepath.com/android/Working-with-the-TextView#autolinking-urls))
- [x] **Advanced**: User can refresh tweets timeline by [pulling down](http://guides.codepath.com/android/Implementing-Pull-to-Refresh-Guide) to refresh (i.e pull-to-refresh)
- [x] **Advanced**: User can open the twitter app offline and see last loaded tweets

  - [x] **Advanced**: Tweets are [persisted into sqlite](http://guides.codepath.com/android/ActiveAndroid-Guide) and can be displayed from the local DB

- [x] **Advanced**: User can tap a tweet to display a "detailed" view of that tweet
- [x] **Advanced**: Improve the user interface and theme the app to feel "twitter branded"
- [ ] **Bonus**: User can see embedded image media within the tweet detail view
- [x] **Bonus**: Compose activity is replaced with a [modal overlay](http://guides.codepath.com/android/Using-DialogFragment)
