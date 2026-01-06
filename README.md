# Sistema de Gestão de Pessoas e Empregados

## 📌 Visão Geral

Este projeto é um **sistema de gestão de pessoas e empregados**, desenvolvido em **Python**, com foco em modelagem orientada a objetos. Ele organiza diferentes tipos de pessoas (físicas e jurídicas), profissionais e funcionários, utilizando **herança, composição e enums** para manter o código estruturado, reutilizável e fácil de manter.

O sistema é ideal para fins **educacionais**, aprendizado de **POO em Python**, ou como base para sistemas maiores de gestão empresarial, jurídica ou de serviços.

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

Classe base do sistema, representando uma pessoa genérica.

**Atributos comuns:**

* Nome
* Documento (CPF ou CNPJ)
* Sexo
* Endereço

---

### 🔹 Pessoa Física (`Fisica`)

Herda de `Pessoa` e representa indivíduos.

**Exemplos:**

* Cliente
* Funcionário

---

### 🔹 Pessoa Jurídica (`Juridica`)

Representa empresas ou organizações.

---

### 🔹 Cliente

Herda de `Fisica` e representa clientes do sistema.

---

### 🔹 Funcionário

Herda de `Fisica` e representa empregados da organização.

**Especializações:**

* Advogado
* Médico
* Motoboy

Cada especialização pode conter regras e atributos próprios conforme a função exercida.

---

## 🏷️ Enums

O projeto utiliza enums para padronizar valores e evitar inconsistências.

### 🔸 Sexo

Define o sexo da pessoa.

### 🔸 Setor

Define o setor de atuação do funcionário.

### 🔸 UnidadeFederativa

Define o estado (UF) do endereço.

---

## ▶️ Execução do Projeto

Para executar o sistema:

```bash
python project/main.py
```

O arquivo `main.py` é o ponto de entrada e pode ser usado para testes, simulações e instanciamento das classes.

---

## 🎯 Objetivo do Projeto

* Praticar **Programação Orientada a Objetos em Python**
* Trabalhar com **herança, enums e organização em camadas**
* Criar uma base sólida para sistemas de gestão

---

## 🚀 Possíveis Evoluções

* Persistência de dados (arquivos ou banco de dados)
* Interface gráfica ou web
* Sistema de autenticação
* CRUD completo de pessoas e empregados

---

## 🧑‍💻 Autor

Projeto desenvolvido para fins educacionais e de aprendizado em Python.
