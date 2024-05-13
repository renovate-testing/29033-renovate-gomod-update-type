# Description

The Go mod dependency `google.golang.org/genproto/googleapis/rpc` is now considered as a `patch` update as before it was seen as a `digest` update type. 

The change was introduced at release `37.327.1`.

## 37.327.0

Check the `updateType`.
```
DEBUG: Branch summary (repository=api-gateway/test)
       "cacheModified": undefined,
       "baseBranches": [{"branchName": "master", "sha": "d3b2a5c7e83004dc75ef21de93d6e95e618e15c4"}],
       "branches": [],
       "defaultBranch": "master",
       "inactiveBranches": ["renovate/google.golang.org-genproto-googleapis-rpc-digest"]
DEBUG: branches info extended (repository=api-gateway/test)
       "branchesInformation": [
         {
           "branchName": "renovate/google.golang.org-genproto-googleapis-rpc-digest",
           "prNo": null,
           "prTitle": "chore(deps): update google.golang.org/genproto/googleapis/rpc digest to 6275950",
           "result": "no-work",
           "upgrades": [
             {
               "datasource": "go",
               "depName": "google.golang.org/genproto/googleapis/rpc",
               "displayPending": "",
               "fixedVersion": "v0.0.0-20240506185236-b8a5c65736ae",
               "currentVersion": "v0.0.0-20240506185236-b8a5c65736ae",
               "currentValue": "v0.0.0-20240506185236-b8a5c65736ae",
               "currentDigest": "b8a5c65736ae",
               "newValue": "v0.0.0-20240506185236-b8a5c65736ae",
               "newDigest": "62759503f4344226051f4e24858a7517e45b4ae6",
               "packageFile": "go.mod",
               "updateType": "digest",
               "packageName": "google.golang.org/genproto/googleapis/rpc"
             }
           ]
         }
       ]
```

## 37.327.1

Check the `updateType`.

```
DEBUG: Branch summary (repository=api-gateway/test)
       "cacheModified": undefined,
       "baseBranches": [{"branchName": "master", "sha": "d3b2a5c7e83004dc75ef21de93d6e95e618e15c4"}],
       "branches": [],
       "defaultBranch": "master",
       "inactiveBranches": ["renovate/google.golang.org-genproto-googleapis-rpc-0.x"]
DEBUG: branches info extended (repository=api-gateway/test)
       "branchesInformation": [
         {
           "branchName": "renovate/google.golang.org-genproto-googleapis-rpc-0.x",
           "prNo": null,
           "prTitle": "chore(deps): update module google.golang.org/genproto/googleapis/rpc to v0.0.0-20240509183442-62759503f434",
           "result": "no-work",
           "upgrades": [
             {
               "datasource": "go",
               "depName": "google.golang.org/genproto/googleapis/rpc",
               "displayPending": "",
               "fixedVersion": "v0.0.0-20240506185236-b8a5c65736ae",
               "currentVersion": "v0.0.0-20240506185236-b8a5c65736ae",
               "currentValue": "v0.0.0-20240506185236-b8a5c65736ae",
               "currentDigest": "b8a5c65736ae",
               "newValue": "v0.0.0-20240509183442-62759503f434",
               "newVersion": "v0.0.0-20240509183442-62759503f434",
               "newDigest": "62759503f434",
               "packageFile": "go.mod",
               "updateType": "patch",
               "packageName": "google.golang.org/genproto/googleapis/rpc"
             }
           ]
         }
       ]
```
