- Iniciando

    ```bash
    git flow init
    ```

- Iniciando uma feature

    ```bash
    git flow feature start <NOME_DA_FEATURE>
    ```

- Finalizando a feature

    ```bash
    git flow feature finish <NOME_DA_FEATURE>
    ```

- Iniciando uma release

    ```bash
    git flow release start 1.0.1
    ```

- Primeiro, crie a tag com uma mensagem:

    ```bash
    git tag -a v1.0.1 -m "Release version 1.0.1"
    ```


- Fazendo o push das tags

    ```bash
    git push --tags
    ```

- Finalizando a release

    ```bash
    git flow release finish 1.0.1
    ```
