swagger: "2.0"
x-collection-name: Codefresh
x-complete: 1
info:
  title: Codefresh API
  description: codefresh-api-swagger2-0-specification
  termsOfService: http://www.codefresh.io
  contact:
    name: Codefresh api team
    url: http://www.codefresh.io
  version: 1.0.0
host: g.codefresh.io
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
  /environments/{id}/status:
    get:
      summary: Get Environments Status
      description: Get environments status.
      operationId: getEnvironmentsStatus
      x-api-path-slug: environmentsidstatus-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environments
      - Status
  /environments/{id}/stop:
    get:
      summary: Get Environments Stop
      description: Get environments stop.
      operationId: getEnvironmentsStop
      x-api-path-slug: environmentsidstop-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environments
      - Stop
  /environments/{id}/start:
    get:
      summary: Get Environments Start
      description: Get environments start.
      operationId: getEnvironmentsStart
      x-api-path-slug: environmentsidstart-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environments
      - Start
  /environments/{id}/pause:
    get:
      summary: Get Environments Pause
      description: Get environments pause.
      operationId: getEnvironmentsPause
      x-api-path-slug: environmentsidpause-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environments
      - Pause
  /environments/{id}/unpause:
    get:
      summary: Get Environments Unpause
      description: Get environments unpause.
      operationId: getEnvironmentsUnpause
      x-api-path-slug: environmentsidunpause-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environments
      - Unpause
  /environments/{id}/terminate:
    get:
      summary: Get Environments Terminate
      description: Get environments terminate.
      operationId: getEnvironmentsTerminate
      x-api-path-slug: environmentsidterminate-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environments
      - Terminate
  /environments/all/terminate:
    get:
      summary: Get Environments All Terminate
      description: Get environments all terminate.
      operationId: getEnvironmentsAllTerminate
      x-api-path-slug: environmentsallterminate-get
      responses:
        200:
          description: OK
      tags:
      - Environments
      - ""
      - Terminate
  /environments/{id}/rename/{newName}:
    get:
      summary: Get Environments Rename Newname
      description: Get environments rename newname.
      operationId: getEnvironmentsRenameNewname
      x-api-path-slug: environmentsidrenamenewname-get
      parameters:
      - in: path
        name: id
        description: The ID of the environment to rename
      - in: path
        name: newName
        description: The new name to assign to the environment
      responses:
        200:
          description: OK
      tags:
      - Environments
      - Rename
      - Newname