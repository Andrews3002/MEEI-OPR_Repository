#*Preperation for Deployment on Azure*
- removed the unnecessary venv/ folder from the repo
- changed the DEBUG value in the app constructor function to changes based on environment variable instead of hardcoded
- removed psycopg2==2.9.10 from requirements.txt since psycopg2==2.9.10 is already listed
- changed the pool recycle interval from 1 to 1800


