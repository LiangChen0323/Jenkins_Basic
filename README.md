# Jenkins_Basic

Gradle:
Install Java 8
build.gradle: uses nodejs:12.17.0 and npm: 6.14.5

Webhook:
Create a token at Github-Developer Settings give appropriate permission
Jenkins-configuration-Github-Github server to select the token (Add->Kind:Secret text)as the credential, check Manege hooks checkbox
in the Jenkins project: check Build Triggers: GitHub hook trigger for GITScm polling
