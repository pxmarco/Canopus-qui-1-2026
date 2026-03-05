1 - Informações gerais

1.1 - Nome do sistema: Cash Alert

1.2 - Nome da equipe: Canopus


2 - Problema e/ou necessidade 

2.1 - Qual é o problema e/ou necessidade que o software deve resolver: 

O sistema tem o propósito de garantir controle e planejamento financeiro para visualizar movimentações e evitar atrasos por meio de alertas e lembretes baseados em datas, prazos e valores de entrada e saída.

2.2 - Quais são as dores dos usuários: 

Boletos e contas atrasando ou vencendo;

Geração de multas e juros;

Ansiedade financeira e problemas psicológicos.

2.3 - O que acontece hoje sem o sistema: 

Acúmulo de contas atrasadas;

Falta de organização desejada com o saldo;

Esquecimento de prazos de despesas;

Falta de planejamento para lidar com valores de despesas;

Organização financeira em planilhas simples ou anotações informais;

Não há um sistema para lembrar o usuário de seus planejamentos e despesas.


3 - Escopo funcional do sistema

3.1 - Principal objetivo do sistema:

Registrar receitas e despesas a fim de promover controle financeiro pessoal eficiente, prevenindo atrasos por meio de alertas automatizados de vencimentos e desorganização nos demais gastos.


3.2 - Funcionalidades específicas (secundárias) do sistema:

Cadastrar perfil do usuário;

Registrar saldo inicial;

Cadastrar receitas;

Cadastrar despesas;

Cadastrar reservas financeiras;

Cadastrar categorias de receitas;

Cadastrar categorias de despesas;

Cadastrar categorias de reservas financeiras;

Classificar despesas como fixas ou variáveis;

Configurar alertas para vencimento de despesas;

Configurar alertas personalizados;

Visualizar registros em formato de calendário;

Gerar relatório financeiro mensal;

Realizar buscas por filtros: saldo, categoria e intervalo de tempo;

Criar históricos dos relatórios mensais;


4. Escopo não funcional

Arquitetura baseada no padrão MVC (Model-View-Controller);

Segurança: política de privacidade LGPD, com autenticação por senha ou token via email/telefone (OpenID).

Desempenho: tempo de resposta < 2s para registrar e <3s para consultar; caching de memórias acessadas com frequência..

Disponibilidade e confiabilidade: backups automáticos para cada movimentação registrada no sistema; sistema disponível 24x7x365; Em caso de indisponibilidade temporária do servidor, o sistema deverá permitir funcionamento limitado offline, com sincronização posterior.

Qualidade: todas as funcionalidades serão testadas, com 100% de cobertura para os fluxos críticos, cerca de 70–80% para funcionalidades secundárias e 60–70% para requisitos de suporte e não funcionais.

Usabilidade e acessibilidade: acessibilidade adequada e usabilidade onboarding (simplificada e intuitiva).

Conformidade e governança de dados: classificar dados (pessoal/sensível), política de retenção.


5. Usuários

Usuário final: pessoa física interessada em organizar e controlar suas finanças pessoais por meio do registro de receitas e despesas.


6. Entregáveis

- Documento de Visão do Sistema;

- Diagrama de Caso de Uso;

- Especificação de Caso de Uso;

- Diagrama de Classe;

- Documento de Arquitetura do Sistema;

- Protótipo do Sistema.

