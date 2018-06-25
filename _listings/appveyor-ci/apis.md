---
name: AppVeyor CI
x-slug: appveyor-ci
description: We provide continuous integration tools for Windows developers. The service
  is offered for free to open-source projects, we offer subscriptions for private
  projects and AppVeyor Enterprise installations on customer premises.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
x-kinRank: "7"
x-alexaRank: "35479"
tags: Environments
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/environments/master/_listings/appveyor-ci/apis.md
specificationVersion: "0.14"
apis:
- name: App Veyor Get Environments
  x-api-slug: app-veyor
  description: Get environments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//environments
  tags: Environments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environments/master/_listings/appveyor-ci/environments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environments/master/_listings/appveyor-ci/environments-get-openapi.md
- name: App Veyor Post Environments
  x-api-slug: app-veyor
  description: Post environments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//environments
  tags: Environments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environments/master/_listings/appveyor-ci/environments-post-openapi.md
- name: App Veyor Put Environments
  x-api-slug: app-veyor
  description: Put environments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//environments
  tags: Environments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environments/master/_listings/appveyor-ci/environments-put-openapi.md
- name: App Veyor Delete Environments Deploymentenvironmentid
  x-api-slug: app-veyor
  description: Delete environments deploymentenvironmentid.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//environments/{deploymentEnvironmentId}
  tags: Environments,DeploymentEnvironmentId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environments/master/_listings/appveyor-ci/environmentsdeploymentenvironmentid-delete-openapi.md
- name: App Veyor Parameters Environments Deploymentenvironmentid
  x-api-slug: app-veyor
  description: Parameters environments deploymentenvironmentid.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//environments/{deploymentEnvironmentId}
  tags: Environments,DeploymentEnvironmentId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environments/master/_listings/appveyor-ci/environmentsdeploymentenvironmentid-parameters-openapi.md
- name: App Veyor Get Environments Deploymentenvironmentid Deployments
  x-api-slug: app-veyor
  description: Get environments deploymentenvironmentid deployments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//environments/{deploymentEnvironmentId}/deployments
  tags: Environments,DeploymentEnvironmentId,Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environments/master/_listings/appveyor-ci/environmentsdeploymentenvironmentiddeployments-get-openapi.md
- name: App Veyor Parameters Environments Deploymentenvironmentid Deployments
  x-api-slug: app-veyor
  description: Parameters environments deploymentenvironmentid deployments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//environments/{deploymentEnvironmentId}/deployments
  tags: Environments,DeploymentEnvironmentId,Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environments/master/_listings/appveyor-ci/environmentsdeploymentenvironmentiddeployments-parameters-openapi.md
- name: App Veyor Get Environments Deploymentenvironmentid Settings
  x-api-slug: app-veyor
  description: Get environments deploymentenvironmentid settings.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//environments/{deploymentEnvironmentId}/settings
  tags: Environments,DeploymentEnvironmentId,Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environments/master/_listings/appveyor-ci/environmentsdeploymentenvironmentidsettings-get-openapi.md
- name: App Veyor Parameters Environments Deploymentenvironmentid Settings
  x-api-slug: app-veyor
  description: Parameters environments deploymentenvironmentid settings.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//environments/{deploymentEnvironmentId}/settings
  tags: Environments,DeploymentEnvironmentId,Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environments/master/_listings/appveyor-ci/environmentsdeploymentenvironmentidsettings-parameters-openapi.md
- name: App Veyor
  x-api-slug: app-veyor
  description: We provide continuous integration tools for Windows developers. The
    service is offered for free to open-source projects, we offer subscriptions for
    private projects and AppVeyor Enterprise installations on customer premises.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api
  tags: Environments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/environments/master/_listings/appveyor-ci/openapi.md
x-common:
- type: x-crunchbase
  url: https://crunchbase.com/organization/appveyor-systems-inc
- type: x-documentation
  url: https://www.appveyor.com/docs/
- type: x-email
  url: jobs@appveyor.com
- type: x-email
  url: team@appveyor.com
- type: x-email
  url: privacy@appveyor.com
- type: x-twitter
  url: https://twitter.com/appveyor
- type: x-website
  url: http://appveyor.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---