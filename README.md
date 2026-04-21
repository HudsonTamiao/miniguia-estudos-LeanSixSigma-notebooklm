# Estudos-LeanSixSigma-notebooklm
Estudo direto Sobre Melhoria Contínua

# 1. Contexto e Objetivos
Este repositório é o resultado de um estudo intensivo focado na aplicação da metodologia Lean Six Sigma (Green Belt) para a otimização da Gestão de Frotas e Planejamento e Controle de Manutenção (PCM) em um cenário agroindustrial.

O objetivo central é consolidar ferramentas estatísticas e analíticas (como Testes de Hipóteses, MSA, ANOVA e DOE) para transformar dados brutos de campo em decisões estratégicas que reduzam o downtime de máquinas e otimizem o custo por hora trabalhada.

# 2. Curadoria de Fontes
Utilizei o NotebookLM para processar e conectar os conhecimentos das seguintes fontes:

Metodologia Green Belt na Manutenção Automotiva: (Vídeo/Aulas focadas em aplicação prática de oficina).

Fundamentos de Estatística Aplicada (Minitab): Documentação técnica sobre testes de hipóteses e análise de variabilidade.

Manual de MSA e FMEA: Diretrizes para análise de sistemas de medição e prevenção de falhas em ativos.

Estudos de Caso Lean Seis Sigma: Exemplos reais de redução de desperdício em ambientes de manutenção.

# 3. Engenharia de Prompts e "Cicatrizes" (Troubleshooting)
O maior desafio deste projeto foi conectar a teoria densa do Six Sigma (frequentemente explicada para indústrias de manufatura de peças) com a volatilidade do setor agrícola.

Prompts Testados:
Prompt Inicial (Fraco): "Me explique como aplicar Green Belt na manutenção."

Resultado: Resposta genérica e teórica.

Prompt Refinado (Estratégico): "Como um assistente de controle de frota agrícola pode aplicar o Teste t de 2 amostras para validar a troca de um fornecedor de pneus, considerando a variabilidade do solo?"

Resultado: Resposta técnica focada em CPK e significância estatística.

"Cicatrizes" de Aprendizado:
Dificuldade: O modelo inicialmente ignorava a diferença entre manutenção preventiva e preditiva no campo.

Ajuste: Tive que alimentar o contexto com o impacto da Telemetria e sensores (ESP32) para que a IA entendesse que o dado é gerado em tempo real, e não apenas em auditorias anuais.

#4. Miniguia de Estudo (Entrega Final)
📚 Resumos Estruturados
O material está dividido em cinco pilares fundamentais para o PCM:

Fundamentos de TH: Como provar que uma melhoria não foi "sorte".

MSA (Sistemas de Medição): Garantir que o paquímetro do mecânico e o sensor da colheitadeira estão falando a verdade.

ANOVA & Regressão: Identificar quais variáveis (modelo, operador, clima) realmente afetam o consumo de diesel.

DOE (Delineamento de Experimentos): Testar novas configurações de colheita sem parar a produção por tentativa e erro.

Controle Estático: Uso de Cartas de Controle para monitorar o MTBF (Tempo Médio Entre Falhas).
<img width="343" height="235" alt="image" src="https://github.com/user-attachments/assets/3e9d37a4-7caf-4dc5-80bb-f08dc1a271ae" />

# Glossário de Conceitos-Chave
P-Value: O "termômetro" da decisão. Se for menor que 0,05, a mudança que você fez na frota realmente funciona.

FMEA: Documento vivo que prevê onde a colheitadeira vai quebrar antes mesmo dela sair para o talhão.

R-Square: O quanto você realmente entende o seu problema (ex: "80% do custo de manutenção é explicado pela idade da máquina").

Gage R&R: Teste para saber se a medição de desgaste de pneus é consistente entre diferentes turnos de inspetores.

# Prompts Reutilizáveis para Revisão
"Resuma os critérios de escolha entre um teste Z e um teste t para amostras de manutenção de frota."

"Crie um checklist de FMEA para uma falha crítica de superaquecimento em tratores série 8R."

"Explique como interpretar um gráfico de resíduos de uma regressão de consumo de combustível."
