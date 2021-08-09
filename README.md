# NODE.JS - Socket.io & Twitter Streaming API

### About

Utilizing Socket.io and the Twitter real-time streaming tweet API, we search for specific keywords on Twitter and display them on our website. In the example below, we are watching for the term "coding". If a tweet with that keyword is found, it is displayed, along with the author's name, and a button to directly access that tweet on the Twitter website. After 60 seconds the tweet is removed from the DOM.

![example_gif](./example.gif)

### Usage

Visit https://developer.twitter.com and sign up for API access. Put you bearer token in the .env file.

```
npm install

npm run dev
```
