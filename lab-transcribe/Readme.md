## Lab 2 - Extract Sentiments from Voice using Amazon Transcribe and Comprehend
This application is based on [this aws sample] (https://github.com/aws-samples/amazon-transcribe-websocket-static) with modification to add comprehend sentiment extraction.

### Resources: 
1. Code repo:  https://github.com/jxuamazon/ai-ml-workshop 
2. Download: https://static.myoctank.net/public/ai-ml-workshop.zip



### Instruction:
1. Login to AWS Console
2. Goto IAM -> Users -> transcribe-user -> Security Credentials -> Create access key. Record the Access key ID and Secret access key for later use
3. From AWS Console/Services: Go to "AWS Amplify"
4. Expand the menu icon on the left -> All apps -> "Connect app" - chose Deploy without Git provider
5. Fill in "App name", "Environment Name" and use "Drag and Drop" : ai-ml-workshop.zip
6. Save and Deploy

Once deployment is completed, click on the "Demo Transcribe and Comprehend application" link below

* If you use Git provider (e.g Github), you can automatically redeploy the app whenever new code is checked in. And Amplify will take care of the build and deployment for you.
Demo Transcribe and Comprehend application

### Using Cloud9 IDE to work with the code

1. From AWS Console -> Cloud9
2. Create an environment, with t3.small
3. File -> upload local files : select the ai-ml-workshop.zip file you downloaded
4. In the console window, unzip ai-ml-workshop.zip
5. Or you can clone the source in the terminal window : $ git clone https://github.com/jxuamazon/ai-ml-workshop