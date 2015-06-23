# Framework Development Test

## Task:

Create an app which allows the user to search Foursquare results and “like” them.   

The app should not concern itself with login process or long term persistence of “likes” at this stage.  

The test was designed to be completed in Ruby on Rails but the candidate can use another appropriate framework, within the context of the skill set we are hiring for.

There should be test coverage provided.

For the purposes of the test, just use a hard coded centre point for the location co-ordinates of the Foursquare lookup. 

The candidate should generate their own CLIENT_ID/CLIENT_SECRET from the Foursquare API service or request one from us since it cannot be published publicly on Github.

```ruby
CLIENT_ID = "GETYOUROWN!"
CLIENT_SECRET = "GETYOUROWN!"
```


### Features

* It should be possible to search for places from Foursquare  
* I should see a list of results from Foursquare  
* It should be possible to “like” items from Foursquare  
* It should be possible to remove a “liked” item from my list of “likes”  
* It should not cache results data from Foursquare locally - should reload items from source  
* It should not persist to the database at present  

### Notes:

CSS, while appreciated is not at this time the purpose of the test, so a non-customised framework layout is acceptable.

### UX

Consideration or discussion of front end UX implementation is a bonus.







