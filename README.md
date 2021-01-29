

sfdx force:auth:web:login --setdefaultdevhubusername 

sfdx force:source:deploy -x ./manifest/package.xml  -u kamlesh.patel-fbk3@force.com

sfdx force:org:open  -u kamlesh.patel-fbk3@force.com

sfdx force:source:pull -u sob
