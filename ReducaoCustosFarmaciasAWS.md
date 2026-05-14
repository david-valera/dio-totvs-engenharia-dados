# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 14/05/2026
Empresa: PharmaStream Solutions 
Responsável: David Rodriguez

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa PharmaStream Solutions, realizado por Analista de Dados Rodriguez. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- Amazon S3 Intelligent-Tiering
- Foco da ferramenta: Otimização automática de custos de armazenamento de dados.
- Descrição de caso de uso: Empresas farmacêuticas geram volumes massivos de dados brutos de ensaios clínicos que, após uma análise inicial, são acessados com frequência irregular. O Intelligent-Tiering move automaticamente os arquivos entre camadas de acesso frequente e raro sem impacto na performance, eliminando custos de recuperação de dados e reduzindo a fatura de storage em até 30%.

Etapa 2: 
- AWS Batch com Instâncias Spot
- Foco da ferramenta: Processamento de cargas de trabalho de computação de alto desempenho (HPC) a baixo custo.
- Descrição de caso de uso: Utilizado para simulações de acoplamento molecular e análise de bioinformática. Ao configurar o AWS Batch para utilizar Instâncias Spot (capacidade ociosa da AWS), a empresa executa análises complexas com descontos de até 90% em relação ao preço sob demanda, ideal para processos que podem ser reiniciados sem perda de integridade.

Etapa 3: 
- AWS Cost Explorer
- Foco da ferramenta: Visibilidade, governança e previsão de gastos.
- Descrição de caso de uso: Implementação de dashboards personalizados para identificar quais projetos de P&D (Pesquisa e Desenvolvimento) estão excedendo o orçamento. Através do recurso de "Rightsizing Recommendations", a ferramenta identifica instâncias de banco de dados superdimensionadas para os sistemas de gestão de laboratório (LIMS), sugerindo o downgrade imediato para economizar recursos desperdiçados.



## Conclusão
A implementação de ferramentas na empresa *PharmaStream Solutions tem como esperado a redução drástica do desperdício de recursos computacionais e a automação do ciclo de vida dos dados*, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

- Manual de Configuração de Ciclo de Vida do S3
- Planilha de Projeção de Economia (Spot vs On-Demand)
- Guia de Boas Práticas de Tagging para Centros de Custo

Assinatura do Responsável pelo Projeto:

David Rodriguez
