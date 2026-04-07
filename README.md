# 🎓 Projeto API Aluno Online - UNIESP (Back-end I)

## 📝 Explicação do Projeto
Este projeto consiste em uma **API REST** para o gerenciamento de uma instituição de ensino. O sistema permite realizar o cadastro, consulta, atualização e exclusão (CRUD) de **Alunos** e **Professores**, integrando o backend em Java com um banco de dados relacional PostgreSQL.

O objetivo principal é oferecer uma base sólida e escalável para o controle acadêmico, garantindo que as informações sejam persistidas de forma segura e organizada.

---

## 💻 Detalhamento do Código e Tecnologias
O código foi desenvolvido utilizando as melhores práticas do ecossistema Java:

* **Java 17 (LTS):** Linguagem base pela sua robustez e estabilidade.
* **Spring Boot 3:** Framework que agiliza o desenvolvimento através da configuração automática.
* **Spring Data JPA / Hibernate:** Tecnologia que mapeia as classes Java para tabelas do banco de dados (ORM), facilitando a persistência sem SQL manual.
* **PostgreSQL:** Banco de dados relacional utilizado para armazenar os dados de forma definitiva.
* **Maven:** Gerenciador de dependências que organiza todas as bibliotecas do projeto (pom.xml).
* **Insomnia:** Ferramenta utilizada para validar e testar todos os endpoints da API.
* **DBeaver:** Interface gráfica para monitoramento e gestão do banco de dados.

---

## 🏗️ Descrição da Arquitetura Utilizada
O sistema utiliza o padrão **MVC (Model-View-Controller)**, dividindo as responsabilidades em camadas:

1.  **Model:** Define as entidades `Aluno` e `Professor` com suas anotações JPA.
2.  **Repository:** Interfaces que estendem `JpaRepository`, fornecendo métodos prontos para o banco.
3.  **Service:** Camada de lógica de negócio, onde tratamos as regras de atualização e exclusão.
4.  **Controller:** Camada que expõe os endpoints e recebe as requisições HTTP (`@RequestBody`, `@PathVariable`).

---

## 🚀 Prints das Requisições (Insomnia)

### 🟢 Cadastro (POST)
> Realizando o cadastro de novos registros no sistema.
>  <img width="1918" height="995" alt="POST_Professor" src="https://github.com/user-attachments/assets/c186fd5c-3f1d-41a1-86d6-9ad38534beec" /> <img width="1916" height="990" alt="POST_Aluno" src="https://github.com/user-attachments/assets/c8320270-8a7f-4643-b611-5d0c2d6ffb24" />
  

### 🔵 Listagem (GET)
> Consultando todos os dados cadastrados na base de dados.
>   <img width="1919" height="992" alt="GET_Aluno" src="https://github.com/user-attachments/assets/3fe25075-1cda-4a9d-a8a8-abc3d99fe117" />
  <img width="1919" height="997" alt="GET_Professor" src="https://github.com/user-attachments/assets/eee56e2c-a625-403f-bb15-5ed71c952acf" />    

### 🟠 Atualização (PUT)
> Alterando informações de registros existentes através do ID.
 <img width="1919" height="992" alt="PUT_Professor " src="https://github.com/user-attachments/assets/6a549bda-4dae-43c2-a0e3-e7294735f084" />   <img width="1919" height="988" alt="PUT_Aluno" src="https://github.com/user-attachments/assets/caecb9e9-2ce8-4a92-b861-ec0cb505934d" />


### 🔴 Exclusão (DELETE)
> Removendo registros do sistema com sucesso.
   <img width="1919" height="995" alt="DELETE_Aluno" src="https://github.com/user-attachments/assets/4f3b467b-f560-4f52-a35a-ee4bbd53d338" />
  <img width="1919" height="997" alt="DEL_Professor" src="https://github.com/user-attachments/assets/4bf45d12-19c1-4faa-8aba-6f602205597e" /> 

---

## 🗄️ Prints do DBeaver (Tabelas do Banco de Dados)
> Evidência das tabelas criadas e populadas no PostgreSQL, confirmando a persistência dos dados testados.

### Tabela de Alunos
   <img width="1919" height="994" alt="DB_Aluno" src="https://github.com/user-attachments/assets/6ad334f5-4483-49c8-b9a8-2e5c2d1f4835" /> 

### Tabela de Professores
 <img width="1919" height="999" alt="DB_Professor" src="https://github.com/user-attachments/assets/2efd9d3e-1ea4-4435-acde-ec0692d8dd84" /> 


---

## 🏁 Conclusão
Este projeto foi desenvolvido como **1ª Avaliação** da disciplina de **Back-end I**, consolidando os conceitos de arquitetura REST, persistência em PostgreSQL e o fluxo de um CRUD completo em Java.

Agradeço ao **Professor Kelson** pelas orientações e pelo excelente material de apoio disponibilizado.

---
### 👤 Desenvolvido por:
**Alyere Targino** | Ciência da Computação (P3)
📍 Centro Universitário UNIESP

