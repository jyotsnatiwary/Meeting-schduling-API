# meetingsapiappointy
A Meeting Scheduling API  
- An API made with Go and MongoDB
## Requirements
* MongoDB
* Go
## Features
Sticks to the given constraint and uses only standard lib

## API

### /meetings
* POST : Schedule a new meeting

### /meeting/\<id here>
* GET : Get meeting using the id
 
### /meetings?starttime=\<start time>&endtime=\<endtime>  
**Please note this function uses "starttime" and "endtime" instead of "start" and "end" in the url.**
* GET: Returns an array of meetings in JSON format that are within the given certain time range

