# Legendas

---

```%``` => Explicação sobre tópicos
```#``` => Comentarios sobre os comandos
```$``` => Comentarios sobre comandos em geral

---

%Branch são versões diferente do sistema 

%Commit quando faz alterações, cria arquivos novos, deletando arquivos explicar oque foi feito sempre quando commitar 

---

```
git config --global user.name "Johnny"
```
##### Quem vai mexer na maquina o nome da maquina.
```
git config --global user.email "jhonatanfeijo98@gmail.com"
```
##### Email de quem vai mexer.

```
git config --global core.editor ...
```
##### Editor que estou utilizando.

```
git config user.name
```
##### Vai ler o nome que está cadastrado na maquina.

```
git config user.email
```
##### Vai ler o email que está cadastrado na maquina.

```
git config --list
```
##### Irá mostrar tudo que está cadastrado.

```
git init
```
##### Para iniciar o repositório.

```
git status
```
##### Vai fazer uma varredura na pasta oque foi modificado, ou alterado.

```
git add (README.md)
```
##### Adiciona para crackear no git.

```
git add -A
```
##### Adiciona crackear tudo no git.

```
git commit -m ""
```
##### Vai commitar as modificações.

```
git log
```
##### Vai ver a listas de todos os commit que foram feitos.

```
git branch
```
##### Vai listar todos os comandos dos branchs do projeto oque que tiver o * vai ser o oque está no momento.

```
git commit -am ""
```

##### Vai crackear e commitar as modificações.

```
git reset --soft => --mixed => --hard
```
##### Faz um reset se der algum bug usar o soft para remove. Evitar o maximo o hard.

```
git checkout ()
```
##### Para trocar de branches.

```
git remote add origin URL
```
##### Adiciona remoto ao local, indica a origem do repositorios.

```
git remote
```
##### Mostra que exite um oring adicionado.

```
git remote -v
```
##### Mostra mais detalhes

##### (Fetch) é a capacidade de puxar o conteudo que está no repositório REMOTO => LOCAL
##### (Push) é levar o conteudo do repositório LOCAL => REMOTO

```
git (fetch ou push) -u origin master 
```
##### Vai tranferir o arquivos para repositório da forma do destino '-u' => Complemento do comando 'origin' => Destino do repositório 'master' => Qual o branch que 
vou enviar do meu repositório

---

```
cd C:
```
##### ```$Vai entrar na pasta principal do computador.```

```
cd (DIRETÓRIO)
```
##### ```$Vai ir até a pasta solicitada.```

```
cd ..
```
##### ```$Volta o diretório.```

```
mkdir__
```
##### ```$Vai criar uma pastas com o nome de sua escolha.```
