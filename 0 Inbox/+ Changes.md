```base
version: 1
filters:
  # Only markdown files
  - file.ext = "md"

views:
  - type: table
    name: "Recently Modified"
    columns:
      - field: file.name
        label: File
      - field: file.folder
        label: Folder
      - field: file.mtime
        label: Last Modified
    order:
      - field: file.mtime
        desc: true
    limit: 20
```