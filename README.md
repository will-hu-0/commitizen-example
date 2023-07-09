# commitizen, commitlint, husky examples

`Husky`, `Commitlint`, and `Commitizen` are popular tools used in software development, particularly in projects that follow the Git version control system and adhere to commit message conventions.

| Tool | Comments |
|:--|:--
| Commitlint | enforce commit message conventions in a Git repository, it integrates with Git hooks |
| Husky | allows you to add Git hooks in your project to enforce certain rules or execute custom scripts (e.g. Commit message conventions check) |
| Commitizen | a command-line utility that helps you create commit messages following the conventional commit format |

## Get started

```
# Install dependencies and init husky
npm install & npm run prepare
```

## Try a commit message not following the conventional commit format

```
touch foo.txt
git add foo.txt
git commit -m "foo"
```
