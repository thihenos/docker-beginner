# docker-beginner

Estrutura de pastas:
```bash
├── app                 # app folder
│   ├── package.json    # package.json
│   └── index.js        # simple application
├──.dockerignore        # dockerignore
├──.gitignore           # gitignore
├── Dockerfile          # Dockerfile
└── README.md           # this file
```

# Comandos principais:
Comando para criar o build da imagem com o Dockerfile
```bash
docker build -t user/docker-node:0.1 .
```

Comando para iniciar o container
```bash
docker run --name docker-test user/docker-node:0.1 sh
```

License
----
MIT
**Free Software, Free Examples, Free hugs!**
