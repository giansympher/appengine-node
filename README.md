Tutorial
1. Create a new project
 - Add the project to a billing account

2. login 
 - gcloud auth login

3. check if project created
 - gcloud projects list

4. go to APIs & Services
 - https://console.cloud.google.com/apis/dashboard?authuser=1&project=learning-gylproject&supportedpurview=project

5. click [+ Enables APIs and services]
 - https://console.cloud.google.com/apis/library?authuser=1&project=learning-gylproject&supportedpurview=project

6. search for "app engine"
 - click App Engine Admin API
 - https://console.cloud.google.com/apis/library/appengine.googleapis.com?q=app%20engine&id=a634ba3f-b36e-4e22-93a1-e80a2e817178&project=learning-gylproject&authuser=1&supportedpurview=project
 - click [Enable]

7. run command
 - gcloud config set project {project_name}
    e.g gcloud config set project learning-gylproject

8. go to appengine dashboard. [Nav] >> [App Engine] >> [Dashboard]
 - https://console.cloud.google.com/appengine/start?authuser=1&project=learning-gylproject&supportedpurview=project

9. create application
 - click [Create Application] or type command `gcloud app create` 
 - select region
 - success

10. create yaml file
 -  create app.yaml write `runtime: nodejs14`
 - https://cloud.google.com/appengine/docs/flexible/nodejs/configuring-your-app-with-app-yaml
 - https://cloud.google.com/appengine/docs/standard/python/config/appref





### Error
1. 
  ERROR: (gcloud.app.deploy) Error Response: [7] Access Not Configured. Cloud Build has not been used in project learning-gylproject before or it is disabled. Enable it by visiting https://console.developers.google.com/apis/api/cloudbuild.googleapis.com/overview?project=learning-gylproject then retry. If yo

  - go to cloud build api, setup billing account :<




