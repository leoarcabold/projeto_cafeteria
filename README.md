# ☕ Café Aroma — Sistema de Gestão de Pedidos e Estoque

Bem-vindo ao repositório do **Café Aroma**, um sistema completo de gestão para cafeterias, englobando vendas, cadastro de produtos, promoções, controle de estoque e relacionamento com clientes. Este projeto demonstra habilidades de modelagem relacional, SQL avançado e boas práticas de desenvolvimento de sistemas integrados.

## 📚 Descrição do Projeto

O **Café Aroma** foi projetado para facilitar o controle operacional de uma cafeteria, incluindo:

- Cadastro e gestão de filiais, funcionários e clientes
- Criação dinâmica de produtos e suas composições
- Controle de estoque de ingredientes
- Aplicação automatizada de promoções e descontos
- Registro de pedidos, itens e ingredientes adicionais

O modelo foi inteiramente desenhado a partir de um **diagrama entidade-relacionamento**:

![Diagrama ER Café Aroma](./der_cafe_aroma.png)

## 🏗️ Modelagem do Banco de Dados

O sistema contempla as seguintes entidades principais:

- Filial
- Funcionário
- Cliente
- Endereço
- Produto, Categoria e Composição
- Ingrediente
- Promoção
- Pedido, Item de Pedido e Adicionais

Toda estrutura foi construída em SQL, 100% normalizada, cobrindo chaves primárias, estrangeiras e tabelas associativas.

## 🚀 Funcionalidades-Chave

- **Controle de estoque automatizado** para ingredientes marcados como controlados
- **Cadastro flexível** de produtos e suas composições
- **Promoções inteligentes** aplicadas diretamente aos pedidos
- **Gestão completa de pedidos**, incluindo históricos, avaliações e adicionais

## 🗂️ Estrutura do Repositório

| Pasta/Arquivo            | Descrição                                                |
|--------------------------|---------------------------------------------------------|
| `der_cafe_aroma.png`     | Diagrama E-R do projeto                                 |
| `ddl/`                   | Scripts SQL de criação das tabelas                      |
| `dml/`                   | Scripts de inserção e exemplos de uso                   |
| `README.md`              | Guia e apresentação geral do projeto                    |

## 💡 Como utilizar

1. Clone este repositório.
2. Importe os scripts SQL em seu SGBD de escolha.
3. Popule o banco com os exemplos disponíveis.
4. Realize consultas e operações conforme suas necessidades.

## 📝 Exemplos de Consultas

- Buscar todos os pedidos de um cliente
- Listar produtos de um pedido e seus ingredientes adicionais
- Verificar estoque de ingredientes controlados

## 👨‍💻 Tecnologias Utilizadas

- SQL ANSI
- Ferramentas de modelagem visual (como dbdiagram.io)
- SGBDs compatíveis: MySQL, PostgreSQL, SQL Server

## 📈 Diferenciais

- Modelagem flexível e expansível, pronta para integrações futuras (ex: aplicativos mobile, delivery)
- Scripts documentados e otimizados para performance
- Código pronto para uso didático e profissional

## 📬 Contato

Dúvidas ou sugestões? Fique à vontade para abrir uma *issue* ou entrar em contato por [seu e-mail ou LinkedIn].

---

Personalize conforme sua identidade visual e área de atuação!




![](https://github.com/leoarcabold/projeto_cafeteria/blob/main/img/der_cafe_aroma.png)

![](https://github.com/leoarcabold/projeto_cafeteria/blob/main/img/modelo%20relacional.png)
