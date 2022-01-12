# Go API client for openapi

No description provided (generated by Openapi Generator https://github.com/openapitools/openapi-generator)

## Overview
This API client was generated by the [OpenAPI Generator](https://openapi-generator.tech) project.  By using the [OpenAPI-spec](https://www.openapis.org/) from a remote server, you can easily generate an API client.

- API version: 1.0.0
- Package version: 1.0.0
- Build package: org.openapitools.codegen.languages.GoClientCodegen

## Installation

Install the following dependencies:

```shell
go get github.com/stretchr/testify/assert
go get golang.org/x/oauth2
go get golang.org/x/net/context
go get github.com/antihax/optional
```

Put the package under your project folder and add the following in import:

```golang
import "./openapi"
```

## Documentation for API Endpoints

All URIs are relative to *http://localhost/ga4gh/wes/v1*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*WorkflowExecutionServiceApi* | [**CancelRun**](docs/WorkflowExecutionServiceApi.md#cancelrun) | **Post** /runs/{run_id}/cancel | Cancel a running workflow.
*WorkflowExecutionServiceApi* | [**GetRunLog**](docs/WorkflowExecutionServiceApi.md#getrunlog) | **Get** /runs/{run_id} | Get detailed info about a workflow run.
*WorkflowExecutionServiceApi* | [**GetRunStatus**](docs/WorkflowExecutionServiceApi.md#getrunstatus) | **Get** /runs/{run_id}/status | Get quick status info about a workflow run.
*WorkflowExecutionServiceApi* | [**GetServiceInfo**](docs/WorkflowExecutionServiceApi.md#getserviceinfo) | **Get** /service-info | Get information about Workflow Execution Service.
*WorkflowExecutionServiceApi* | [**ListRuns**](docs/WorkflowExecutionServiceApi.md#listruns) | **Get** /runs | List the workflow runs.
*WorkflowExecutionServiceApi* | [**RunWorkflow**](docs/WorkflowExecutionServiceApi.md#runworkflow) | **Post** /runs | Run a workflow.


## Documentation For Models



## Documentation For Authorization

 Endpoints do not require authorization.



## Author


