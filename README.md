# projeto-integrador

Classe Pessoa
------------------
- nome: String
- em_direito: String
- telefone: String
- e-mail: String
- dataCadastro: Date
- id: Sequência de caracteres


classDiagram
    class Pessoa {
        +String nome
        +String em_direito
        +String telefone
        +String e_mail
        +Date dataCadastro
        +String id
    }


```mermaid
classDiagram
    class Pessoa {
        +String nome
        +int idade
        +falar()
    }
    class Aluno {
        +String matricula
        +estudar()
    }
    Pessoa <|-- Aluno
