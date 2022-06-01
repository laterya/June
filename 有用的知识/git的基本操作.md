## 本地仓库推送到远程仓库

-   `git remote add `添加远程仓库

    ```
    git romote add origin git@……
    ```

    新建一个空的远程仓库时最后会提醒这一段

    git会自动将远程仓库的名称设置为origin

-   `git push`推送至远程仓库

    -   推送master分支：在master分支下进行操作

        ```
        git push -u origin master
        ```

        当前分支的内容就会被推送给远程仓库的master分支

    -   推送至`master`以外的分支

        ```
        git push -u origin feature(分支名)
        ```

## 仓库更新

-   远程仓库更新使用`git pull origin master`即可拉取最新内容
-   本地仓库更新使用`git push -u origin master`即可更新至远程仓库