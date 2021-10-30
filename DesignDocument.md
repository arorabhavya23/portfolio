# Design Document
## Spring boot Angular Application to display my achievements

> This App would be a visually appealing document based portfolio

> Will have all the certificates and Awards won by me with the certificate as a copy attached to it and a link to redirect to issuing authority website.(where applicable)

> It would be developed on a timeline based design with most recent at top and going down to all previous events 

> To start with will include all the academic achievements with possible photographs of events.

> will add more personal details on the go.

> Option to dynamically add details with date, and it gets appended automatically to the timeline deciding the location

> Save all the details on backend with images and their URLs where applicable 

> Take input from Backed server and render that json to generate the webpage 

> To begin with have a static JSON with Just Past year events 

> Have option to add markup or ascii doc styling features to enable bullet lines or any other basic styling features

## Designs and View

* Landing page to have a Static content with a photograph.
* Static content to have details like of my Cover letter and Hobbies
* On scroll Image should be fixed to one corner either right or left based on view 
  * Should lead to timeline can have blue color gradient for a starter and can see further.
* Have an alternate view of text and Images 
  * Add random images based on a criteria filled while inserting the details of event/award/achievement
* Can have an option to click and view more details(might clash with view certificate check implementations)


## Data And Backend Configs

* Have a section to take input of event/award/achievement
  * Take Date (Required)
  * Event Category (Required)
  * Image/PDF of certificate (Required)
  * Personal Event Image (Required)
* Based on the input JSon Render the Timeline on frontend 
* If Image is not available get one from the Category 
* One Endpoint to take input 
* One to provide output 
* One to provide the files(ie the images and certificates)


## Future Scope

* Add options for blogs 
* Link projects that are completed 
* Link to OSS contributions 
* Link to published papers
* Option to subscribe to new letters
