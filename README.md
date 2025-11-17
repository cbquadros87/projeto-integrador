# Sistema de Cadastro Universitário

Este README descreve o projeto desenvolvido para a disciplina da
faculdade, no qual criamos um **sistema de cadastros** para uma
universidade. O objetivo foi modelar entidades, suas relações e
prototipar as telas no Figma, bem como estruturar a lógica de cadastro
para diferentes tipos de usuários.

---

## 📘 Objetivo do Sistema

O sistema visa permitir o cadastro e gerenciamento de:

- Pessoas físicas (como professores e alunos)
- Pessoas jurídicas (como fornecedores)
- Professores e suas disciplinas
- Alunos e suas informações acadêmicas
- Fornecedores e subordinados autorizados

A modelagem inclui heranças, associações, atributos e métodos
necessários para garantir um fluxo completo de cadastro.

---

## 🧱 Estrutura e Relações

### 🔹 **Pessoa**

Classe-base que contém informações comuns a qualquer indivíduo ou
organização cadastrada.

### 🔹 **PessoaFisica**

Especialização de Pessoa, referenciada pelos cadastros de **Aluno** e
**Professor**.

### 🔹 **PessoaJuridica**

Especialização de Pessoa, utilizada no cadastro de **Fornecedor**.

### 🔹 **Professor**

Contém dados profissionais e lista de disciplinas ministradas. Cada
professor está associado a uma Pessoa Física.

### 🔹 **Aluno**

Contém informações acadêmicas como curso, turno, período e matrícula.
Também vinculado a uma Pessoa Física.

### 🔹 **Fornecedor**

Representa empresas cadastradas pela universidade. Está associado a uma
Pessoa Jurídica e possui uma lista de subordinados autorizados.

### 🔹 **Disciplina**

Unidade curricular relacionada a Professores.

---

## 🖥️ Telas no Figma

Também desenvolvemos protótipos no Figma representando as telas de:

- Cadastro de Pessoas Físicas
- Cadastro de Professores
- Cadastro de Alunos
- Cadastro de Fornecedores
- Gerenciamento de Disciplinas

Esses protótipos ajudaram a validar a experiência do usuário e os fluxos
principais do sistema.

---

## ✔️ Conclusão

Este projeto integrou conceitos de **orientação a objetos**, **modelagem
UML** e **prototipação de interface**. O diagrama e as classes definidas
fornecem uma base sólida para a implementação futura do sistema.
