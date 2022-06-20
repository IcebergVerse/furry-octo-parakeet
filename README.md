# Note: If on Windows, run
# git clone -c core.symlinks=true https://github.com/plaid/quickstart
# instead to ensure correct symlink behavior

git clone https://github.com/plaid/quickstart.git
cd quickstart

# Copy the .env.example file to .env, then fill
# out PLAID_CLIENT_ID and PLAID_SECRET in .env
cp .env.example .env

# start the container for one of these languages:
# node, python, java, ruby, or go

make up language=node

# Go to http://localhost:3000
