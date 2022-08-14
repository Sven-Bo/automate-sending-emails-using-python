# Automate Your Emails Using Python - Build An Payment Reminder & Schedule Your Script Online (FREE)

Are you still manually sending emails to your customers and clients? In this video, I'll show you how to send automated reminders. In particular, I will show you how to send emails with emails. Afterwards, we are going to host our Python script. You can then determine when exactly you want to run your script. This solution might be helpful if you do not want to spend a dime on any expensive email automation solution. You can build your email automation solution for free if you follow this video.


## Architecture
![Architecture](./Architecture.png?raw=true "Architecture")


## Video Tutorial
..will follow soon!
[![YouTube Video](https://img.youtube.com/vi/XXX/0.jpg)](https://youtu.be/XXX)


## Requirements
Install the dependencies with pip
```
pandas
python-dotenv
```
[FOR WINDOWS]
Install the Deta CLI, open PowerShell and enter:
```bash
  iwr https://get.deta.dev/cli.ps1 -useb | iex
```


## Deployment
👉 Official Documentation: https://docs.deta.sh/docs/micros/getting_started

[FOR WINDOWS]
To deploy this project you:
1) need to login
```bash
  deta login
```
2) create a new micro (only once!):
```bash
  deta new --python first_micro
```
3) upload your environment variables:
```bash
  deta update -e <env_file_name>
```
4) deploy your app:
```bash
  deta deploy
```
5) set the cron job:
Example: Run every minute
```bash
  deta cron set "1 minute"
```

## Environment Variables
To run this project, you will need to add the following environment variables to your .env file
`EMAIL`
`PASSWORD`

## Run the app
Terminal
```
# vanilla terminal
streamlit run app.py
```

## About Me
- Sven from Coding Is Fun
- YouTube: https://youtube.com/c/CodingIsFun
- Website: https://pythonandvba.com

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/X7X47Q0EG)

## Feedback
If you have any feedback, please reach out to me at contact@pythonandvba.com
![Logo](https://www.pythonandvba.com/banner-img)
