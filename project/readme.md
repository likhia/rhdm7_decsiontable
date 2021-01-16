Repository Init Content
=======================

Your project description here.

Payload 
```
{
  "lookup": "default-stateless-ksession",
  "commands": [
    {
      "insert": {
        "object": {
          "com.myspace.sample.Request": {
            "port": 2000,
            "tier": "DB",
            "application": "SQL",
            "zone": "INTRANET"
          }
        },
        "out-identifier": "request"
      }
    },
    {
      "fire-all-rules": {}
    },
    {
      "get-objects": {
        "out-identifier": "objects"
      }
    },
    {
      "dispose": {}
    }
  ]
}
```
