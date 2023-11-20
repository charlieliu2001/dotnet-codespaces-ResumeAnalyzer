# Adanomad Resume Analyzer Challenge

I wrote the frontend page on the GitHub .NET Codespace.

This repo originally built a Weather API using Minimal APIs, opens Swagger so you can call and test the API, and displays the data in a web application using Blazor with .NET 8.

I directly edited the frontend razor page to accomplish resume analysis.

## Overview

This app takes in resume information, and generates both a word cloud of the most frequently mentioned words and the top 5 most frequently mentioned technical skills.

### Run Options

Go to Code -> CodeSpaces and click on 'Create codespace on main' to open in the browser.

If the created codespace is stuck loading, close the tab and try to open it again. This time, you should see the codespace you just created listed under 'CodeSpaces'. Click on it.

![](images/setup.png)
![](images/open.png)

## Getting started

1. **📤 One-click setup**: opening the CodeSpace gives you a fully configured cloud developer environment.
2. **▶️ Run all, one-click again**: Use VS Code's built-in *Run* command and open the forwarded ports *8080* and *8081* in your browser. 

![](images/RunAll.png)

3. If it doesn't open automatically, go to ports and click on the globe to open the front end.

![](images/how_to_run.png)

4. The Blazor web app should now be open on your browser. 

![image](images/1.png)

5. To stop running, return to VS Code, and click Stop twice in the debug toolbar. 

![](images/StopRun.png)


## Usage

1. Enter in the resume information.

![image](images/2.png)

2. Press submit and see the magic happen.

![image](images/3.png)

3. Click the Edit Information button to edit the provided information if needed, and resubmit.

![demofile](https://github.com/charlieliu2001/dotnet-codespaces-ResumeAnalyzer/blob/3f21f8a4ae78c565ba3cc88bc01e777848f5d2b3/images/demo.gif)

## Error checking

1. Checks if the name is empty or has special characters other than apostrophes ('), and hyphens (-), which means it's most likely wrong.

2. Checks if there aren't any listed, and if the ones listed are short enough (less than 20 characters). Otherwise it's most likely wrong.

3. Soft check - if there aren't any of the listed skills mentioned in the experience, let the user know, but still continue with the analysis.

![demofile](https://github.com/charlieliu2001/dotnet-codespaces-ResumeAnalyzer/blob/abe70ded2b6d8c7352295977554d1feadf0ab24e/images/errorcheck-demo.gif)


