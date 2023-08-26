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