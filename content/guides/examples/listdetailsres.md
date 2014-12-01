---
title: Search Results
parent: resultlistdetails
order: 1
---
### The response:
- HTTP/1.1 200 OK: (Success)
- HTTP/1.1 401 Unauthorized: Your username or your password is wrong
- HTTP/1.1 404 NOT found: The url doesn't exist

After a successful request, the response consists of a list of PIDs containing this term.

<pre><code>
{
"/handles/11239/51E3506B-01EB-4061-92E9-7B22EA431890":[
{
"idx":1,
"type":"URL",
"parsed_data":"http://www.grnet.gr/",
"data":"aHR0cDovL3d3dy5ncm5ldC5nci8=",
"timestamp":"2013-11-26T15:17:15Z",
"ttl_type":2,
"ttl":"1970-01-02T00:00:00Z",
"refs":[],
"privs":"rwr-"
},
{
"idx":2,
"type":"URL",
"parsed_data":"https://www.grnet.gr/en/node/64",
"data":"aHR0cHM6Ly93d3cuZ3JuZXQuZ3IvZW4vbm9kZS82NA==",
"timestamp":"2013-11-26T15:17:15Z",
"ttl_type":0,
"ttl":86400,
"refs":[],
"privs":"rwr-"
},
{
"idx":3,
"type":"INST",
"parsed_data":"GRNET",
"data":"Q0xBUklOLUVM",
"timestamp":"2013-11-26T15:17:15Z",
"ttl_type":0,
"ttl":86400,
"refs":[],
"privs":"rwr-"
},
{
"idx":100,
"type":"HS_ADMIN",
"parsed_data":{
"adminId":"0.NA/11239",
"adminIdIndex":300,
"perms":{
"add_handle":true,
"delete_handle":true,
"add_naming_auth":false,
"delete_naming_auth":false,
"modify_value":true,
"remove_value":true,
"add_value":true,
"read_value":true,
"modify_admin":true,
"remove_admin":true,
"add_admin":true,
"list_handles":false
}
},
"data":"B/MAAAAKMC5OQS8xMTIzOQAAASw=",
"timestamp":"2013-11-26T15:17:15Z",
"ttl_type":0,
"ttl":86400,
"refs":[],
"privs":"rwr-"
}
],
"/handles/11239/2D2E3023-B1A9-4B39-91E0-52C2DADC9D57":[
{
"idx":1,
"type":"URL",
"parsed_data":"http://www.grnet.gr/",
"data":"aHR0cDovL3d3dy5ncm5ldC5nci8=",
"timestamp":"2013-12-06T09:17:30Z",
"ttl_type":1,
"ttl":"1970-01-02T00:00:00Z",
"refs":[],
"privs":"rwr-"
},
{
"idx":2,
"type":"URL",
"parsed_data":"https://www.grnet.gr/en/node/64",
"data":"aHR0cHM6Ly93d3cuZ3JuZXQuZ3IvZW4vbm9kZS82NA==",
"timestamp":"2013-12-06T09:17:30Z",
"ttl_type":0,
"ttl":86400,
"refs":[],
"privs":"rwr-"
},
{
"idx":3,
"type":"INST",
"parsed_data":"GRNET",
"data":"Q0xBUklOLUVM",
"timestamp":"2013-12-06T09:17:30Z",
"ttl_type":0,
"ttl":86400,
"refs":[],
"privs":"rwr-"
},
{
"idx":100,
"type":"HS_ADMIN",
"parsed_data":{
"adminId":"0.NA/11239",
"adminIdIndex":300,
"perms":{
"add_handle":true,
"delete_handle":true,
"add_naming_auth":false,
"delete_naming_auth":false,
"modify_value":true,
"remove_value":true,
"add_value":true,
"read_value":true,
"modify_admin":true,
"remove_admin":true,
"add_admin":true,
"list_handles":false
}
},
"data":"B/MAAAAKMC5OQS8xMTIzOQAAASw=",
"timestamp":"2013-12-06T09:17:30Z",
"ttl_type":0,
"ttl":86400,
"refs":[],
"privs":"rwr-"
}
],
"/handles/11239/CLARIN-1":[
{
"idx":1,
"type":"URL",
"parsed_data":"http://www.clarin.gr/",
"data":"aHR0cDovL3d3dy5jbGFyaW4uZ3Iv",
"timestamp":"2013-11-25T10:17:52Z",
"ttl_type":0,
"ttl":86400,
"refs":[],
"privs":"rwr-"
},
{
"idx":2,
"type":"INST",
"parsed_data":"GRNET",
"data":"Q0xBUklOLUVM",
"timestamp":"2013-11-25T10:17:52Z",
"ttl_type":0,
"ttl":86400,
"refs":[],
"privs":"rwr-"
},
{
"idx":100,
"type":"HS_ADMIN",
"parsed_data":{
"adminId":"0.NA/11239",
"adminIdIndex":300,
"perms":{
"add_handle":true,
"delete_handle":true,
"add_naming_auth":false,
"delete_naming_auth":false,
"modify_value":true,
"remove_value":true,
"add_value":true,
"read_value":true,
"modify_admin":true,
"remove_admin":true,
"add_admin":true,
"list_handles":false
}
},
"data":"B/MAAAAKMC5OQS8xMTIzOQAAASw=",
"timestamp":"2013-11-25T10:17:52Z",
"ttl_type":0,
"ttl":86400,
"refs":[],
"privs":"rwr-"
}
]
}
</code></pre>