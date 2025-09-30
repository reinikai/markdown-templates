```base
views:
  - type: table
    name: Table
    filters:
      and:
        - file.path.startsWith("3 Resources/People/")
        - '!file.name.startsWith("+")'
```