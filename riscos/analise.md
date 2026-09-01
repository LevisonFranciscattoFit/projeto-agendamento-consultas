# Análise Qualitativa de Riscos

## 1. Risco de Instabilidade na API Externa
- **Impacto:** Alto (Pode bloquear a entrega principal da aplicação, que é crítica).
- **Fatores Condicionantes:** Mudanças recentes sem aviso no sistema de terceiros e documentação deficiente.

## 2. Risco de Alteração de Requisitos no Agendamento
- **Impacto:** Médio/Alto (Exige refatoração do código já implementado e retrabalho).
- **Fatores Condicionantes:** Falta de validação prévia detalhada com a equipe de negócio nas fases iniciais.

## 3. Risco de Sobrecarga e Gargalo no Teste/Desenvolvimento
- **Impacto:** Alto (Risco de atraso nas datas de entrega e queda na qualidade do software).
- **Fatores Condicionantes:** Equipe enxuta (apenas 1 QA para 4 desenvolvedores) e aumento não planejado do escopo.
