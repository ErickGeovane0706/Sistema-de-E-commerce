# 🌟 Spring Boot E-commerce

## Sobre o Projeto
Este projeto é um **sistema de e-commerce**, desenvolvido como demonstração de habilidades em **desenvolvimento backend com Java e Spring Boot**.  

Ele foi construído para mostrar **organização, boas práticas e domínio de tecnologias essenciais** para o mercado de tecnologia, incluindo:

- Modelagem de entidades complexas (Usuários, Produtos, Categorias, Pedidos, Pagamentos)  
- Relacionamentos avançados (1:N, N:N, 1:1)  
- Persistência de dados com **JPA/Hibernate**  
- Criação de **APIs REST** com endpoints claros e seguros  
- Tratamento de exceções estruturado e confiável  
- Configuração para múltiplos bancos de dados (PostgreSQL e H2)  


> Este projeto demonstra meu comprometimento em escrever código limpo, organizado e funcional – habilidades essenciais para qualquer estágio em desenvolvimento de sistemas.

---

## Funcionalidades Principais

- **Gestão de Usuários** – CRUD completo de clientes, com validações e tratamento de exceções  
- **Produtos e Categorias** – Listagem, associação e busca por ID  
- **Pedidos** – Criação de pedidos com múltiplos itens, cálculo automático do total  
- **Pagamentos** – Registro e associação de pagamentos aos pedidos  
- **Tratamento de Erros** – Respostas estruturadas em JSON para erros de banco ou recursos não encontrados  

---

## Tecnologias e Ferramentas

- **Java 17** – Base do desenvolvimento  
- **Spring Boot** – Framework principal  
- **Spring Data JPA** – Persistência de dados  
- **PostgreSQL e H2** – Bancos de dados para produção e testes  
- **Maven** – Gerenciamento de dependências  
- **Jackson** – Manipulação de JSON    

---

## Demonstração de Endpoints

| Recurso | Método | Descrição |
|---------|--------|-----------|
| `/users` | GET | Lista todos os usuários |
| `/users/{id}` | GET | Consulta usuário por ID |
| `/users` | POST | Cria novo usuário |
| `/users/{id}` | PUT | Atualiza usuário |
| `/users/{id}` | DELETE | Deleta usuário |
| `/products` | GET | Lista produtos |
| `/products/{id}` | GET | Consulta produto por ID |
| `/categories` | GET | Lista categorias |
| `/categories/{id}` | GET | Consulta categoria por ID |
| `/orders` | GET | Lista pedidos |
| `/orders/{id}` | GET | Consulta pedido por ID |

> Todos os endpoints seguem boas práticas REST e retornam mensagens claras em caso de erros, facilitando integração com front-end ou apps móveis.

---

## Por que este projeto destaca minhas habilidades

1. **Organização e boas práticas de código** – Estrutura clara entre entidades, repositórios, serviços e controllers  
2. **Capacidade de modelagem de dados complexos** – Uso de chaves compostas, relacionamentos N:N e 1:1  
3. **Resiliência e tratamento de erros** – Exceções personalizadas (`ResourceNotFoundException`, `DataBaseException`) e respostas consistentes (`StandardError`)  
4. **Foco em resultado** – APIs prontas para integração real, com endpoints funcionais e dados de teste  

> Esse projeto mostra que sou capaz de **aplicar conceitos de Engenharia de Software em sistemas reais**, garantindo confiabilidade, manutenção e escalabilidade.

---

## Como Executar

1. Clone o projeto:
```bash
git clone <URL_DO_REPOSITORIO>
cd <NOME_DO_PROJETO>
