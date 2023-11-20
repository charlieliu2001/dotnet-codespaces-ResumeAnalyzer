# Adanomad Resume Analyzer Challenge

I wrote the frontend page on the GitHub .NET Codespace.

This repo originally built a Weather API using Minimal APIs, opens Swagger so you can call and test the API, and displays the data in a web application using Blazor with .NET 8.

I directly edited the frontend razor page to accomplish resume analysis.

## Overview

This app takes in resume information, and generates both a word cloud of the most frequently mentioned words and the top 5 most frequently mentioned technical skills.

### Run Options

[![Open in GitHub Codespaces](https://img.shields.io/static/v1?style=for-the-badge&label=GitHub+Codespaces&message=Open&color=lightgrey&logo=github)](https://codespaces.new/github/dotnet-codespaces)
[![Open in Dev Container](https://img.shields.io/static/v1?style=for-the-badge&label=Dev+Container&message=Open&color=blue&logo=visualstudiocode)](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/github/dotnet-codespaces)

You can also run this repository locally by following these instructions: 
1. Clone the repo to your local machine `git clone https://github.com/bradygaster/dotnet-codespace`
1. Open repo in VS Code

## Getting started

1. **📤 One-click setup**: [Open a new Codespace](https://codespaces.new/github/dotnet-codespaces), giving you a fully configured cloud developer environment.
2. **▶️ Run all, one-click again**: Use VS Code's built-in *Run* command and open the forwarded ports *8080* and *8081* in your browser. 

![](images/RunAll.png)

3. Go to ports and click on the globe to open the front end.
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


## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
