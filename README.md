This is Manuel's base setup for Django Projects.

I will try to use GitHub Actions and Docker to create a nice CI/CD Flow.

**psycopg2-binary**
I use psycopg2-binary as a database-adapter for Python.
This is a standalone package that includes the psycopg2 package along with the compiled C binaries.
The key advantage of psycopg2-binary is that it doesn't require the compilation step during installation, 
making it easier and faster to install, especially in environments where compiling from source might be problematic or undesirable 
(such as in some Docker containers, CI/CD pipelines, or on Windows machines where setting up a C compiler environment can be more challenging)

**python-dotenv**
To securely manage values like the database credentials, I use environment variables and the python-dotenv package.
Check the settings for the usage.
