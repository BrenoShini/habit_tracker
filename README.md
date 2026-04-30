# Do.it - Gerenciamento e Evolução de Rastreador de Hábitos

O Do.it é um projeto de evolução de software baseado no repositório open-source habit_tracker. Este trabalho é desenvolvido como parte da disciplina SSC0535 - Gerência de Configuração, Evolução e Manutenção de Software no ICMC-USP.

O objetivo central é transformar uma ferramenta de rastreio básico em um sistema de alta retenção, utilizando técnicas de gamificação e uma estrutura de dados voltada para metas quantificáveis.

## Funcionalidades em Desenvolvimento

Diferente de rastreadores convencionais, o Do.it foca nos seguintes pilares de evolução:

* Registro Dual: Gestão de hábitos positivos (incorporar) e hábitos nocivos (reduzir).
* Metas Quantificáveis: Implementação de objetivos mensuráveis atrelados a valores numéricos.
* Gamificação: Sistema de recompensas e troféus baseado na manutenção de ofensivas (streaks).
* Persistência de Dados: Histórico visual via calendário e exportação de logs em CSV.
* Gestão de Exceções: Funcionalidade para pausa temporária no rastreio sem perda de progresso histórico.

## Arquitetura e Tecnologias

* Frontend: Vue.js (Interface Responsiva)
* Backend: Node.js com framework Express
* Banco de Dados: SQLite
* Conteinerização: Docker e Docker Compose
* Qualidade de Código: Integração com SonarCloud para análise estática e segurança
