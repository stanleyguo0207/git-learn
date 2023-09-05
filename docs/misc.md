-   git config

    ```
    git config --list --show-origin
    ```

    -   system
        ```
        /etc/gitconfig
        ```
    -   global
        ```
        ~/.gitconfig
        ```
    -   local
        ```
        .git/config
        ```
-   git log

    ```
    git log --pretty=format:"%h %s" --graph
    ```

-   git archive

    ```
    git archive master --prefix='git-learn/' | gzip > `git describe master`.tar.gz
    ```

-   git shortlog

    ```
    git shortlog --no-merges master --not v0.0.1
    ```