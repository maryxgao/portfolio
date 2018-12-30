# portfolio
Personal portfolio website

Instructions provided by powerhouseofthecell:

make sure you have git, python3, pip3, and django (that order works well)

1. Create a Github repository and clone to your machine
2. Go into that repository
3. django-admin startproject projectname
4. mv the root project directory to projectname.old
5. copy all of the contents of projectname.old to the current directory
6. rm projectname.old
7. move our .html, .js, .css, files into their corresponding static/ || templates/ directories
8. edit projectname/settings.py's ALLOWED_HOSTS, INSTALLED_APPS
9. add views.py to projectname/.
10. add a view to this views.py file
11. edit urls.py to direct us to this view
12. edit .html files to reflect a new static config
13. edit settings.py to allow for heroku static files
14. add a Procfile with web: python3 manage.py runserver 0.0.0.0:$PORT
15. create a requirements.txt with pip3 freeze
16. Grab the dns target from Heroku Settings (scroll down)
17. Go to manage dns in Godaddy for your domain
18. Add that DNS target to the CNAME record with www
19. in Godaddy, also forward the domain to http://www.domain.com and update name servers and DNS
20. done
