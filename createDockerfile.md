# Dockerfile

Modemo de Dockerfile
```
FROM ubuntu
RUM apt update && apt install curl --yes
```

## Opções de uso no Dockerfile
`FROM` -> Inicializa o build de uma imagem docker a partir de uma imagem base existente. <br>
`WORKDIR` -> Define direitório corrente <br>
`RUN` -> Executa um comando <br>
`LABEL` -> Adicona metadados a imagem <br>
`EXPOSE` -> Define que o container presisa expor determinada porta <br>
`ENV` -> Defina variável de ambiente <br>
`COPY` -> Copia arquivos ou diretórios e adiciona ao sistema de arquivos da imagem <br>
`ADD` -> Copia arquivos ou diretórios remotos e adiciona ao sistema de arquivos da imagem <br>
`CMD` -> Define o comando e/ou os parâmetros padrão <br>
`ARG` -> Define um argumento para ser usando no processo de construção da imagem <br>
`ENTRYPOINT` ->  Ajuda você a configurar um container que pode ser executado como um executável. <br>
`VOLUME` -> Define volumes que devem ser definidos <br>

<style>
code {
  color: #4ED0FB
}

h1, h2, h3 {
  color: #58C
  }

body{
    color: #D4D4D4;
    font-size: 15px
}

</style>