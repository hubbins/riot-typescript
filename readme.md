Install riot compiler
    npm install riot -g

Install typescript
    npm install typescript -g

Install typescript-simple
    npm install typescript-simple -g

Create a "tag" folder and add a .tag file.

Compile all the tag files into "tags.js" in the dist folder.  Or watch the tag folder for changes.
    riot --type typescript tag dist/tags.js
    riot -w --type typescript tag dist/tags.js

Install http-server
    npm install http-server -g

Run http-server and browse to 127.0.0.1:8080
