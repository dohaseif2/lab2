- Remove Local Branch:
 git branch -d branch_name
- if not merged:
git branch -D branch_name


- Delete a remote branch:
  git push origin --delete branch_name
  (or)
  git push origin :branch_name

- to list tags:
git tag


- to delete tag locally remotely:
git tag -d your_tag_name
- to delete tag remotely:
git push origin --delete your_tag_name

