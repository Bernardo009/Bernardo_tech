# **SystemCall – Gestão Inteligente de Chamados Técnicos**

**Automatize o suporte técnico com triagem por Inteligência Artificial**

--- 

## 📌 Sobre o SystemCall

O **SystemCall** é um sistema de **gestão de chamados técnicos** desenvolvido pela Bernardo Tech para otimizar o atendimento em empresas de tecnologia, mobilidade urbana e outros setores que demandam suporte constante. Com uso de **Inteligência Artificial para triagem automática**, o sistema oferece mais agilidade, organização e precisão no tratamento de incidentes.

---

## 🎯 Missão

Transformar o atendimento técnico por meio da automação, proporcionando **respostas rápidas**, **priorização eficiente**, **organização de equipes de suporte** e **transparência nos processos**, sempre em conformidade com a **LGPD**.

---

## 💡 Funcionalidades do Sistema

- **Abertura de chamados com interface web, mobile e Desktop**
- **Triagem automática de chamados com uso de IA**, categorizando e atribuindo prioridade
- **Painel de atendimentos em tempo real**
- **Histórico completo de interações**
- **Encaminhamento automático para setores responsáveis**
- **Relatórios personalizados de desempenho**
- **Notificações por e-mail**
- **Sistema seguro e compatível com a LGPD**

---

## 📁 Documentação Técnica

> ⚠️ **Nota:** Este repositório contém os artefatos acadêmicos utilizados para simular o desenvolvimento do sistema SystemCall, incluindo requisitos, diagramas e planejamento ágil.

- Levantamento de requisitos
- Backlog do produto e sprints
- Diagramas UML (caso de uso, classe, sequência e implantação)
- Protótipos de interface
- Estrutura do banco de dados
- Estratégias de integração com serviços de IA (Azure/OpenAI)

---

## 🧠 Contexto do Projeto

O **SystemCall** foi desenvolvido como parte de um projeto acadêmico multidisciplinar (PIM III e IV), simulando um produto de mercado dentro de uma empresa de tecnologia fictícia, **Bernardo Tech**.

---


## 🛠️ Tecnologias Utilizadas

- **Python** [Downloads](https://www.python.org/downloads/)
- **Astah** [Downloads](https://astah.net/products/astah-uml/)
- **Postgree** [Downloads](https://www.postgresql.org/download/)
- **Azure AI / OpenAI** para triagem inteligente
- **GitHub Projects** para gestão ágil

---


© 2024 PagBus Solutions / BernardoTech. Todos os direitos reservados.

---


## 👤 Autor

- **João Pedro Maximiliano Bernardo** — Desenvolvedor e mantenedor do projeto (projeto individual BernardoTech).
- | [GitHub](https://github.com/Bernardo009/Bernardo_tech)    | [LinkedIn](https://www.linkedin.com/in/jo%C3%A3o-pedro-maximiliano-bernardo-4172a41a7/) |

---

## 📝 Padrão de mensagens de commit

Adote um padrão simples inspirado no *Conventional Commits*, com o formato:

```
<tipo> (<id_issue opcional>): <descrição curta no imperativo>
```

**Tipos mais comuns:** `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`.

**Exemplos:**
```
feat (#12): implementa triagem por IA no cadastro de chamados
fix: corrige validação de prioridade ao encerrar chamado
docs: inclui diagrama de sequência e instruções de build
```

---

## 🌱 Estratégia de branch

Siga **GitHub Flow** para desenvolvimento individual:

- `main` mantém a versão estável.
- Crie branches curtas por assunto: `feature/triagem-ia`, `fix/fechamento-chamado`.
- Abra um Pull Request para revisar o que será integrado (mesmo em projeto solo, use checklist de revisão).
- Faça *merge* após testes passarem.

---

## ✅ Boas práticas de Git (resumo)

- Crie um `.gitignore` desde o início (logs, binários, segredos).
- Evite *commits* grandes; prefira entregas pequenas e objetivas.
- Use descrições claras nos PRs e, quando possível, liste cenários de teste.
- Não faça *commit* direto em `main`; trabalhe por branches e PRs.
- Relacione *issues* nos commits/PRs quando existir rastreio de tarefas.

