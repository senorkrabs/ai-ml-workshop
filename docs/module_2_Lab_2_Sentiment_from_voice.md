## Lab 2 - Extract Sentiments from Voice using Amazon Transcribe and Comprehend

This application is based on this aws sample with modification to add comprehend sentiment extraction.

### Instruction:

- Login to AWS Console
    - Goto IAM -> Users -> transcribe-user -> Security Credentials -> Create access key. 
    - Recordthe Access key ID and Secret access key for later use

![iam](/images/access_key.png)

- From AWS Console/Services: Go to "AWS Amplify"
        - Expand the menu icon on the left -> All apps -> "Connect app" - chose Deploy without Git provider
        - Fill in "App name", "Environment Name" and use "Drag and Drop" : ai-ml-workshop.zip
        - Save and Deploy
        - Once deployment is completed, click on the "Demo Transcribe and Comprehend application" link below
        [Demo Transcribe and Comprehend application](/lab-transcribe/index.html)

* If you use Git provider (e.g Github), you can automatically redeploy the app whenever new code is checked in. And Amplify will take care of the build and deployment for you.

### Using Cloud9 IDE to work with the code

- From AWS Console -> Cloud9
- Create an environment, with t3.small
- Once Cloud9 environment is up
    - File -> upload local files : select the ai-ml-workshop.zip file you downloaded
    - In the console window, unzip ai-ml-workshop.zip
    - Or you can clone the soruce in the terminal window : git clone https://github.com/jxuamazon/ai-ml-workshop