## CleverTap golang csv upload tool

##Usage:
```
  -csv string               Absolute path to the csv file
  
  -id string                CleverTap Account ID
  
  -p string                 CleverTap Account Passcode
  
  -t string                 The type of data, either profile or event, defaults to profile (default "profile")
  
  -evtName string           Event name. Required only when uploading events. Each CSV file can only have one type of event
  
  -dryrun                   Do a dry run, process records but do not upload
  
```

NOTE:  you must include one of identity, objectID, FBID or GPID, in your data.  Email addresses can serve as an identity value, but the key must be identity.