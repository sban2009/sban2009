```mermaid
  graph TD;
      Edit-->Docs;
      Edit-->Pages;
      Docs-->RaisePR1;
      Pages-->RaisePR2;
      RaisePR1-->Merge;
      RaisePR2-->Merge;
```
