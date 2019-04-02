
## commands ran to solve this 

docker container run -p 80:4000 -v E:\\Users\Rob\src\udemy-docker-mastery\dockerfile-sample-2-assignment-2:/site bretfisher/jekyll-serve

## Notes
* Note how the volume mount had to be done in order to satisfy Windows ... this does work and I was able to change files and see those changes reflected in the browser.
* Also remember to clear the web browser cache (open Chrome dev tools) in order to see changes like this. Case in point, I had been running nginx and on a certain port for localhost so when I first opened this project the cached version was all that displayed and my jekyll website never displayed until I opened the Dev Tools and forced a refresh.

