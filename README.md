# Fundamentos docker 🐳
## Projeto elaborado no curso ***DOCKER - COD3R***

<br>
<p float="left">
 <img src="https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white">
 <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white">
 <img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=darkgreen">
 <img src="https://img.shields.io/badge/Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white">
</p>
<br>

## Ideia: 💡
Criar um imagens utilizando o docker para entender conceitos básicos da ferramenta.

## Funcionalidades:
- Dockerfile para imagem do **Python**;
- Dockerfile para imagem do **Debian**;
- Dockerfile para imagem do **Nginx**.

## Executando o projeto: 🚀
Para executar e visualizar o projeto em **modo de desenvolvimento**, você precisará seguir as próximas etapas.

### Pré-requisitos:
Abaixo estará listada as ferramentas necessárias para o funcionamento do projeto.
- **Docker** 🐳<br>
  [Guia de instalação docker](https://docs.docker.com/get-docker/).
  
### Executando o projeto:
Os scripts abaixo executam a compilação do projeto.
  ```sh
   docker image build -t nomedaimagem caminhoDoArquivoDockerfile 
   ```
   ###### Comando para executar o build das imagens passando o caminho do arquivo

---
## Links: 🌐
***Curso Cod3er:***<br>
[<ins>Docker: Ferramenta essencial para Desenvolvedores</ins>](https://www.cod3r.com.br/courses/docker)

***Imagens utilizadas:***<br>
[<ins>Debian image</ins>](https://hub.docker.com/_/debian) 
<br>
[<ins>Python image</ins>](https://hub.docker.com/_/python) 
<br>
[<ins>Nignx image</ins>](https://hub.docker.com/_/nginx) 

---
## Licença
Este projeto está licenciado sob a licença [MIT] - consulte o arquivo LICENSE.md para obter detalhes
