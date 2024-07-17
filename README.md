# Automate Your Emails Using Python - Build A Payment Reminder & Schedule Your Scripts Online (FREE)

Are you still manually sending emails to your customers and clients? In this video, I'll show you how to send automated reminders. In particular, I will show you how to send emails with Python. Afterwards, we are going to host our Python script. You can then determine when exactly you want to run your script. This solution might be helpful if you do not want to spend a dime on any expensive email automation solution. You can build your email automation solution for free if you follow this video.


## Architecture
![Architecture](./Architecture.png?raw=true "Architecture")


## Video Tutorial
[![YouTube Video](https://img.youtube.com/vi/OLrC4J2-pvk/0.jpg)](https://youtu.be/OLrC4J2-pvk)


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

## Make a Google Sheets Copy
Here you find the **Google Sheet** I have used in the video: ⤵ <br/>
https://pythonandvba.com/sheets-invoice-data <br/>
![Google Sheets](/google_sheets_invoice_data.png?raw=true "Google Sheets")

## Deployment
**Official Documentation:** https://docs.deta.sh/docs/micros/getting_started <br/>

[FOR WINDOWS] <br/>
To deploy this project you:
1) login via the deta CLI
```bash
  deta login
```
2) create a new micro (only once!)
```bash
  deta new --python first_micro
```
3) upload your environment variables
```bash
  deta update -e <env_file_name>
```
4) deploy your app
```bash
  deta deploy
```
5) set the cron job <br/>
Example: Run every minute
```bash
  deta cron set "1 minute"
```

## Environment Variables
To run this project, you will need to add the following environment variables to your .env file <br/>
`EMAIL`
`PASSWORD`




## 🤓 Check Out My Excel Add-ins
I've developed some handy Excel add-ins that you might find useful:

- 📊 **[Dashboard Add-in](https://pythonandvba.com/grafly)**: Easily create interactive and visually appealing dashboards.
- 🎨 **[Cartoon Charts Add-In](https://pythonandvba.com/cuteplots)**: Create engaging and fun cartoon-style charts.
- 🤪 **[Emoji Add-in](https://pythonandvba.com/emojify)**: Add a touch of fun to your spreadsheets with emojis.
- 🛠️ **[MyToolBelt Add-in](https://pythonandvba.com/mytoolbelt)**: A versatile toolbelt for Excel, featuring:
  - Creation of Pandas DataFrames and Jupyter Notebooks from Excel ranges
  - ChatGPT integration for advanced data analysis
  - And much more!



## 🤝 Connect with Me
- 📺 **YouTube:** [CodingIsFun](https://youtube.com/c/CodingIsFun)
- 🌐 **Website:** [PythonAndVBA](https://pythonandvba.com)
- 💬 **Discord:** [Join our Community](https://pythonandvba.com/discord)
- 💼 **LinkedIn:** [Connect with me](https://www.linkedin.com/in/sven-bosau/)
- 📸 **Instagram:** [Follow me](https://www.instagram.com/codingisfun_official/)

## Support My Work
Love my content and want to show appreciation? Why not [buy me a coffee](https://pythonandvba.com/coffee-donation) to fuel my creative engine? Your support means the world to me! 😊

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://pythonandvba.com/coffee-donation)

## Feedback
Got some thoughts or suggestions? Don't hesitate to reach out to me at contact@pythonandvba.com. I'd love to hear from you! 💡
![Logo](https://www.pythonandvba.com/banner-img)
