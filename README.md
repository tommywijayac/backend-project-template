Simple structure for small to medium projects.

Concept:
* `cmd`: main and app initialization.
* `bin`: build output path.
* `config`: configs.
* `handler`: API name. Includes input validation and pre-processing.
* `usecase`: business logic.
* `repo`: data store or external services.
* `model`: structures and const.

For medium projects, in each domain, folders with a name defining the content should be created. Else, just use files.