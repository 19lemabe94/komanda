Sistema de Registro de Vendas
Descrição
O Sistema de Registro de Vendas é uma aplicação desktop que permite a um usuário registrar vendas de produtos, associar vendas a clientes e gerar relatórios de vendas. O sistema foi desenvolvido com o objetivo de automatizar o processo de vendas, facilitando o registro e a gestão de transações de forma eficiente e prática.

A interface gráfica é construída com custom TKINTER, oferecendo uma experiência de usuário simples e intuitiva.

Funcionalidades
Login de Usuário: O sistema exige que o usuário faça login para acessar as funcionalidades do sistema.
Registro de Vendas: Permite que o usuário registre vendas, incluindo informações sobre os produtos vendidos e o cliente associado à venda.
Cálculo Automático: O sistema calcula automaticamente o valor total da venda, incluindo os subtotais dos produtos vendidos.
Geração de Relatórios: O usuário pode gerar relatórios de vendas para visualizar o total de vendas realizadas em um período específico.

Interface Gráfica: Interface intuitiva construída com custom TKINTER para facilitar a interação do usuário com o sistema.

Tecnologias Utilizadas

Python: Linguagem de programação utilizada para o desenvolvimento do sistema.

custom TKINTER: Biblioteca para criar a interface gráfica do sistema, com componentes personalizados.

MySQL: Banco de dados relacional utilizado para armazenar informações sobre clientes, produtos e vendas.

HTML/CSS/JavaScript (caso seja necessário para alguma funcionalidade adicional).

Instalação
1. Clone o Repositório

git clone https://github.com/seu-usuario/sistema-registro-vendas.git
cd sistema-registro-vendas

2. Instale as Dependências
Certifique-se de que o Python esteja instalado. Em seguida, instale as dependências necessárias:
pip install -r requirements.txt

3. Configuração do Banco de Dados
Crie um banco de dados no MySQL para armazenar as informações do sistema (clientes, produtos, vendas).

Atualize as configurações de banco de dados no arquivo de configuração do sistema (config.py ou similar).

4. Executando o Sistema
Para rodar a aplicação:
python app.py
A interface gráfica será aberta automaticamente, permitindo que o usuário interaja com o sistema.

Estrutura do Projeto
/sistema-registro-vendas
│
├── /app.py            # Arquivo principal da aplicação
├── /models.py         # Definições das classes (Produto, Cliente, Venda, etc.)
├── /config.py         # Configurações do banco de dados e do sistema
├── /interface.py      # Código relacionado à interface gráfica customizada com TKINTER
├── /requirements.txt  # Dependências do projeto
└── /README.md         # Este arquivo


Como Contribuir:
- Faça um fork do projeto.

- Crie uma branch para suas modificações (git checkout -b feature/novas-funcionalidades).

- Realize suas alterações e commit (git commit -am 'Adiciona nova funcionalidade').

- Envie para o repositório remoto (git push origin feature/novas-funcionalidades).

- Abra um Pull Request.

Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes.