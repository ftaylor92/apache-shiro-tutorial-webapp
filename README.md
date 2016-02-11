apache-shiro-webapp-tutorial: http://shiro.apache.org/webapp-tutorial.html
============================

A step-by-step tutorial showing how to secure a web app with Apache Shiro

curl -X POST --user 6NNSLCT1QJVJDR7CR2QM7R5SB:mxSmEaMsTb7JIyV1G+FQP+AcD7mo1cPqB90sBPeirlI -H "Accept: application/json" -H "Content-Type: application/json" -d '{ "name" : "Apache Shiro Tutorial Webapp" }'     'https://api.stormpath.com/v1/applications?createDirectory=true'
        
curl -X POST --user 6NNSLCT1QJVJDR7CR2QM7R5SB:mxSmEaMsTb7JIyV1G+FQP+AcD7mo1cPqB90sBPeirlI -H "Accept: application/json" -H "Content-Type: application/json" -d '{ "name" : "Apache Shiro Tutorial Webapp" }' 'https://api.stormpath.com/v1/applications?createDirectory=true'

curl -X POST --user 6NNSLCT1QJVJDR7CR2QM7R5SB:mxSmEaMsTb7JIyV1G+FQP+AcD7mo1cPqB90sBPeirlI -H "Accept: application/json" -H "Content-Type: application/json" -d '{ "apacheShiroPermissions": [ "ship:NCC-1701-D:command", "user:jlpicard:edit" ] }' "https://api.stormpath.com/v1/accounts/3LVbbsIBLZEsZSRRxpARUx/customData"

figure out how to use database instead of StormCloud, or not