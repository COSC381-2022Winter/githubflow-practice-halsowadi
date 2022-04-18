# Movies website for COSC 381
## Steps for starting the website (development mode


Steps:
1. Create a virtual environment in the root directory: 'python3 -m venv venv'
2. Activate the virtual environment: 'source venv/bin/activate'
3. Install dependencies: 'python3 -m pip install -r requirments.txt'
4. Set up environment variables for the falsk app: 'source env-var.sh'
5. Initialize the databse: 'flask init-db' After the database is initailized, 
the database file is at: 'instance/flaskr.sqlite'
6. Start the website: 'flask run'
7. The webpage can be checked at: 'http://127.0.0.1:500/movies/'