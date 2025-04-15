# Projeto A1 - Sistema de Cadastro de Usuários (PHP)

**Autor:** _Kauan Amélio Cipriani_

**Contexto Acadêmico:**
* **Instituição:** Universidade do Oeste de Santa Catarina (UNOESC) - Campus São Miguel do Oeste
* **Curso:** Bacharelado em Ciências da Computação
* **Disciplina:** Programação III
* Objetivo da Disciplina: Aprofundar o conhecimento em programação para web, com foco em PHP, abordando conceitos de segurança, gerenciamento de sessões e interação com bancos de dados.
* Objetivo do Projeto: Demonstrar a capacidade de aplicar os conceitos aprendidos na disciplina para desenvolver uma aplicação web funcional e segura, que inclua cadastro e autenticação de usuários.

## 🚀 Introdução

Esta é uma aplicação web para cadastro e autenticação de usuários, desenvolvida no contexto da atividade acadêmica A1. O projeto foca na implementação prática de conceitos PHP para web, como:

* **Autenticação Segura:** Registro e login com validação de dados e hashing de senha.
* **Controle de Acesso:** Gerenciamento de sessões de usuário com PHP.
* **Apresentação Visual:** Interface simples estilizada com CSS.

---

## 🛠️ Tecnologias Utilizadas

* PHP 8.0+
* HTML5
* CSS3

---

## ⚙️ Configuração e Execução

1.  **Servidor Local:** Instale e inicie um ambiente de servidor web (ex: XAMPP, WAMP, Laragon).
2.  **Código-Fonte:** Coloque os arquivos do projeto na pasta raiz do servidor (geralmente `htdocs` ou `www`).
3.  **Navegação:** Acesse a aplicação pelo navegador em: `http://localhost/nome-do-arquivo/index.php` *(substitua `nome-do-arquivo` pelo nome real da pasta do projeto)*.

    * *A partir daí, é possível registrar-se, autenticar-se, visualizar o painel principal e desconectar-se.*

---

## ✨ Recursos Principais

* **Registro de Usuário:** Permite a criação de novas contas (nome, email, senha) com validação de entrada.
* **Autenticação de Usuário:** Login via email e senha, gerenciado por sessões PHP (com suporte opcional a cookies para persistência).
* **Painel do Usuário:** Exibe uma área restrita e personalizada após o login bem-sucedido.
* **Encerramento de Sessão:** Funcionalidade para desconectar o usuário de forma segura, invalidando a sessão.

---

## 📚 Referências

* [PHP Documentation](https://www.php.net/manual/pt_BR/) - Consulta essencial para funções PHP (sessões, `password_hash`, etc.).
* [MDN Web Docs](https://developer.mozilla.org/pt-BR/docs/Web) - Ótimo recurso para padrões web e boas práticas (HTML, CSS).
