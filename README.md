# SETUP
    - fork repository
    - new replit with forked repository
    - start application (It installs deps and start the server)
    - `cd src && python manage.py createsuperuser`
# SETP 1: todo app
    - `python manage.py startapp todos`
    - add app to installed apps
    - add models
    - add admin
    - `python manage.py makemigrations`
    - `python manage.py migrate`
https://github.com/eigenmannmartin/workshop-solution/commit/93fb9e7e5518b8b1bbf7b53fc5c78078725fb36c

# STEP 2: hello world view
    - add view
    - add template (base & index)
    - add urls (for todo index and accounts)
https://github.com/eigenmannmartin/workshop-solution/commit/2f67ff26787a6d61cd420f7115706eebedc6041f

# STEP 3: Forms
    - add view and url for collection
    - update templates
https://github.com/eigenmannmartin/workshop-solution/commit/ea9ea44d18c3ec7360ea411b678a8d29ce5d9ab1

# SETP 4: REST API
    - add serializer, viewsets and urls, installed app and config
https://github.com/eigenmannmartin/workshop-solution/commit/090c21e0bb4971659ae8b4e4e701d3a19d7658e5

# SETP 5: API Token
    - add app & config
    - migrate
https://github.com/eigenmannmartin/workshop-solution/commit/114ff4610630d3ea3302e69a2a8d586a9e0aca5e

# SETP 6: Tests
    - add tests file
    - `python manage.py tests todos`
https://github.com/eigenmannmartin/workshop-solution/commit/db6e0b455bed1dbb8666a3b3e2e7aced19daf057