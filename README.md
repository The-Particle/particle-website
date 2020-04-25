# particle-website
View at: https://the-particle.github.io

### Run Locally
* Clone the repo to your local environment: `git clone https://github.com/The-Particle/particle-website.git`
* In your terminal switch to the root directory for clone repo.
* Run `hugo server -D` to start a local server.
* Go to http://localhost:1313 to view this site.
* Saving changes to the source code will automatically update in the browser.

### HUGO is used to build this site
* data/homepage.yml - alter this file as a starting point for updating the webpage content
* static - location of webpage static content (e.g. images, etc)

### Building and Deploying website changes
* Make sure to push all changes first
* Delete the `public\` folder if it was generated
* Finally run the deploy script
```bash
./deploy.sh "OPTIONAL COMMIT COMMENT"
```

Hooray! If all went well the site changes will be up in a few minutes at https://the-particle.github.io