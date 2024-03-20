# Api-Testing-Using-Postman-and-Newman-report

Run newman extra report on cmd: 

//path to newman:

C:\Users\MSI>cd C:\Users\MSI\AppData\Roaming\npm

//run report and make a folder and save it:

--previous try:((C:\Users\MSI\AppData\Roaming\npm>newman run  "F:\SQA\API testing\Scripting and html report\Scripting tutorial.postman_collection.json" -r htmlextra --reporter-htmlextra-export ./results/report.html))

C:\Users\MSI>newman run  "F:\SQA\API testing\Scripting and html report\Scripting tutorial.postman_collection.json" -r htmlextra --reporter-htmlextra-export "F:\SQA\API testing\Scripting and html report/results/report.html"

source to installation: 
https://github.com/DannyDainton/newman-reporter-htmlextra/blob/main/README.md
https://www.npmjs.com/package/newman-reporter-htmlextra
