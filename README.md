# git_practice

收集關於我在使用Git遇到的各種問題!


### 刪除已 PUSH 的 Commit
【STEP】
1) 先把 HEAD 移至上一個或者想去的 Commit
    - 上一個: ```git reset HEAD^```
    - 上兩個: ```git reset HEAD^^```
    - 上五個: ```git reset HEAD~5```
    - 指定: ```git reset ffa7c0c```
2) 強制推上遠端
    ```git push -f```

> 參考來源: https://officeguide.cc/git-delete-commit-in-remote-branch-tutorial-examples/