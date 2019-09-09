AI/ML Workshop

## Lab-1 


## Lab 2 - Amazon Transcribe + Comprehend

Using Amazon Transcribe Websocket in a static web application, we can capture voice, transcribe the voice stream into text, and then perform sentiment analysis on the text to display the POSITIVE, NEGATIVE, NUTURL sentiments. 

Components built and deployed:

* A static site with Amplify
* real-time audio transcription via Amazon Transcribe over a WebSocket.
* real-time comprehend API call to extract sentiments

This demo app uses browser microphone input and client-side JavaScript to demonstrate the real-time streaming audio transcription capability of [Amazon Transcribe](https://aws.amazon.com/transcribe/) using WebSockets.

Check out the [Amazon Transcribe WebSocket docs](https://docs.aws.amazon.com/transcribe/latest/dg/websocket.html).

### Building and Deploying

[![amplifybutton](https://oneclick.amplifyapp.com/button.svg)](https://console.aws.amazon.com/amplify/home#/deploy?repo=https://github.com/jxuamazon/ai-ml-workshop)

Even though this is a static site consisting only of HTML, CSS, and client-side JavaScript, there is a build step required. Some of the modules used were originally made for server-side code and do not work natively in the browser.

We use [browserify](https://github.com/browserify/browserify) to enable browser support for the JavaScript modules we `require()`.

1. Clone the repo
2. run `npm install`
3. run `npm run-script build` to generate `dist/main.js`.

Once you've bundled the JavaScript, all you need is a webserver. For example, from your project directory: 

```
npm install --global local-web-server
ws
```

#### Credits

This project is based on code written by Karan Grover from the Amazon Transcribe team, who did the hard work (audio encoding, event stream marshalling).
Sentiment fetch based on the transcription is added by Jianjun Xu

#### License

This library is licensed under the Apache 2.0 License. 