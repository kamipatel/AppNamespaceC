kamlesh.patel-fccu@force.com

sfdx force:auth:web:login --setdefaultdevhubusername 

sfdx force:source:deploy -x ./manifest/package.xml  -u kamlesh.patel-fccu@force.com

sfdx force:org:open  -u kamlesh.patel-fccu@force.com

sfdx force:source:pull -u sob
