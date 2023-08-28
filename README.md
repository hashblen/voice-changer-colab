<a target="_blank" href="https://colab.research.google.com/github/hashblen/voice-changer-colab/blob/main/w_okada_voice_changer_running_on_Colab.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

# voice-changer-colab
This is a very very simple Google colab notebook for running [w-okada/voice-changer](https://github.com/w-okada/voice-changer) in Google's server instead of your machine.

## Prerequesites
You need an account on https://dashboard.ngrok.com and a token. Change the value of `NGROK_AUTH_TOKEN` to your token.

You also need to have chrome (/maybe others based on chromium) or the electron app `voice-changer-native-client.exe` from w-okada's repository.

## Running
Open https://colab.research.google.com/github/hashblen/voice-changer-colab/blob/main/w_okada_voice_changer_running_on_Colab.ipynb
<a target="_blank" href="https://colab.research.google.com/github/hashblen/voice-changer-colab/blob/main/w_okada_voice_changer_running_on_Colab.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

Run each cell one by one. Now paste the link you got from the second cell into chrome (or use `voice-changer-native-client.exe --url https://the-url-that-you-got.ngrok-free.app`)

You're good to go ! Please keep in mind that because there is a substantial delay, changing sliders is a bit tricky.

## Note
w-okada seems to have added a colab notebook on their own repository a month after I had done it, so this one is no longer needed: https://github.com/w-okada/voice-changer/blob/master/Realtime_Voice_Changer_on_Colab.ipynb
