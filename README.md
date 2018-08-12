# allegro-interview-postman

Repositiory of postman collection for { JSON : Placeholder }.

The idea behind was to create full end2end test of endpoints of jsonplaceholder using Postman. 
As JSONPlaceholder is a simple fake REST API for testing and resources are not really created on the server (but only are faked as if) I decided to show two solutions of this task.
First one is simple to check, but part of tests fails due to JSONPlaceholder 'fake' adding and changing posts.
Second one requaires installing local JSONPlaceholder (shor information below).

I added two env files - one with basic env and the other one with local env.

To set local env.:
1. npm install -g json-server
2. downloand db.jso file from this repository 
3. json-server --watch db.json
