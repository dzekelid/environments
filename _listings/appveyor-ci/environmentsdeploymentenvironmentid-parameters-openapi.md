---
swagger: "2.0"
x-collection-name: AppVeyor CI
x-complete: 0
info:
  title: App Veyor Parameters Environments Deploymentenvironmentid
  description: Parameters environments deploymentenvironmentid.
  termsOfService: https://www.appveyor.com/terms-of-service/
  contact:
    name: AppVeyor Team
    url: https://www.appveyor.com/about/
    email: team@appveyor.com
  version: 0.20170106.0
host: ci.appveyor.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /environments:
    get:
      summary: Get Environments
      description: Get environments.
      operationId: getEnvironments
      x-api-path-slug: environments-get
      responses:
        200:
          description: OK
      tags:
      - Environments
    post:
      summary: Post Environments
      description: Post environments.
      operationId: postEnvironments
      x-api-path-slug: environments-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Environments
    put:
      summary: Put Environments
      description: Put environments.
      operationId: putEnvironments
      x-api-path-slug: environments-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Environments
  /environments/{deploymentEnvironmentId}:
    delete:
      summary: Delete Environments Deploymentenvironmentid
      description: Delete environments deploymentenvironmentid.
      operationId: deleteEnvironmentsDeploymentenvironment
      x-api-path-slug: environmentsdeploymentenvironmentid-delete
      responses:
        200:
          description: OK
      tags:
      - Environments
      - DeploymentEnvironmentId
    parameters:
      summary: Parameters Environments Deploymentenvironmentid
      description: Parameters environments deploymentenvironmentid.
      operationId: parametersEnvironmentsDeploymentenvironment
      x-api-path-slug: environmentsdeploymentenvironmentid-parameters
      responses:
        200:
          description: OK
      tags:
      - Environments
      - DeploymentEnvironmentId
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---