---
swagger: "2.0"
x-collection-name: GitLab
x-complete: 0
info:
  title: GitLab Put Projects Environments Environment
  version: 1.0.0
  description: This feature was introduced in GitLab 8.11.
host: localhost:3000
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v3/projects/{id}/environments:
    get:
      summary: Get Projects Environments
      description: This feature was introduced in GitLab 8.11.
      operationId: getV3ProjectsIdEnvironments
      x-api-path-slug: v3projectsidenvironments-get
      parameters:
      - in: path
        name: id
        description: The project ID
      - in: query
        name: page
        description: Current page number
      - in: query
        name: per_page
        description: Number of items per page
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Environments
    post:
      summary: Post Projects Environments
      description: This feature was introduced in GitLab 8.11.
      operationId: postV3ProjectsIdEnvironments
      x-api-path-slug: v3projectsidenvironments-post
      parameters:
      - in: formData
        name: external_url
        description: URL on which this deployment is viewable
      - in: path
        name: id
        description: The project ID
      - in: formData
        name: name
        description: The name of the environment to be created
      - in: formData
        name: slug
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Environments
  /v3/projects/{id}/environments/{environment_id}:
    put:
      summary: Put Projects Environments Environment
      description: This feature was introduced in GitLab 8.11.
      operationId: putV3ProjectsIdEnvironmentsEnvironmentId
      x-api-path-slug: v3projectsidenvironmentsenvironment-id-put
      parameters:
      - in: path
        name: environment_id
        description: The environment ID
      - in: formData
        name: external_url
        description: The new URL on which this deployment is viewable
      - in: path
        name: id
        description: The project ID
      - in: formData
        name: name
        description: The new environment name
      - in: formData
        name: slug
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Environments
      - Environment
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