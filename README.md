# trab-perso1-2022b-giovannircl
trab-perso1-2022b-giovannircl created by GitHub Classroom

**Motivações:**

  - Por trabalhar com Delphi, me senti preparado para me desafiar neste trabalho, utilizando muito do que conheci sobre POO e banco de dados tanto nas aulas com as       práticas quanto no dia a dia.

**Funções do sistema:**

- **Produto:**

  - Cadastrar (Fornecedor deve existir previamente).

    - Nome, preço de custo e venda, quantidade, categoria, peso ou unidade.

  - Localizar.

    - Habilita as funcionalidades: Alterar e Excluir.

- **Fornecedor:**

  - Cadastrar

    - Nome, cidade, CNPJ, endereço, CEP, telefone, email.

  - Localizar.

    - Habilita as funcionalidades: Alterar e Excluir.

**Tabelas do sistema:**

Nome do schema: projetoparadigmas.

- PRODUTOS
- FORNECEDORES

**Estrutura do sistema em código:**

O sistema é estruturado com 6 Forms e 1 Data module:

- **udmPrincipal**.

  - A partir deste módulo de dados, é possível fazer a conexão com o banco de dados, bem como preencher 'DataSets' com todos os dados das tabelas criadas, por meio das   querys.
  - Todos os formulários utilizam este Data Module.

- **uPrincipal**.

  - Formulário principal que contém o padrão da tela do sistema, para que assim todos os outros formulários herdem dele e estejam nesse padrão, com os mesmos             componentes e podendo utilizar as funções declaradas nele também.

- **uHome**.

  - Formulário com dois botões que levam ao uFornecedores e uProdutos, apenas como uma página inicial.

- **uFornecedores e uProdutos.**

  - Formulários para cadastrar e consultar fornecedores e produtos respectivamente.

- **uLocalizarFornecedores e uLocalizarProdutos**.

  - Formulários para localizar e selecionar fornecedores e produtos respectivamente

**Como utilizar o sistema:**

- **Home:**

  - Fornecedores:Ambiente de cadastro/consulta dos fornecedores.

  - Produtos:Ambiente de cadastro/consulta dos produtos.

- **Botões:**

  - **Novo:** Ao clicar neste botão, os campos são habilitados para serem populados e posteriormente o seu registro salvo em banco.
  - **Cancelar** : Caso não deseje alterar ou incluir novos registros, clique neste botão, assim os campos são desabilitados e você pode selecionar a aba consulta para   localizar os registros desejados.
  - **Localizar** : Ao clicar neste botão, é exibido um grid com todos os registros e você pode selecionar um deles para conferir, alterar ou excluir.
  - **Alterar** : Ao clicar neste botão, você é redirecionado para a aba de cadastro podendo alterar os dados do registro selecionado anteriormente no localizar.
  - **Excluir:** Ao clicar neste botão, o registro selecionado anteriormente no localizar é excluído do banco de dados.
