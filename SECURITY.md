# 🛡️ Segurança – AURA-projects

## 📘 Visão Geral

A **AURA-projects** está comprometida em manter **os mais altos padrões de segurança** em todos os seus projetos.  
Este documento descreve **como reportar vulnerabilidades**, práticas recomendadas de desenvolvimento seguro e responsabilidades de todos os colaboradores.

---

## 🚨 Reporte de Vulnerabilidades

Se você encontrar uma vulnerabilidade em qualquer projeto da AURA:

1. **Evite explorar a falha publicamente.**  
2. **Reporte imediatamente** para a equipe de segurança da organização.

### Contato seguro:

- Email dedicado: `security@aura-projects.org`  
- Assunto do email: `[SECURITY] <Projeto> - <Descrição breve da vulnerabilidade>`  
- Inclua:
  - Projeto afetado e versão;
  - Passos para reproduzir o problema;
  - Impacto potencial;
  - Sugestões de mitigação, se aplicável.

> Todas as submissões serão tratadas **com confidencialidade**.

---

## ⚙️ Processo de Avaliação

1. Recebimento do reporte pelo **Governance Team** ou Security Team.  
2. **Classificação do risco** (Baixo, Médio, Alto, Crítico).  
3. **Notificação aos mantenedores** do projeto afetado.  
4. **Mitigação e correção**: implementação de patch ou solução temporária.  
5. **Divulgação controlada**: a vulnerabilidade será publicada apenas após correção ou mitigação adequada.

---

## 🔒 Boas Práticas de Segurança

Todos os projetos AURA devem adotar:

- **Dependências confiáveis e atualizadas**;  
- **Revisão de código e auditoria de segurança** periódica;  
- **Validação de entradas de usuários** para prevenir ataques (XSS, SQL Injection, etc.);  
- **Criptografia adequada** para dados sensíveis;  
- **Segurança em pipelines de CI/CD**;  
- **Controle de acessos e permissões** restrito a funções essenciais.

---

## 🧩 Responsabilidades dos Contribuidores

- Contribuir com código seguro e seguindo boas práticas.  
- Reportar vulnerabilidades ou riscos de forma imediata e responsável.  
- Revisar Pull Requests com atenção a problemas de segurança.  
- Manter confidencialidade de dados sensíveis de usuários e sistemas.

---

## 🛠️ Atualizações de Segurança

- As correções de segurança devem ser **priorizadas**.  
- Versionamento de patches segue a política de **Semantic Versioning** (PATCH ou HOTFIX).  
- Releases contendo correções críticas devem ser comunicadas via changelog e GitHub Releases.

---

## 📄 Referências e Recursos

- [OWASP Top 10](https://owasp.org/www-project-top-ten/) – Guia de principais vulnerabilidades web  
- [GitHub Security Advisories](https://docs.github.com/en/code-security/security-advisories)  
- [Semantic Versioning](VERSIONING.md) – Controle de releases de segurança  
- [CONTRIBUTING.md](CONTRIBUTING.md) – Fluxo de contribuição seguro

---

<p align="center">
  <em>Segurança é responsabilidade de todos — cada linha de código conta.</em><br>
  — AURA-projects
</p>
