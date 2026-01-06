# StaffCore — Sistema de Gestão de Pessoas e Empregados

## 📌 Visão Geral

O **StaffCore** é um sistema de gestão de pessoas e empregados desenvolvido em **Python**, com foco em **Programação Orientada a Objetos (POO)**. O projeto modela diferentes tipos de pessoas, empregados e profissionais específicos, utilizando conceitos como **herança**, **composição** e **enumerações (Enums)** para garantir organização, clareza e reutilização de código.

Este sistema é indicado para fins **acadêmicos**, **educacionais** e como base para futuras expansões em sistemas de gestão empresarial.

---

## 🗂️ Estrutura do Projeto

```text
├── README.md
└── project
    ├── main.py
    └── models
        ├── Pessoa.py
        ├── Fisica.py
        ├── Juridica.py
        ├── Cliente.py
        ├── Funcionario.py
        ├── Advogado.py
        ├── Medico.py
        ├── Motoboy.py
        ├── Endereco.py
        └── enums
            ├── Sexo.py
            ├── Setor.py
            └── UnidadeFederativa.py
```

---

## 🧱 Modelagem do Sistema

### 🔹 Pessoa

Classe base do sistema, responsável por atributos comuns a qualquer tipo de pessoa.

**Principais atributos:**

* Nome
* Documento (CPF ou CNPJ)
* Endereço
* Sexo

---

### 🔹 Pessoa Física (`Fisica`)

Herda de `Pessoa` e representa indivíduos.

**Exemplos de uso:**

* Cliente
* Funcionário

---

### 🔹 Pessoa Jurídica (`Juridica`)

Representa empresas ou organizações, também herdando de `Pessoa`.

---

### 🔹 Cliente

Especialização de `Fisica`, utilizada para representar clientes do sistema.

---

### 🔹 Funcionário

Especialização de `Fisica`, representando empregados da organização.

**Tipos de funcionários implementados:**

* Advogado
* Médico
* Motoboy

Cada tipo pode conter regras, atributos e comportamentos específicos de acordo com sua função.

---

## 🏷️ Enums

Os Enums são utilizados para padronizar valores e evitar inconsistências no sistema.

### 🔸 Sexo

Define o sexo da pessoa.

### 🔸 Setor

Define o setor de atuação do funcionário.

### 🔸 UnidadeFederativa

Define o estado (UF) do endereço.

---

## ▶️ Execução do Projeto

Para executar o sistema, utilize o comando:

```bash
python project/main.py
```

O arquivo `main.py` funciona como ponto de entrada para testes e simulações do sistema.

---

## 🎯 Objetivos do Projeto

* Aplicar conceitos de **Programação Orientada a Objetos em Python**
* Praticar **herança, composição e enums**
* Desenvolver um sistema organizado e escalável

---

## 🚀 Possíveis Evoluções

* Persistência de dados em arquivos ou banco de dados
* Interface gráfica ou aplicação web
* Cadastro e gerenciamento completo de pessoas e empregados

---

## 🧑‍💻 Autor

Projeto desenvolvido para fins acadêmicos e educacionais.
