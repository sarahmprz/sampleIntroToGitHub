## Sample for 'Intro to GitHub' Workshop - MaptimeYVR

This is a sample built for the 'Intro to GitHub' session for [MaptimeYVR](https://twitter.com/maptimeYVR) held on Tuesday Feb. 17, 2015  
[Slides for this talk](http://www.amreldib.com/slides/introToGitHub/#/).

### Goal of this exercise

Learn how to:  
- Fork, commit, and submit a pull request on a Git repo.  
- Use the gh-pages branch to host websites on GitHub.  

### Background

The [published site](http://www.amreldib.com/sampleIntroToGitHub/) is a simple map that loads one Geojson file for each user/contributor that includes some points of interest.  
Each user will fork the main repo, add a folder for themself, point to that folder in the main Index.html file and submit a pull request.  

### Resources

- [Get Lat Lon](http://dbsgeo.com/latlon/)  
- [Color hex codes](http://www.color-hex.com/)

### Steps

- Fork this repo.  
- Use the GitHub client ([Windows](https://windows.github.com/) or [Mac](https://mac.github.com/)) to clone the files to your machine.  
- Add a folder with your username. Add a geojson file named 'locations'.  
- Add a point (or more) in the file with properties 'name', 'color' and 'user'.  
- Modify Index.html to add the folder name to the array named 'users'.  
- Commit changes.  
- Sync repo with GitHub.  
- Check changes by visiting the published page at `http://<username>.github.io/sampleIntoToGitHub`  
- Submit pull request.  
