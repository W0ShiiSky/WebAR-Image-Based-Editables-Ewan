This version is the LTA CNY AR web app 2024 and the assets is accessed locally instead of the S3 URL.


To change or add new data like fortunes and targetImage

1. Fortunes.json - To add new fortunes just add in new string of fortunes and save it
2. config.json
   Step 1: Go into https://hiukim.github.io/mind-ar-js-doc/tools/compile/ to compile a new target image\
   Step 2: Put the new mind-file into folder name "./static/mind-file"
   Step 3: Change the config.json file details for the "imageTargetSrc" to the new mind-file file path
