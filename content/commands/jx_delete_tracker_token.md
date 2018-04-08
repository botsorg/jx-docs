---
date: 2018-04-08T21:24:37Z
title: "jx delete tracker token"
slug: jx_delete_tracker_token
url: /commands/jx_delete_tracker_token/
---
## jx delete tracker token

Deletes one or more api tokens for a user on an inssue tracker server

### Synopsis

Deletes one or more API tokens for your issue tracker from your local settings

```
jx delete tracker token [flags]
```

### Examples

```
  # Deletes an issie tracker user token
  jx delete tracker token -n jira myusername
```

### Options

```
  -h, --help          help for token
  -n, --name string   The name of the git server to add a user
  -u, --url string    The URL of the git server to add a user
```

### SEE ALSO

* [jx delete tracker](/commands/jx_delete_tracker/)	 - Deletes one or many issue tracker resources

###### Auto generated by spf13/cobra on 8-Apr-2018