# Create a new folder and initialize git
mkdir my-new-app
cd my-new-app
git init

# Create a sample file
echo "# My New App" > README.md

# Add and commit your changes
git add .
git commit -m "Initial commit"

# Link to your GitHub repo
git remote add origin https://github.com/<your-username>/my-new-app.git

# Push your code
git branch -M main
git push -u origin main
