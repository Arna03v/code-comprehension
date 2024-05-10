Assume that the multiple different code bases inside the codbase folder are all diff folders of the same coedebase

That was the summaries fodler can work with a larger codebase as well

-> make a bash script to init the same folder structure as the code base?
-> add return types, code examples  to the jsons?
-> potentially add an import section in the jsons

A sample json
```
{
  "filePath": "file_name.py",
  "fileDescription": "Brief description of the Python file's purpose.",
  "functions": [
    {
      "name": "function_name",
      "summary": "Brief summary describing what the function does.",
      "parameters": [
        {
          "name": "parameter_name",
          "type": "parameter_type",
          "description": "Brief description of the parameter's purpose."
        },
        ...
      ]
    },
    ...
  ]
}
```

-> havent added jsons for simplecon v3 and v4 as it was time taking and repetitive