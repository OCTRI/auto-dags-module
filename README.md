# auto-dags-module
A REDCap External Module that automatically creates, renames, and assigns records to DAGs based on a specified field.

### Note
This module will generate an error in projects using it when editing records with repeating forms or events.
```
Multiple instances are not currently supported!
```

This error does not prevent the record from being saved, but will result in an email to the project administrator.
