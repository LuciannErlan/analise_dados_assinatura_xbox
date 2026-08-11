# analise_dados_assinatura_xbox

# 🎮 Análise de Dados de Assinaturas (Dashboard Xbox)

## 📌 Sobre o Projeto
Este projeto apresenta a análise de uma base de dados (fictícia/simulada) de assinantes de um serviço de jogos semelhante ao ecossistema Xbox Game Pass. O objetivo principal do projeto é extrair métricas financeiras, entender o perfil de adesão dos usuários e responder a perguntas de negócio estruturadas através de um Dashboard interativo desenvolvido em Excel.

## 📊 Destaques e Insights da Análise
Com base na exploração da base de dados (295 registros de clientes), extraímos os seguintes insights principais:
- **Faturamento Total Gerado:** \$ 7.633
- **Equilíbrio de Planos:** A base de usuários está muito bem distribuída entre os planos oferecidos: **Core** (101 usuários), **Ultimate** (98) e **Standard** (96).
- **Frequência de Assinatura:** A modalidade de pagamento preferida é a **Mensal** (139 assinantes), seguida pela Trimestral (85) e Anual (71).
- **Renovação Automática:** Exatamente metade da base de clientes mantém a renovação automática ativa (148 com *Yes* e 147 com *No*), demonstrando uma área de oportunidade para campanhas de retenção.
- **Add-ons:** Os dados também mapeiam compras de Passes de Temporada extras, como *EA Play* e *Minecraft*, além do impacto de Cupons de Desconto no Valor Total (*Total Value*).

## 📂 Estrutura do Arquivo Excel
O documento analisado está dividido nas seguintes abas:

1. **A̳ssets (Ativos):** Contém a padronização visual, ícones e a paleta de cores (ex: #22C55E e #9BC848) baseada na identidade visual do Xbox.
2. **B̳ases:** A tabela principal (Raw Data) com o registro granular dos usuários (ID, Nome, Plano, Data de Início, Status de Renovação e Valores).
3. **C̳álculos:** Aba dedicada a tabelas dinâmicas e processamento de dados para responder a Perguntas de Negócio (ex: Faturamento de vendas de planos segregado por auto-renovação).
4. **D̳ashboard:** A camada de visualização final, consolidando os KPIs e gráficos interativos para tomada de decisão.

## 🛠️ Ferramentas Utilizadas
- **Microsoft Excel**: Limpeza de dados, Tabelas Dinâmicas e construção do Dashboard.
- **Análise de Dados**: Lógica de Negócio e extração de KPIs.
