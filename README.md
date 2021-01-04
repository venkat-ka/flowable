# flowable

Flowable Docs Startedhttps://flowable.com/open-source/docs/bpmn/ch02-GettingStarted/
http://localhost:8091/runtime/process-instancesReq
To Create Task

{ "processDefinitionKey": "riskregisterdata", "variables": [ { "name": "myyy Holiday first", "type": "string", "value": "cccc vvvvvv nnnnnnnnnnnn", }]}To get process instance id which is cordinate to task single or multiple tasks those are co-ordinate to tprocessid and keyhttp://localhost:8091/runtime/process-instances?processDefinitionKey=riskregisterdataRes{
    "data": [
        {
            "id": "855c95f4-4d03-11eb-95ca-e60e3a30c293",
            "url": "http://localhost:8091/runtime/process-instances/855c95f4-4d03-11eb-95ca-e60e3a30c293",
            "name": null,
            "businessKey": null,
            "suspended": false,
            "ended": false,
            "processDefinitionId": "riskregisterdata:1:7776aacf-4cd6-11eb-9e16-e60e3a30c293",
            "processDefinitionUrl": "http://localhost:8091/repository/process-definitions/riskregisterdata:1:7776aacf-4cd6-11eb-9e16-e60e3a30c293",
            "processDefinitionName": "RiskRegister",
            "processDefinitionDescription": "Risk Register data Review",
            "activityId": null,
            "startUserId": null,
            "startTime": "2021-01-02T19:35:08.261+05:30",
            "variables": [],
            "callbackId": null,
            "callbackType": null,
            "referenceId": null,
            "referenceType": null,
            "tenantId": "",
            "completed": false
        },
        {
            "id": "ecb62cdd-4d01-11eb-95ca-e60e3a30c293",
            "url": "http://localhost:8091/runtime/process-instances/ecb62cdd-4d01-11eb-95ca-e60e3a30c293",
            "name": null,
            "businessKey": null,
            "suspended": false,
            "ended": false,
            "processDefinitionId": "riskregisterdata:1:7776aacf-4cd6-11eb-9e16-e60e3a30c293",
            "processDefinitionUrl": "http://localhost:8091/repository/process-definitions/riskregisterdata:1:7776aacf-4cd6-11eb-9e16-e60e3a30c293",
            "processDefinitionName": "RiskRegister",
            "processDefinitionDescription": "Risk Register data Review",
            "activityId": null,
            "startUserId": null,
            "startTime": "2021-01-02T19:23:42.660+05:30",
            "variables": [],
            "callbackId": null,
            "callbackType": null,
            "referenceId": null,
            "referenceType": null,
            "tenantId": "",
            "completed": false
        }
    ],
    "total": 2,
    "start": 0,
    "sort": "id",
    "order": "asc",
    "size": 2
    
    
}Task Update or CreateURL http://localhost:8091/runtime/process-instances/855c95f4-4d03-11eb-95ca-e60e3a30c293/variablesReq[{ "name": "third var ch", "scope": "local", "type": "string", "value": "thir valueeee" }] Res[ { "name": "third var ch", "type": "string", "value": "thir valueeee", "scope": "local" }]Note : third var ch if it same overwrite or create





http://localhost:8091/runtime/process-instances
Req
To Create Task

{
  "processDefinitionKey": "riskregisterdata",
  "variables": [
    {
      "name": "myyy Holiday first",
      "type": "string",
      "value": "cccc vvvvvv nnnnnnnnnnnn",     
    
  }]
}


http://localhost:8091/runtime/process-instances?processDefinitionKey=riskregisterdata

Res
{
    "data": [
        {
            "id": "855c95f4-4d03-11eb-95ca-e60e3a30c293",
            "url": "http://localhost:8091/runtime/process-instances/855c95f4-4d03-11eb-95ca-e60e3a30c293",
            "name": null,
            "businessKey": null,
            "suspended": false,
            "ended": false,
            "processDefinitionId": "riskregisterdata:1:7776aacf-4cd6-11eb-9e16-e60e3a30c293",
            "processDefinitionUrl": "http://localhost:8091/repository/process-definitions/riskregisterdata:1:7776aacf-4cd6-11eb-9e16-e60e3a30c293",
            "processDefinitionName": "RiskRegister",
            "processDefinitionDescription": "Risk Register data Review",
            "activityId": null,
            "startUserId": null,
            "startTime": "2021-01-02T19:35:08.261+05:30",
            "variables": [],
            "callbackId": null,
            "callbackType": null,
            "referenceId": null,
            "referenceType": null,
            "tenantId": "",
            "completed": false
        },
        {
            "id": "ecb62cdd-4d01-11eb-95ca-e60e3a30c293",
            "url": "http://localhost:8091/runtime/process-instances/ecb62cdd-4d01-11eb-95ca-e60e3a30c293",
            "name": null,
            "businessKey": null,
            "suspended": false,
            "ended": false,
            "processDefinitionId": "riskregisterdata:1:7776aacf-4cd6-11eb-9e16-e60e3a30c293",
            "processDefinitionUrl": "http://localhost:8091/repository/process-definitions/riskregisterdata:1:7776aacf-4cd6-11eb-9e16-e60e3a30c293",
            "processDefinitionName": "RiskRegister",
            "processDefinitionDescription": "Risk Register data Review",
            "activityId": null,
            "startUserId": null,
            "startTime": "2021-01-02T19:23:42.660+05:30",
            "variables": [],
            "callbackId": null,
            "callbackType": null,
            "referenceId": null,
            "referenceType": null,
            "tenantId": "",
            "completed": false
        }
    ],
    "total": 2,
    "start": 0,
    "sort": "id",
    "order": "asc",
    "size": 2
}



