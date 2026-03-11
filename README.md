# 🔐 Password Security Utilities (.NET)

Conjunto de **classes utilitárias em C# (.NET)** para segurança de senhas.  
Inclui geração de **senhas aleatórias**, criação de **salt criptográfico**, geração de **hash de senha** e **validação de credenciais** comparando senha + salt com o hash armazenado.

As classes foram projetadas para serem **simples de integrar e reutilizar em diferentes projetos .NET**, como APIs, aplicações web, desktop ou mobile.

---

# 🚀 Funcionalidades

## 🔑 Geração de Senhas Aleatórias
Classe responsável por gerar **senhas fortes automaticamente**, podendo incluir:

- Números de 6 digitos gerados de forma aleatória  

Útil para criação automática de credenciais para usuários.

---

## 🧂 Geração de Salt
Cada senha deve possuir um **salt único** para aumentar a segurança.

O salt é um valor aleatório que é combinado com a senha antes da geração do hash, ajudando a prevenir:

- Ataques de dicionário
- Rainbow tables

---

## 🔒 Geração de Hash de Senha

O processo de armazenamento de senha segue o fluxo:

