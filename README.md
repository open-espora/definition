# Open-Espora

This is a content management proposal for learning material (courses, workshops, tutorials, etc.).

## Conventions

1. `espora.json` file must contains relevant information about the learning material. The valid fields are:
  * name (String): Name of the learning material.
  * mentors (person[]): Objects that contains the mentors information.
  * collaborators (person[]): Objects that contains the collaborators information.
2. `content` folder must have language folders to separate the course content by languages.
3. `content/<lang>` folder can have the markdown files with the learning material or a folder structure with the learning material.
4. The file naming conventions for files/folders is:
  * Order Prefix: a number to define the position of the content/folder.
  * A lodash (_): a separator between number and file name.
  * if you have spaces in your file name replace it by underscores (_).
5. Repo information:
  * Repo title: The name of the learning material.
  * Repo about information: The learning material abstract.
  * Repo topics: The learning material categories to clasify the content.

## NOTES

* Relevant tutor(s) and/or collaborator(s) information could be extracted from users repository.
