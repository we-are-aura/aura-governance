# 🤝 Guia de Contribuição – AURA-projects

Obrigado por dedicar seu tempo para contribuir com a **AURA-projects**!  
Este documento descreve as **diretrizes oficiais** para colaboração e desenvolvimento dentro dos projetos da organização.

Nosso objetivo é garantir que todas as contribuições mantenham um **alto padrão de qualidade, consistência e transparência**.

---

## 📘 Sumário
- [Como Contribuir](#-como-contribuir)
- [Padrão de Branches](#-padrão-de-branches)
- [Commits Semânticos](#-commits-semânticos)
- [Pull Requests (PRs)](#-pull-requests-prs)
- [Revisões e Aprovações](#-revisões-e-aprovações)
- [Guia de Estilo](#-guia-de-estilo)
- [Boas Práticas](#-boas-práticas)
- [Recursos Úteis](#-recursos-úteis)

---

## 🚀 Como Contribuir

1. **Crie um fork** do repositório desejado dentro da organização.  
2. **Crie uma branch** descritiva para sua modificação (veja o padrão abaixo).  
3. **Implemente** sua melhoria, correção ou documentação.  
4. **Envie um Pull Request (PR)** para o repositório principal.  
5. Aguarde a **revisão e aprovação** de um mantenedor.

> 💡 Antes de abrir um PR, verifique se já existe uma issue relacionada à sua contribuição.

---

## 🌱 Padrão de Branches

Para manter um fluxo organizado, seguimos o padrão **Gitflow simplificado**:

| Tipo | Convenção | Exemplo |
|------|------------|----------|
| Branch principal | `main` | — |
| Desenvolvimento | `develop` | — |
| Funcionalidades | `feature/<descrição>` | `feature/add-login-form` |
| Correções | `fix/<descrição>` | `fix/button-alignment` |
| Documentação | `docs/<descrição>` | `docs/update-readme` |
| Lançamentos | `release/<versão>` | `release/1.2.0` |
| Hotfixes | `hotfix/<descrição>` | `hotfix/urgent-api-fix` |

---

## 🧩 Commits Semânticos

Todos os commits devem seguir o formato de **Conventional Commits**:

```
<tipo>(escopo opcional): <descrição breve>
```


**Tipos válidos:**
- `feat` → nova funcionalidade  
- `fix` → correção de bug  
- `docs` → alteração na documentação  
- `style` → mudanças de formatação sem impacto funcional  
- `refactor` → refatoração sem mudança de comportamento  
- `test` → inclusão ou atualização de testes  
- `chore` → tarefas internas ou manutenção  
- `perf` → otimizações de performance  
- `build` → alterações em build ou dependências  
- `ci` → ajustes em pipelines e integração contínua  

**Exemplos:**
```bash
feat(auth): add JWT-based authentication
fix(ui): correct button alignment in mobile view
docs(readme): update setup instructions
```
> 💬 Dica: Commits semânticos ajudam no versionamento automático e geração de changelogs.

---

## 🔀 Pull Requests (PRs)
Antes de abrir um PR:
1. Sincronize sua branch com develop ou main.
2. Verifique se o código segue os padrões de lint, formatação e testes.
3. Descreva claramente o objetivo e impacto das alterações.
4. Associe o PR a uma issue existente, se aplicável.
> Use o modelo padrão de Pull Request disponível em TEMPLATES/PULL_REQUEST_TEMPLATE.md.

---

## 🔎 Revisões e Aprovações
- Todo PR requer ao menos uma revisão aprovada de um Project Maintainer.
- PRs que alterem políticas, arquitetura ou segurança exigem duas aprovações (um mantenedor + um core maintainer).
  - Revisores devem:
  - Verificar conformidade com o código existente.
  - Avaliar clareza, desempenho e impacto.
  - Solicitar ajustes com comentários objetivos.

---

## 🎨 Guia de Estilo

Cada projeto AURA pode ter suas próprias regras adicionais (lint, formatação, etc.), mas todos devem seguir princípios gerais:
- Código limpo e legível.
- Comentários claros e necessários.
- Funções e variáveis com nomes significativos.
- Evite duplicação de lógica.
- Sempre inclua testes (quando aplicável).
- Documente comportamentos importantes.

--- 

## 💡 Boas Práticas

✅ Crie PRs pequenos e com propósito único.
✅ Prefira clareza a esperteza.
✅ Teste localmente antes de enviar.
✅ Respeite o tempo e o feedback dos revisores.
✅ Mantenha a comunicação construtiva.

--- 

## 🔗 Recursos Úteis

- Guia de Versionamento Semântico
- Política de Governança
- Código de Conduta
- Segurança e Reporte de Vulnerabilidades

<p align="center"> <em>Contribuir com a AURA-projects é colaborar com excelência, propósito e comunidade.</em><br> 💙 <a href="https://github.com/AURA-projects">github.com/AURA-projects</a> </p>









