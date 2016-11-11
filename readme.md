
```
python importissues.py config.ini lastThreadProcessed.txt syn2580853 87

```

Where:

config.ini is a file of the form:
```
[synapse]
username: ...
apiKey: ...

[github]
token: ...
```


lastThreadProcessed.txt is a writable file containing the ID of the last thread previously processed;

syn2580853 is the Synapse ID of the project to process

87 is the ID of the forum object in the aforementioned project
