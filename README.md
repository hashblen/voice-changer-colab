# voice-changer-colab
This is a very very simple Google colab notebook for running [w-okada/voice-changer](https://github.com/w-okada/voice-changer) in Google's server instead of your machine.

## Prerequesites
You need an account on https://dashboard.ngrok.com and a token. Change the value of `NGROK_AUTH_TOKEN` to your token.

You also need to have chrome (/maybe others based on chromium) or the electron app `voice-changer-native-client.exe` from w-okada's repository.

## Running
Run each cell one by one. Now paste the link you got from the second cell into chrome (or use `voice-changer-native-client.exe --url https://the-url-that-you-got.ngrok-free.app`)

You're good to go ! Please keep in mind that because there is a substantial delay, changing sliders is a bit tricky.
