# Obsidian vault opinionated PARA boilerplate

## Design considerations

- PARA method supplemented with an *Inbox*
- Archives close to original content (`_archive` directories)
- Obsidian core plugins only

### Meeting notes

- Must accommodate for meeting-heavy workflows with multiple parallel projects
- Meeting note archival takes place when:
- File name format: ISO 8601 date (YYYY-MM-DD) followed by the meeting title. This, however, necessitates the use of a per-folder sort direction in the File Explorer, in order to avoid excess scrolling;

## Folder structure

### 0 Inbox

- An Inbox layer inspired by GTD (Getting Things Done).
- It's an **unprocessed holding area** — a place where you quickly capture new ideas, tasks, or information before deciding where they belong in PARA.
- Later, during review, you process the inbox contents:
  - Move actionable items to a *Project*
  - Assign ongoing items to an *Area*
  - Store useful info in *Resources*
  - Delete or *Archive* what's not needed
- Adding an Inbox to PARA solves PARA’s main weakness: PARA assumes you always know where something belongs.
- This combination provides:
  - Low friction capture (Inbox)
  - High-clarity structure (PARA)
  - A clear review flow: Inbox → Project / Area / Resource / Archive

### 3 Resources/_templates

#### Architecture

- For modeling software or service architectures. Links together a series of Component notes.

#### Associate

- A person, in a professional context.

#### Component

- Allows for modeling of individual software components or services. Here, service modeling is about domain-driven design and decomposing systems.

#### Organization

- A company, group, etc.

#### Team

- Links together a series of Associate notes.
