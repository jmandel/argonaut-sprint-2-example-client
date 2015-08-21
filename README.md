## Quick start example app

Download this repo and run a static web server to host this app. (Note that you
don't need to use our web server; you can use any web server you want, as long
as content is hosted at http://localhost:8000/fhir-app).

    git clone https://github.com/jmandel/argonaut-sprint-2-example-client
    cd argonaut-sprint-2-example-client
    npm install
    npm run serve


Then launch a local browser and open
[http://localhost:8000/fhir-app/launch.html](http://localhost:8000/fhir-app/launch.html).

You should be directed to approve access, and upon successful completion you'll
see a JSON patient bundle response in your browser.
