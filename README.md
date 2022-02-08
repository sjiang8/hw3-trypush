# Project Milestone 1 
    Sijia Jiang
    CSC 4350
    Prof. Martin

## Tools
1. libraries: `os`
2. Tools: `requests`, `python-dotenv`, `Flask`
3. deployment: `heroku`

## Setup
1. install request by `pip install Flask python-dotenv requests`
2. Clone the project repository by running `git clone https://github.com/csc4350-sp22/project1-sjiang8.git `
3. Get heroku account and login to heroku if possible `heroku login -i`
4. Login to TMDB account and generate an api key.
5. Create a `env.` file in the directory and enter
```
export API_KEY='YOUR_KEY'

```

## Run
1. `python3 app.py`
2. heroku-URL: http://sleepy-savannah-45990.herokuapp.com/


## Technical Issues
1. error: failed to push some refs to 'https://www.github.com/sjiang8/lect-7.git'

That's because I already create a README file in my main branch, so I delete my lect7 repo and recreate an empty one.

2. 
```
/mnt/c/Program Files/heroku/bin/../client/bin/heroku.cmd: 1: @echo: not found
/mnt/c/Program Files/heroku/bin/../client/bin/heroku.cmd: 2: setlocal: not found
/mnt/c/Program Files/heroku/bin/../client/bin/heroku.cmd: 4: Syntax error: "(" unexpected (expecting "then")

```
fixed after adding `sudo` to each heroku command
3. 
```
Password for 'https://git.heroku.com':
remote: !       WARNING:
remote: !       Do not authenticate with username and password using git.
remote: !       Run `heroku login` to update your credentials, then retry the git command.
remote: !       See documentation for details: https://devcenter.heroku.com/articles/git#http-git-authentication
fatal: Authentication failed for 'https://git.heroku.com/sleepy-savannah-45990.git/'
```
fixed by 




