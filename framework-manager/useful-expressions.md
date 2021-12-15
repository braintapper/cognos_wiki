# Useful Expressions



## Hours Between Timestamps

```
( unixtimestamp(currenttimestamp) - _unixtimestamp(shifttimezone ( ,'GMT', 'GMT') ) ) / 3600
IF ( [Hours Since Last Run] < 49 ) THEN ( [Hours Since Last Run] || ' hour(s) ago' ) ELSE ( round([Hours Since Last Run]/24,0) || ' day(s) ago' )
IF ( [Hours Since Last Run] < 49 ) THEN ( [Hours Since Last Run] || ' hour(s) ago' ) ELSE ( floor([Hours Since Last Run]/24) || ' day(s) ago' )
```

