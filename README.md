# Api-Testing-Using-Postman-and-Newman-report

Run newman extra report on cmd: 

![ss1](https://github.com/MUMTAHINA-766/Api-Testing-Using-Postman-and-Newman-report/assets/64628178/df5cef2c-e3bd-463a-8cd0-452b0b96e868)


![ss2](https://github.com/MUMTAHINA-766/Api-Testing-Using-Postman-and-Newman-report/assets/64628178/7e417619-5057-45d2-873f-e7ddb8c89d02)


## path to newman:

C:\Users\MSI>cd C:\Users\MSI\AppData\Roaming\npm

## run report and make a folder and save it:

--previous try:((C:\Users\MSI\AppData\Roaming\npm>newman run  "F:\SQA\API testing\Scripting and html report\Scripting tutorial.postman_collection.json" -r htmlextra --reporter-htmlextra-export ./results/report.html))

C:\Users\MSI>newman run  "F:\SQA\API testing\Scripting and html report\Scripting tutorial.postman_collection.json" -r htmlextra --reporter-htmlextra-export "F:\SQA\API testing\Scripting and html report/results/report.html"

## Command source for installation: 

https://github.com/DannyDainton/newman-reporter-htmlextra/blob/main/README.md
https://www.npmjs.com/package/newman-reporter-htmlextra

