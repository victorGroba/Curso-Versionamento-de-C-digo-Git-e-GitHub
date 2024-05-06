
# DIO | Resumos Git e GitHub

Repositórios para armazenar resumos sobre Git e GitHub do curso Versionamento de  Código Git e GitHub - Bootcamp Santander da [Digital Innovation One](https://web.dio.me/track/santander-2024-fundamentos-de-ia-para-devs?tab=about)



## 📚 Documentação
- [Documentação Git](https://git-scm.com/doc)
- [Documentação GitHub](https://docs.github.com/pt)

## 💻 Comandos Úteis

### Configurações


| Definir Usuário | 
|------------------------------------------|

```
git config --global user.name "victorGroba"
```
| Definir E-mail | 
|------------------------------------------|

```
git config --global user.email victorgroba2@gmail.com
```

| Setar arquivos a serem ignorados | 
|------------------------------------------|

```
git config --global core.excludesfile ~/.gitignore
```
| Listar configurações | 
|------------------------------------------|

```
git config --list
```

- Ignorar Arquivos
Os nomes de arquivos/diretórios ou extensões de arquivos listados no arquivo .gitignore não serão adicionados em um repositório. Existem dois arquivos .gitignore, são eles:

Geral: normalmente armazenado no diretório do usuário do Sistema Operacional. O arquivo que possui uma lista de arquivos/diretórios a serem ignorados por todos os repositórios deverá ser declarado conforme citado acima. O arquivo não precisa ter o nome de .gitignore .

Por repositório: Deve ser armazenado no diretório do repositório e deve conter a lista dos arquivos/diretórios que devem ser ignorados apenas para o repositório específico.

### Repositório Local

|Criar novo repositório|
|----------------------|

```
git init
```


|Verifique o estado dos arquivos/diretórios|
|----------------------|

```
git status
```


|Adicionar arquivo/diretório (área preparada)|
|----------------------|

- Adicionar um arquivo específico
```
git add meu_arquivo.txt
```

- Adicionar um diretório específico

```
git add meu_diretorio
```

- Adicionar todos os arquivos/diretórios

```
git add .	
```

- Adicione um arquivo que está listado no .gitignore (geral ou do repositório)

```
git add -f arquivo_no_gitignore.txt
```
# dio-resumos-git-e-github
