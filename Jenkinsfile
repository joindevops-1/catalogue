#!groovy
// it means the libraries will be downloaded and accessible at run time
@Library('roboshop-shared-library') _

def configMap = [
    application: "nodeJSEKSCI",
    component: "catalogue"
]
if ( env.BRANCH_NAME.equalsIgnoreCase('master') ){
    pipelineDecission.decidePipleine(configMap)
}
