# Microsoft_Azure-instancia_BD

# 1- Acesso à Página Inicial
- Navegue para **[Página Inicial](https://portal.azure.com) > Banco de Dados**.

# 2- Seleção de Nome para o Banco de Dados
- Escolha o tipo de banco de dados que deseja usar. O Azure oferece opções como SQL Database, Cosmos DB e mais. Aqui, vamos criar um **SQL Database**. 

- **Plano de Tarifação** (Importante): Selecione o plano que se adapta às suas necessidades. Se você está apenas testando, o plano gratuito pode ser suficiente. 
- **Backup e Recuperação** (Importante): Configure as opções de backup conforme necessário para garantir que seus dados estejam seguros. 


# 3- Criação de um Servidor
- Como não havia nenhum servidor existente, foi criado um novo servidor.
  - **Importante:** O servidor precisa ser configurado corretamente para garantir segurança e performance.

# 4- Autenticação do Banco de Dados
- Configurou-se a **autenticação** necessária para acesso ao banco de dados:
  - **Autenticação SQL** (nome de usuário e senha).
  - **Autenticação baseada em Active Directory** (opcional, mas recomendada para ambientes corporativos).

# 5- Outras Configurações Importantes para VMs
  - **Definição de tamanho e tipo de VM** (considerando o balanceamento entre custo e desempenho).
  - **Escolha de zona de disponibilidade** para garantir alta disponibilidade.
  - **Backup automático** e **configurações de replicação** para garantir segurança e recuperação de desastres.

# 6- Cálculo de Custos Mensais
- A **Calculadora de Custos da Microsoft** estimou o custo mensal médio da configuração do banco de dados:
  - Esse valor varia de acordo com o tipo de VM, o uso de recursos e as opções adicionais escolhidas.


# Referências:
- [Calculadora de Custos Microsoft Azure](https://azure.microsoft.com/en-us/pricing/calculator/)
- [Documentação Azure SQL Database](https://learn.microsoft.com/en-us/azure/azure-sql/)
