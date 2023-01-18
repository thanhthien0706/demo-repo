# demo-repo

Some Description

## Subheader

- B1: Create branch main
- B2: Create branch develop, git push -u origin develop
- B3: After the leader assigns the issues, developer create new branch with name branch `{label}/{number}-(add,update,delete)-{name-task}` on branch develop.
    Demo: git checkout -b feature/2-add-cart.model-file develop
- B4: After done feature, use git add file... /
- B5: Use git commit -m `{number} - {Name issues}` / Demo: git commit -m "#2 - ThanhThien create cart.model.js file"
- B5: git push | git push --set-upstream origin feature/2-add-cart.model-file
- B6: Comparing changes on github. /Demo: write write #number . and create pull request
- B7: Create branch release : git checkout -b release-1.0.0 develop
- B8: Create tag name : git tag 'v1.0.0' and push : git push --tags