# 📋 Resultado da Análise — Feedbacks de Clientes Bancários

> Análise gerada a partir do [prompt final](./README.md#prompt-final), aplicada à [base fictícia de 15 feedbacks](./dados-ficticios.md).

---

## Resumo Executivo

A análise de 15 feedbacks revela predominância de reclamações (7 registros), concentradas em instabilidade das interfaces digitais e tempo de espera excessivo nos canais de atendimento. Clientes 60+ enfrentam barreiras de acessibilidade no app. O chat recebe tanto elogios pela agilidade quanto críticas pela falta de resolução efetiva e indisponibilidade fora do horário comercial. As oportunidades mais claras estão na estabilização técnica do app e site, na ampliação da acessibilidade e na revisão dos SLAs de atendimento.

---

## Tabela Detalhada

| # | Tipo | Tema | Assunto | Faixa Etária | Sentimento | Evidência | Possível Impacto na Experiência | Ação Sugerida | Urgência |
|---|------|------|---------|-------------|------------|-----------|-------------------------------|---------------|----------|
| 1 | Reclamação | Interface digital | App trava ao fazer Pix à noite | 18–25 | Negativo | "o app travou três vezes seguidas. Perdi a paciência e desisti" | Alto — impede transação e gera abandono | Investigar instabilidade do app iOS em horário noturno; priorizar correção no próximo sprint | Alta |
| 2 | Elogio | Atendimento | Agilidade no atendimento via chat | 36–45 | Positivo | "resolveu meu problema com o cartão em menos de 10 minutos" | Positivo — reforça confiança no canal | Reconhecer boas práticas da equipe de chat; usar como referência de SLA | Baixa |
| 3 | Reclamação | Atendimento | Tempo de espera excessivo no telefone | 46–55 | Negativo | "Fiquei 40 minutos na espera"; "a ligação caiu" | Alto — frustração extrema e retrabalho | Revisar dimensionamento da equipe telefônica; implementar callback automático | Alta |
| 4 | Sugestão de melhoria | Interface digital | Filtro de extrato por categoria de gasto | 26–35 | Neutro/Positivo | "se o app tivesse um filtro de extrato por categoria de gasto" | Médio — agregaria valor e diferenciação | Avaliar viabilidade com equipe de UX; incluir no backlog de melhorias do app | Média |
| 5 | Elogio | Atendimento | Atendimento presencial com apoio digital | 60+ | Positivo | "o gerente me ensinou tudo com paciência. Agora consigo ver meu saldo" | Positivo — inclusão digital e fidelização | Replicar prática de apoio digital nas agências; criar programa de onboarding presencial | Baixa |
| 6 | Dúvida | Interface digital | Dificuldade para alterar senha no site | 18–25 | Negativo | "Não consigo achar onde muda a senha"; "O site é confuso" | Médio — compromete segurança e gera frustração | Revisar arquitetura de informação do Internet Banking com equipe de UX | Média |
| 7 | Reclamação | Atendimento | Cobrança indevida não resolvida no prazo | 26–35 | Negativo | "disse que ia resolver em 5 dias úteis, mas já fazem 15 dias" | Alto — quebra de confiança e risco regulatório | Auditar fila de estornos; revisar SLA e comunicação de prazos ao cliente | Alta |
| 8 | Elogio | Interface digital | Pagamento por aproximação no app | 36–45 | Positivo | "Adorei a nova funcionalidade de pagamento por aproximação" | Positivo — conveniência e modernidade | Divulgar funcionalidade para aumentar adoção; coletar mais feedback para evolução | Baixa |
| 9 | Dúvida | Atendimento | Informações sobre programa de pontos | 46–55 | Negativo | "ninguém soube me explicar direito" | Médio — perda de engajamento com o produto | Capacitar equipe telefônica sobre programa de pontos; criar FAQ acessível | Média |
| 10 | Sugestão de melhoria | Interface digital | Acessibilidade — tamanho de fonte no app | 60+ | Negativo | "As letras do app são muito pequenas"; "Precisa ter uma opção de letra maior" | Alto — exclui clientes com dificuldade visual | Implementar configuração de tamanho de fonte/modo acessível no app Android | Alta |
| 11 | Reclamação | Interface digital | Site instável ao gerar boleto | 18–25 | Negativo | "O site cai toda vez que tento gerar um boleto" | Alto — impede operação financeira básica | Investigar erro na geração de boletos no Internet Banking; priorizar correção | Alta |
| 12 | Reclamação | Atendimento | Tempo de espera excessivo na agência | 26–35 | Negativo | "esperei quase 1 hora para uma operação simples" | Alto — frustração e possível churn | Avaliar sistema de agendamento online; otimizar triagem na agência | Alta |
| 13 | Sugestão de melhoria | Atendimento | Chat disponível 24h | 36–45 | Neutro | "Vocês poderiam ter atendimento por chat 24h" | Médio — limita suporte fora do horário comercial | Avaliar viabilidade de chatbot noturno ou extensão de horário do chat | Média |
| 14 | Reclamação | Interface digital | App lento após atualização | 46–55 | Negativo | "demora uns 20 segundos para abrir. Antes era instantâneo" | Alto — regressão de performance perceptível | Investigar regressão de performance no app iOS pós-atualização | Alta |
| 15 | Elogio | Interface digital | Funcionalidade de investimentos | 26–35 | Positivo | "Consigo comparar CDBs e fundos de forma visual e clara" | Positivo — diferenciação competitiva | Destacar como case de sucesso interno; expandir para outros produtos | Baixa |

---

## Tabela Resumida

| Tema | Sentimento Geral | Urgência | Ação Sugerida |
|------|-----------------|----------|---------------|
| Interface digital — Estabilidade (app e site) | Negativo | Alta | Priorizar correções de travamentos no app (Pix noturno, lentidão pós-update) e quedas no Internet Banking (geração de boletos) |
| Atendimento — Tempo de espera (telefone e agência) | Negativo | Alta | Revisar dimensionamento das equipes; implementar callback automático e agendamento online |
| Atendimento — Resolução de demandas (chat e telefone) | Misto | Alta | Auditar SLAs de estorno; capacitar equipe sobre produtos (ex.: programa de pontos) |
| Interface digital — Acessibilidade | Negativo | Alta | Implementar modo acessível no app (fonte ajustável, contraste) para público 60+ |
| Interface digital — Novas funcionalidades | Positivo | Baixa | Manter ritmo de inovação (aproximação, investimentos); avaliar sugestão de filtro por categoria |
| Atendimento — Disponibilidade do chat | Neutro | Média | Avaliar chatbot ou extensão de horário para cobertura noturna |
| Atendimento — Experiência presencial | Positivo | Baixa | Replicar boas práticas de onboarding digital nas agências |

---

## 🔺 3 Prioridades Mais Importantes

1. **Estabilizar app e site.** Quatro feedbacks reportam falhas técnicas que impedem operações básicas (Pix, boleto, lentidão). Impacto direto na capacidade do cliente usar os serviços e alto risco de churn. *Ação: escalar para engenharia com prioridade máxima.*

2. **Reduzir tempo de espera nos canais de atendimento.** Telefone e agência concentram reclamações de espera superior a 40 minutos e 1 hora, respectivamente. Somado à ligação que caiu sem resolução, o cenário aponta para subdimensionamento de equipe. *Ação: revisar capacity planning e implantar callback automático e agendamento.*

3. **Implementar acessibilidade no app.** O público 60+ relata impossibilidade de leitura por tamanho de fonte. Além de excluir um segmento importante, há risco de descumprimento de normas de acessibilidade digital. *Ação: incluir modo de acessibilidade (fonte, contraste) no roadmap de UX com prazo definido.*

---

> **Limitação identificada:** A base analisada contém apenas 15 registros, o que impede generalizações estatísticas. As tendências apontadas são indicativas e devem ser validadas com uma amostra maior antes de fundamentar decisões de grande investimento.
