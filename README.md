#

# Sistema de Gerenciamento de Biblioteca

### Objetivo

Implementar um Sistema de Gerenciamento de Biblioteca para gerenciar diferentes tipos de materiais de biblioteca (como livros, revistas e mídias digitais) e seus comportamentos unicos. Este exercício deve utilizar princípios de programaça"o orientada a objetos, como herança, interfaces e polimorfismo.

##

### Requisitos
1. Classe Consumidora: `LibraryManagementSystem`

- Esta e a classe principal onde a aplicaça" será executada. Deve demonstrar a criação de varias instancias de materiais da biblioteca, a invocaçao de seus metodos e a demonstraçao de polimorfismo.

2. Interface: `Borrowable`

- Definir metodos que todos os materiais da biblioteca devem implementar, como
`borrow()` e `returnItem()`.

3. Superclasse: `LibraryItem`

- Contém propriedades e meétodos comuns para todos os materiais da biblioteca, como `title` (título), `author` (autor) e `publicationYear` (ano de publicaça"o).

- Implementa a interface `Borrowable`.

4. Classes Especializadas: `Book`, `Magazine`, `DigitalMedia`

- Cada classe herda da superclasse `LibraryItem` e implementa comportamentos específicos para diferentes tipos de materiais.

- Cada classe especializada deve ter propriedades e métodos adicionais exclusivos. Por exemplo:

- `Book` pode ter uma propriedade `genre` (ge/nero) e um método `readSample()` (ler
amostra).

- `Magazine` pode ter uma propriedade `issueNumber` (número da ediça"o) e um método
`flipPages()` (folhear páginas).

- `DigitalMedia` pode ter uma propriedade `fileFormat` (formato de arquivo) e um método `play()` (reproduzir).

##

### Detalhes da Tarefa

Passo 1: 

Definir a Interface `Borrowable`
Defina os métodos obrigatérios que todos os materiais da biblioteca devem implementar, como `borrow()` e `returnItem()`.

##

Passo 2: 

Definir a Superclasse `LibraryItem`
Crie a classe abstrata `LibraryItem` que contém as propriedades comuns (`title`, `author`,`publicationYear`) e um método para exibir essas informaço"es. A classe também deve implementar a interface `Borrowable`.

##

Passo 3: 
Implementar as Classes Especializadas


Implemente as classes especializadas `Book`, `Magazine` e `DigitalMedia`, herdando de
`LibraryItem` e sobrescrevendo os métodos da interface `Borrowable`. Adicione
propriedades e métodos exclusivos para cada classe.

##

Passo 4: 
Implementar a Classe Consumidora `LibraryManagementSystem` Na classe `LibraryManagementSystem`, crie insta/ncias de cada tipo de material da
biblioteca, demonstre o uso de polimorfismo, chame os métodos comuns e específicos de
cada classe.

##

Instruções
1. Implemente as classes e a interface conforme descrito.
2. Teste o programa na classe `LibraryManagementSystem`.
3. O resultado deve demonstrar o uso de polimorfismo, herança e interfaces.
Resultado Esperado
Quando os alunos executarem a classe `LibraryManagementSystem`, eles devera"o ver:
- Informaço"es sobre cada item da biblioteca.
- Aço"es de empréstimo e devoluça"o para cada item.
- Comportamentos únicos de cada classe especializada.
Este novo tema mantém a complexidade e os objetivos de aprendizado, aplicando-os a um
contexto de biblioteca.

##