# GitHub Label Maker

## Task

Create a program that will create a certain set of labels on a given GitHub repository. 

### Input parameters

- GitHub repository owner
- GitHub repository name

## Semantics

Terms the client program has to understand in order to fulfill the task:

- `repository`
-  `owner`
- `labels`
- `label`
- `color` (in `label` context)
- `name` (in `label` context)

## Workflow

1. Retrieve `repository` name from program user
2. Retrieve repository `owner` from program user
3. Connect to GitHub API root
4. Look for the `repository` transition
5. Exercise `repository` transition with `repository` name and `owner` as parameters*
6. Look for `labels` transition
