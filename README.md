# OCR in .NET Core with Tesseract and Google Vision

![Framework](https://img.shields.io/badge/framework-.net%20core%20v3.1-green)
![Framework](https://img.shields.io/badge/API-Google%20Vision%20API-orange)

# Dependencies for Tesseract

| Tools & Frameworks                           | Links                                                                |
| -------------------------------------------- | -------------------------------------------------------------------- |
| Tesseract Engine exe                         | [Download](https://digi.bib.uni-mannheim.de/tesseract/)              |
| Tesseract Nuget Package                      | [Nuget](https://www.nuget.org/packages/Tesseract/4.1.1/)             |
| System.Drawing.Common                        | [Nuget](https://www.nuget.org/packages/System.Drawing.Common/5.0.0/) |
| Tesseract Installation & Configuration Guide | [Youtube](https://www.youtube.com/watch?v=QJkKDsjj1oA)               |

# How to use it? (Tesseract)

Once Tesseract Engine has been installed and configured

**Step # 1 :**

    Clone the repository

**Step # 2 :**

    Open the solution file (Recommended with Visual Studio 2019)

**Step # 3 :**

    Run the project

# Inside Program.cs of OCR-in-Dot-NET-Core-with-Tesseract

- Put the path of your image with text at "**imgPath**" variable
- Put the path of your tessdata directory at "**tessdataPath**" variable
- Put your desired language selection in "**lang**" variable based on file names available inside **tessdata** directory

# Dependencies for Google Vision API

| Tools & Frameworks                             | Links                                                                                                                       |
| ---------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------  |
| Google Account                                 | [SignUp](https://accounts.google.com/signup/v2/webcreateaccount?hl=en&flowName=GlifWebSignIn&flowEntry=SignUp)              |
| This API method requires billing to be enabled | [Enable Billing](https://console.developers.google.com/billing/enable?project=testocr-302208)                               |
| CommandLine Parser                             | [Nuget](https://www.nuget.org/packages/CommandLineParser)                                                                   |
| Google Cloud Storage V1                        | [Nuget](https://www.nuget.org/packages/Google.Cloud.Storage.V1/)                                                            |
| Google Cloud Vision V1                         | [Nuget](https://www.nuget.org/packages/Google.Cloud.Vision.V1/)                                                             |

# How to use it? (Google Vision API)

Once Tesseract Engine has been installed and configured

**Step # 1 :**

    Clone the repository
    
**Step # 2 :**

    Get Cridientials for API and set Environment Variables.
    This youtube tutorial might be helpful :
    https://www.youtube.com/watch?v=UYKukqorksU&t=117s
    
**Step # 3 :**

    Enable Google Vision API for your project from here
    https://console.developers.google.com/apis/api/vision.googleapis.com/overview
    
**Step # 4 :**

    Enable Billing for your project. Take help from here
    https://console.developers.google.com/billing/enable
    
**Step # 5 :**

    Run the project
