# 🏦 Extraindo Insights do Feedback de Clientes Bancários

**Desafio Criativo — DIO**

Neste desafio, construí um prompt passo a passo para orientar uma IA a extrair insights de feedbacks de clientes bancários, seguindo três etapas:

1. **Definir a intenção** — o que a IA deve produzir, para quem e com qual finalidade
2. **Adicionar contexto e restrições** — dados disponíveis, critérios de análise e cuidados
3. **Unir as peças e refinar** — montar e revisar o prompt final

---

## Prompt Final

```
Atue como um Analista de Customer Success especialista em ambientes bancários.

Sua tarefa é analisar feedbacks de clientes bancários sobre atendimento ao cliente para
identificar dúvidas, reclamações, sugestões de melhorias e elogios.

Contexto: A análise será usada por uma equipe de Customer Success para priorizar melhorias
em todos os canais de atendimento, bem como na utilização dos serviços bancários através
das interfaces digitais.

Dados disponíveis: A base contém data do comentário, faixa etária do cliente, canal de
atendimento, tipo de software (para feedbacks entregues por meio digital), texto do feedback
e nota de satisfação de 1 a 5.

Instruções de análise:

1. Classifique os feedbacks por:
   1.1 tipo: dúvidas, reclamações, sugestões de melhorias, elogios ou outros
       (use "outros" ou crie uma nova categoria, se necessário)
   1.2 tema: sobre atendimento, sobre interface digital ou outros
       (use "outros" ou crie uma nova categoria, se necessário)
   1.3 assunto
   1.4 faixa etária do cliente
   1.5 sentimento
   1.6 urgência
   1.7 possível impacto na experiência do cliente
2. Identifique os principais padrões, problemas, elogios e oportunidades.
3. Aponte evidências nos dados fornecidos.
4. Sugira ações práticas para as equipes de Customer Success e User Experience do banco.

Formato da resposta: Entregue um resumo executivo com até 5 linhas, uma tabela com as
classificações tipo, tema, assunto, faixa etária do cliente, sentimento, evidência,
possível impacto na experiência do cliente, ação sugerida e urgência, uma tabela resumida
contendo tema, sentimento, urgência e ação sugerida, além de uma lista final com as
3 prioridades mais importantes.

Restrições:

- Use apenas os dados fornecidos.
- Não invente números, causas ou conclusões.
- Não exponha dados pessoais ou sensíveis.
- Informe limitações quando os dados não forem suficientes.
- Use linguagem executiva, direta e voltada para tomada de decisão.
```

---

## Teste com Dados Fictícios

Para validar o prompt, criei uma base fictícia e apliquei a análise:

| Arquivo | Descrição |
|---------|-----------|
| [dados-ficticios.md](./dados-ficticios.md) | 15 feedbacks fictícios com diferentes perfis, canais e tipos de problema |
| [resultado-analise.md](./resultado-analise.md) | Resultado completo da análise: resumo executivo, tabelas e prioridades |
