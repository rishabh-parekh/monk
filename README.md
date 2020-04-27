# monk

Hugo Site for Monk Yogurt

# Instructions on how to edit the content

## Quick Edit

1. The data/homepage.yml has all the content for various sections. Use that to edit to content in github, commit. 
2. As soon as you commit, the Github Action (check the actions tab), will kickoff the new build. 
3. If the build is successful, you will see the new content at https://rishabh-parekh.github.io/monk/#/
4. Add new images in static/images
5. Some showcase images are in static/images/showcase. 


## Longer way to edit. 

1. Install hugo using `brew install hugo`
2. Git clone this repo e.g. 

```` 
    git clone https://github.com/rishabh-parekh/monk.git`
    cd monk
```` 
3. Start `hugo`
     
   `hugo serve`

4. Open up localhost:1313/monk to see the website locally. 

5. Make local changes in `code` and when you are ready `git commit -am "Changes by XYZ"` and `git push origin master`

6. The build will automatically kick off. 

