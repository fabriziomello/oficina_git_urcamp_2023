# Introduçao ao Git

## Criar um novo repositório local vazio
Na linha de comando do seu Linux digite o que segue:
```bash
mkdir <nome_do_repositorio>
cd <nome_do_respositorio>
git init
```

## Como verificar o status do meu repositório
Estando dentro do diretório do projeto digite o seguinte comando:
```bash
git status
```

## Como adicionar uma nova mudança no repositório
Após verificar o status do repositório e identificar que existem artefatos pendentes para efetivação ("commit") devemos executar os seguintes comandos:
```bash
git add <arquivo>
git commit -m "Mensagem"
```
