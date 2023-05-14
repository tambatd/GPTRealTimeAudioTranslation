# GPTRealTimeAudioTranslation
Translate spoken audio in real time utilizing OpenAI's text-davinci-003 engine 

https://github.com/tambatd/GPTRealTimeAudioTranslation/assets/54927248/f0551289-09a2-4fdb-bd94-39972baa62d9


To change the language being translated change the word "Japanese" on line 27 to any other ChatGPT supported language
```py
 answer = query_question("You are hyper-fluent in Japanese, translate the following English sentence into Japanese: " + text)
```

you'll also need to install these modules via pip
  ```
  openai
  speech_recognition
  ```
