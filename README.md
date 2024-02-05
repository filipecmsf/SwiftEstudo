### Manifesto

Este roteiro foi pensado em ser um guia nos estudos sobre git, swift, swiftUI e outros tópicos relacionados. Passando por conceitos de todos os níveis, que serão documentados aos poucos.

### <p id="indice">Indice</p>

1. <a href="#git">GIT</a>
    - <a href="#branch">Branch</a>
    - <a href="#remote">Local e remoto</a>
    - <a href="#gitFlow">Git Flow</a>
    - <a href="#commit">Commit</a>
    - <a href="#mr">Merge request e merge back</a> 
    - <a href="#conflito">Conflito</a>
    - <a href="#submodulo">Submodulo</a>
    - <a href="#ignore">Git ignore</a>
    - <a href="#comandos">Principais comandos</a>
1. <a href="#swift"> Swift</a>
    - <a href="#tipos"> Principais tipos primitivos</a>
    - <a href="#class"> Class e Struct</a>
    - <a href="#loop"> Loop</a>
    - <a href="#validacao"> Validações</a>
    - <a href="#var"> var e let</a> 
    - <a href="#protocol"> Protocol (inteface e delegate)</a>
    - <a href="#visibilidade"> Visibilidade</a>
    - <a href="#array"> Array e Dictionary (criação e manipulação)</a>
    - <a href="#extension"> Extension</a>
    - <a href="#enum"> Enum</a>
    - <a href="#closure"> Closure</a>
    - <a href="#uikit"> Componentes de UIKit</a>
    - <a href="#mvvm"> MVVM</a>
    - <a href="#clean">Clean Code</a>
    - <a href="#lint"> Lint</a>
1. <a href="#swiftUI">SwiftUI</a>
    - <a href="#propertyWrappers">Property Wrappers</a>
    - <a href="#combine">Combine</a>
    - <a href="#componentesSwiftUI">Componentes de SwiftUI</a>
1. <a href="#referencia">Sites de referência</a>

## <p id="git">GIT</p>
O git é o sistema de controle de versão gratuita mais utilizado atualmente. É utilizado para salvar, restaura e compartilhar entre os desenvolvedores, todas as alterações de código do projeto que estão trabalhando junto.

### <p id="branch">Branch</p>

Todo repositório de git inicia com uma branch principal chamada __MASTER__. As branches são criadas para criar uma cópia do código em um determinado ponto do tempo. Desta forma é possível desenvolver a funcionalidade e ir fazendo os commits (<a href="#commit">commit</a>) sem alterar o estado estável da __MASTER__, desta forma outros desenvolvedores consegue criar branchs para trabalhar em paralelo em outras funcionalidades sem se deparar com códigos inacabados, com bugs de desenvolvimento ou qualquer outra surpresa.

Branches podem ser criadas a partir de outras branches e podem ser atualizadas e juntadas (<a href="#mr">Merge request e merge back</a>) a fim de manter o código que esta trabalhando atualizado e reduzir a quantidade de conflitos (<a href="#conflito">conflito</a>) no merge request final.

### Comandos
O git pode ser utilizado no terminal ou em softwares gratuitos e pagos que criam uma interface.

No terminal é necessário executar comandos para que o git crie uma branch ou mude.

> git branch <new_feature>

Serve para criar uma nova branch local.

> git checkout <new_feature>

É utilizado para mudar de branch.

> git branch -d <new_feature>

É utilizado para deletar uma branch local.

> git pull

É utilizado para baixar os novos commits da branch atual.

### Exemplo
Ao criar o repositório para um aplicativo de receitas. A tarefa de criar a tela inicial poderia ser desenvolvida em uma branch chamada `introduction`, enquanto a tarefa de desenvolver a tela de adicionar receita poderia ser feita na branch de `new_recipe`.

<a href="#indice">↑ indices</a>

---
### <p id="remote">Local e remoto</p>

> não documentado

<a href="#indice">↑ índice</a>

---
### <p id="gitFlow">Git Flows</p>

> não documentado

<a href="#indice">↑ índice</a>

---
### <p id="commit">Commit</p>

> não documentado

<a href="#indice"> índice</a>

---
### <p id="mr"> Merge request e merge back</p>

> não documentado

<a href="#indice"> Índice</a>

---
### <p id="conflito">Conflito</p>

> não documentado

<a href="#indice"> índices </a>

---
### <p id="submodulo">Submodulo</p>

> não documentado

<a href="#indice">↑ indices </a>

---
### <p id="ignore">Git ignore</p>

> não documentado

<a href="#indice">↑ indices </a>

---
### <p id="comandos">Principais comandos</p>

> não documentado

<a href="#indice">↑ indices </a>

## <p id="swift">Swift</p>

### <p id="tipos">Principais tipos primitivos</p>

> não documentado

<a href="#indice">↑ indices </a>

---
### <p id="class"> Class e Struct</p>

> não documentado

<a href="#indice">↑ indices </a>

---
### <p id="loop"> Loop</p>

> não documentado

<a href="indice">↑ indices </a>

---
### <p id="#validacao"> Validações</p>

> não documentado

<a href="#indice">↑ indices </a>

---
### <p id="var"> var e let</p> 

> não documentado

<a href="#indice">↑ indices </a>

---
### <p id="protocol"> Protocol (inteface e delegate)</p>

> não documentado

<a href="#indice">↑ indices </a>

---
### <p id="visibilidade"> Visibilidade</p>

> não documentado

<a href="#indice">↑ indices </a>

---
### <p id="array"> Array e Dictionary (criação e manipulação)</p>

> não documentado

<a href="#indice">↑ indices </a>

---
### <p id="extension"> Extension</p>

> não documentado

<a href="#indice">↑ indices </a>

---
### <p id="enum"> Enum</p>

> não documentado

<a href="#indice">↑ indices </a>

---
### <p id="closure"> Closure</p>

> não documentado

<a href="#indice">↑ indices </a>

---
### <p id="uikit"> Componentes de UIKit</p>

> não documentado

<a href="#indice">↑ indices </a>

---
### <p id="mvvm"> MVVM</p>

> não documentado

<a href="#indice">↑ indices </a>

---
### <p id="clean">Clean Code</p>

> não documentado

<a href="#indice">↑ indices </a>

---
### <p id="lint"> Lint</p>

> não documentado

<a href="#indice">↑ indices </a>

## <p id="swiftUI">SwiftUI</p>

> não documentado

<a href="#indice">↑ indices </a>

---
### <p id="propertyWrappers">Property Wrappers</p>

> não documentado

<a href="#indice">↑ indices </a>

---
### <p id="combine">Combine</p>

> não documentado

<a href="#indice">↑ indices </a>

---
### <p id="componentesSwiftUI">Componentes de SwiftUI</p>

> não documentado

<a href="#indice">↑ indices </a>

## <p id="referencia">Sites de referência</p>

Introdução a GIT (https://phoenixnap.com/kb/how-to-use-git)

<a href="#indice">↑ indices </a>