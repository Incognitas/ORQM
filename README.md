# ORQM

## INTRODUCTION

Open Req Manager

Because managing requirements and associated tests should not be painful !
Trying to make a simple tool to manage this.

Base data to know on this:

- use C++
- Use Qt for multi OS support
- QML used for GUI 
- use SQL:
  - sqlite first
  - other engines later (thanks to QtSql abstraction for easier addition of engines)

## TODO / WISHLIST

What is to be expected from this tool (for now):

- Add/remove users
- Add/remove projects (name, description, date added)
- Add/remove tests (name, description, date added, status ?)
- Create/delete requirements (in terms of name, description, date of creation, date of addition to a project, date of removal of a project if any, associated tests etc)
- Add/remove requirements to/from a specific project
- Report generation containing :
  - the list of requirements associated to this project
  - the list of associated tests if asked
  - etc (list to be completed)
- Possibility to have a log of all modifications performed on the database. This will allow users to fetch:
  - modifications between two dates for a given project (more options to define)
  - additions/removals/updates for all elements


TODO: update this document for more formal content

