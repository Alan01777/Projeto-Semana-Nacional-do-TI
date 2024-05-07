# Pipeline CI/CD com GitHub Actions para Projeto da Semana Nacional de TI

Este é um guia passo-a-passo para configurar uma pipeline CI/CD utilizando GitHub Actions para o projeto da Semana Nacional de TI.

## Descrição

Este projeto visa automatizar o processo de integração contínua e entrega contínua (CI/CD) para facilitar o desenvolvimento e a entrega de software.

## Pré-requisitos

-   Conta no GitHub (com [chave SSH configurada](https://docs.github.com/pt/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account))
-   IDE configurada (ex: [VSCode](https://code.visualstudio.com/download))
-   Conta no [DockerHub](https://hub.docker.com/)
-   (Opcional) Docker instalado

## Configuração Inicial

1. Crie seu próprio repositório no GitHub.
2. Clone o repositório atual:

    ```bash
    git clone https://github.com/Alan01777/Projeto-Semana-Nacional-do-TI.git
    ```

3. Exclua a pasta .git:

    - Windows:

    ```bash
    Remove-Item -Recurse -Force .git\
    ```

    - Linux:

    ```bash
    rm -rf .git/
    ```

4. Adicione seu repositório do GitHub ao projeto atual. Por exemplo:
    ```bash
    git init
    git add .
    git commit -m "first commit"
    git branch -M main
    git remote add origin <url-do-seu-repositorio>
    git push -u origin main
    ```

## Extras

### Link do projeto completo e comentado

-   Link do repositório com o projeto comentado: [link](https://github.com/Alan01777/CI-CD---Semana-TI)
-   Link da imagem construida no dockerhub: [link](https://hub.docker.com/r/alan01777/semana-nacional-ti/tags)

### Instalando o Docker

-   Windows: [Download](https://www.docker.com/products/docker-desktop/)
-   Linux:
    ```bash
    curl -ssL get.docker.com | bash
    ```
