# Building a Django app w/ REST, Postgres > Heroku

## Build the Django project and app

>[Jeanettes simple Django start](https://www.notion.so/Starting-a-new-Django-project-071f052d07cc4ea6bdf998eb9e4a4a3c)
>
>[Install Django Extensions](https://django-extensions.readthedocs.io/en/latest/installation_instructions.html)

## Install REST and djoser registration

>Install Rest
>- [Documentation install](https://www.django-rest-framework.org/#installation)
>- [Good tutorial](https://learndjango.com/tutorials/official-django-rest-framework-tutorial-beginners)
>
>[Install djoser registration](https://djoser.readthedocs.io/en/latest/index.html) 

## Set up db's

>[Set up local postgres db](https://momentumlearn.notion.site/Using-Postgres-Locally-6d24cd1ea8854eabb875023d6696fba9#f0f19d289e6c4371867fe815dc8ddeac)
>    - remember 'username' and 'dbname' for the next step.
>
>[Hook up Postico](https://eggerapps.at/postico/)
>    - After download: File > Show Favorites Window > New Favorite

## Deploy to Heroku and view db
>[Deploy to Heroku](https://momentumlearn.notion.site/Deploying-a-Django-App-to-Heroku-81488333c03445539bfc7eb3c1691ed0#b2ef336a412b40e590ea73f689f2cd7d)
>
>Configure postgres on Heroku
>1. At Heroku, Go to app page > 'configure add-ons'.
>2. Pick Heroku Postgress, Hobby Dev $0 option.
>
>Configure Postico for remote
>1. At Heroku: go to app page > in 'installed add-ons' click 'Heroku Postgres'
>2. Go to 'Settings' > on right side of 'Database Credentials
>3. Click View Credentials > copy keys:values into Postico > File > Show Favorites Window > New Favorite. 



## Don't forget
1. Get .env straight
    -[generate secret key](https://humberto.io/blog/tldr-generate-django-secret-key/) always comes in handy
2. Make sure you do a gitignore BEFORE you push to GitHub

## Git work cycle
>[Git collaboration slideshow](https://slides.com/amy_nc/git-collaboration#/4)
>
>1. Make a branch
>2. Do your work 
>    - Do commits often, short/sweet comments and bundle them together w/ pushes that are only for 1 feature at a time.
>3. Push the branch.  NEVER PUSH ORIGIN MAIN!
>4. Do Pull request, get merge done at GitHub, delete remote branch
>5. Back at local: 
>    - git fetch
>    - git pull origin main
>    - migrate anything that came w/ the pull (IF YOU DON'T DO THIS IT WILL BE HEADACHES LATER)
>6. GOTO top

## Use [Insomnia](https://insomnia.rest/download)
