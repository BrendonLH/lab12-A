# lab12-A
readme for lab 12-a
# OAuth Comparative Analysis

## OAuth Provider Name 

* Google Auth

### Research Conducted By: 
Diane Stephani
Jonathon Lee
Ryan Geddes
Brendon Hampton

### Overall Score and Comments
#### Score (Out of 10): 7
#### General Comments
We spent alot of time reading the wrong docs. We managed to get everything just about done except for the last part of getting a token back. We just ran out of time after we realized what we were missing.

#### Pros
* We All worked great together and all had great input
* Setting up the initial google credentials was a breeze

#### Cons
* The dropdown on where to find the right docs was too small
* Staring at a screen hurts our heads

### Ratings and Reviews
#### Documentation
* The overall process was pretty smooth other than our being stuck. 
* As a team we understand the concept and what we need to do and now definitly know where to look.

#### Systems Requirements
Above and beyond 'node' and 'linux', what dependencies or core requirements exist for this framework?  Can it play at AWS/Heroku?  Does it require a certain database?
we originally used Ajax but then went with a simple POST so only library we needed was the google platform. 

#### Ramp-Up Projections
How long would/should it take a team of mid-junior developers to become productive?
We were very productive to the point where we probably should have taken an extra break or so. 

#### Community Support and Adoption levels
How popular is this framework? What big companies are running on it? How is it "seen" in the general JS community?  Is there an active community of developers supporting and growing it?

There is a lot of docs outside of the google docs so we imagine it is used alot.  




### Links and Resources
* [framework](http://xyz.com)
* [docs](https://developers.google.com/identity/protocols/oauth2/javascript-implicit-flow)
* [examples/tutorials](https://medium.com/@bogna.ka/integrating-google-oauth-with-express-application-f8a4a2cf3fee)

### Code Demos
* [live/running application](http://xyz.com)
* [code repository](https://github.com/ryangeddes-401-advanced-javascript/auth-server/pull/1)

### Operating Instructions
If someone were to download your repo (above), what steps do they need to take to run the application
setting up Auth 2.0 for google

to just sign in, you would need a google account. Then npm I followed by running the server and then clicking the link to connect google. 

1. console.developers.google.com 
    1. Create Creadentials
        1. select Oauth client ID
    2. navigate to credentials tab
    3. name app
    4. initial URI = whatever server your using
    5. Authorized redirect URLS = your server with oauth path
3. get client id and secret id from credentials form
4. bring in 1 libraries ( google api client platform js)
