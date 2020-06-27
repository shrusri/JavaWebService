# JavaWebService

** Launch the zip file on Tomcat server **
** Sql files are given in dump format to export in DB **

FETCH ALL EVENTS

http://localhost:8080/JSONRestWebServiceExample/dataEvents/fetchAllData

no form data. Get Method

Sample Response
{
    "STATUS": "SUCCESS",
    "RESULT": [
        {
            "createdDate": null,
            "data": "{ \"page\": \"pages\" }",
            "id": 1,
            "link": "link sample123",
            "type": "sample1"
        },
        {
            "createdDate": null,
            "data": "12",
            "id": 2,
            "link": "sac",
            "type": "cc"
        },
        {
            "createdDate": null,
            "data": "12",
            "id": 3,
            "link": "sac",
            "type": "cc"
        },
        {
            "createdDate": null,
            "data": "012",
            "id": 4,
            "link": "sac",
            "type": "cc"
        },
        {
            "createdDate": null,
            "data": "sdsd",
            "id": 5,
            "link": "pot",
            "type": "6s"
        }
    ]
}

SAVE EVENTS

http://localhost:8080/JSONRestWebServiceExample/dataEvents/saveData

POST method. Form data needed

data : "value";
link : "value";
type : "value"

Sample Response

{
    "STATUS": "SUCCESS"
}


For all jobs and events related activity Response will contain STATUS as SUCCESS or FAIL and RESULT will actually give the desired information or payload.

**Make sure the variable names are as mentioned in form data **
**Both Jobs and events have same variable name and structure **
