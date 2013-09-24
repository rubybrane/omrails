$ rails new omrails                 # Create a new Rails application in the folder omrails
$ rails server                      # Run a local server (defaults to localhost:3000)
$ git config --global user.name "Your Name"               # Set your Git name
$ git config --global user.email youremail@gmail.com      # Set your Git email
$ git init                          # Set up Git on your project
$ git status                        # See tracked, untracked, and staged files
$ git add .                         # Add new files to Git
$ git commit -am "Initial commit"   # Save your project files to Git
$ git remote add origin git@github.com:yourusername/omrails.git     # Set up git to push to your Github repository
$ git push -u origin master         # Push your code to Github (sets the upstream the first time)
$ git push                          # Push your code to Github
$ ssh-keygen -t rsa -C "youremail"  # Generate an ssh key
$ pbcopy < ~/.ssh/id_rsa.pub        # Copy the contents of the id_rsa.pub file to your clipboard
$ ssh -T git@github.com             # Attempt to ssh to Github
$ mv README.rdoc README.md          # Rename the file README.rdoc to README.md
$ heroku keys:add                   # Push your ssh keys up to Heroku
$ heroku create                     # Set up an application on Heroku
$ git push heroku master            # Push your code to Heroku
$ subl .                            # Open the current directory in Sublime Text