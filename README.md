<p align="center">
    <img src="http://www.connect4sell.com/img/avatar-ifcmaravilhas.20bab9b4.jpg">
</p>
<h5 align="center">Aqui temos todos os códigos do novo site. Antes de sair copiando, entenda a estrutura das pastas:</h6>
<br />

```text
assets/
├── css/
├── images/
├── js/
```

**Assets**: Pasta onde estarão todos as imagens, estilos e arquivos JavaScript da nossa aplicação.
**Images**: Toda e qualquer imagem deverá estar dentro da pasta images.
**JS**: Todos os arquivos JavaScript deverão estar nessa pasta.
**CSS**: Todos os arquivos de estilo.

<br>
## Bootstrap 4.4
Estamos utilizando o boostrap para nos auxiliar no desenvolvimento do layout responsivo e em alguns pontos importantes para agilizar o nosso processo de desenvolvimento.

[Clique aqui](https://getbootstrap.com/docs/4.4/getting-started/introduction/) e veja a documentação completa do Bootstrap

<br>
## Fluxo de trabalho
Temos algumas 2 branchs principais:
- master
- develop

Sempre que você for absorver alguma demanda, criar sua branch a partir da **develop**. Para fazer isso corretamente você deverá ir até a branch develop usando o seguinte comando: 
```text
git checkout develop
```

Agora digite o seguinte comando para criar uma nova branch
```text
git branch feature/nove_da_sua_branch
```
ou

```text
git checkout -b feature/nove_da_sua_branch
```
<br>
Agora que você criou uma branch nova a partir da develop, você pode começar a programar sua tarefa. **Não esqueça de commitar(subir as versões da sua branch) sempre que finalizar trechos da sua tarefa**. Para fazer isso rode as etapas a seguir:
```text
git status
git commit -am "digite dentro das aspas duplas o que você fez, sempre no gerúndio. Por exemplo: Criando o header responsivo"
git push origin feature/nome_da_sua_branch
```