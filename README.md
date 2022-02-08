# dashboard for labour flow in france work zones
 Intra-regional and inter-regional labor flows over the last 20 or so years
 
The app is too large to be run by Heroku (Slug size 1.1G (max is 500M)

Commands for Heroku by Voila:

Launch local : voila MyApp.ipynb

heroku login

heroku create

heroku apps:rename dashboard-for-labour-flow --app ....

Clone from Desktop git

heroku git:remote -a dashboard-for-labour-flow

git push heroku main 

heroku open

To destroy : heroku apps:destroy

Debug : heroku logs -n 200   
