# 🧩 Versionamento Semântico – AURA-projects

A **AURA-projects** utiliza o padrão **[Semantic Versioning 2.0.0](https://semver.org/lang/pt-BR/)** para nomear versões de todos os seus projetos e pacotes.  
Esse modelo garante previsibilidade, estabilidade e clareza sobre o impacto de cada alteração.

---

## 📘 Estrutura da Versão

As versões seguem o formato:
MAJOR.MINOR.PATCH

| Parte | Exemplo | Descrição |
|--------|----------|------------|
| **MAJOR** | `1.x.x` | Alterações incompatíveis com versões anteriores. |
| **MINOR** | `x.2.x` | Novas funcionalidades compatíveis. |
| **PATCH** | `x.x.3` | Correções de bugs ou pequenas melhorias compatíveis. |

---

## 🧠 Regras Gerais

- **Aumente MAJOR** quando houver mudanças incompatíveis na API ou no comportamento.  
- **Aumente MINOR** quando adicionar funcionalidades compatíveis.  
- **Aumente PATCH** quando corrigir bugs ou ajustar comportamento sem impacto na compatibilidade.  
- **Versões 0.x.x** são consideradas de desenvolvimento inicial e podem sofrer alterações a qualquer momento.  

---

## 🧱 Exemplo de Evolução

| Versão | Tipo de Alteração | Descrição |
|---------|--------------------|------------|
| `1.0.0` | Inicial | Primeira versão estável. |
| `1.1.0` | Minor | Nova funcionalidade adicionada. |
| `1.1.1` | Patch | Correção de bug. |
| `2.0.0` | Major | Mudança estrutural incompatível. |

---

## 🧩 Versões Pré-Lançamento

Durante o desenvolvimento de novas features ou versões grandes, utilize sufixos de pré-lançamento:

| Sufixo | Significado | Exemplo |
|---------|--------------|----------|
| `-alpha` | Versão inicial instável | `2.0.0-alpha.1` |
| `-beta` | Versão em testes | `2.0.0-beta.3` |
| `-rc` | *Release candidate* (pré-final) | `2.0.0-rc.1` |

Essas versões **não devem ser usadas em produção**.

---

## 🧾 Changelog Padrão

Cada repositório AURA deve conter um arquivo `CHANGELOG.md` com o histórico de alterações.  
O changelog deve seguir o formato **Keep a Changelog** ([keepachangelog.com](https://keepachangelog.com/pt-BR/1.0.0/)) e agrupar as mudanças em seções semânticas.

### Estrutura recomendada:

```markdown
# Changelog

Todas as mudanças relevantes deste projeto serão documentadas neste arquivo.

O formato é baseado em [Keep a Changelog](https://keepachangelog.com/pt-BR/1.0.0/),
e este projeto adere a [Semantic Versioning](https://semver.org/lang/pt-BR/).

## [1.2.0] - 2025-10-07
### Added
- Implementação do módulo de autenticação.
- Novo componente de layout responsivo.

### Changed
- Atualização das dependências principais.

### Fixed
- Correção no cálculo de tokens de sessão.

## [1.1.0] - 2025-09-15
### Added
- Nova API de relatórios.
```

## ⚙️ Automação de Versionamento

A AURA-projects recomenda o uso de versionamento automatizado com base em conventional commits e ferramentas como:
- semantic-release
- standard-version
Essas ferramentas geram:
- Versões automaticamente com base nos commits (feat, fix, etc.);
- CHANGELOG.md atualizado;
- Tags no Git (v1.2.3);
- Publicação automatizada (npm, Docker, etc.).

## 🪜 Política de Lançamentos
| Ambiente            | Tipo de versão                     | Tag Git        | Política                       |
| ------------------- | ---------------------------------- | -------------- | ------------------------------ |
| **Desenvolvimento** | Pré-lançamento (`-alpha`, `-beta`) | `vX.Y.Z-alpha` | Publicado para testes internos |
| **Homologação**     | Release Candidate (`-rc`)          | `vX.Y.Z-rc`    | Estágio de validação final     |
| **Produção**        | Versão estável (`X.Y.Z`)           | `vX.Y.Z`       | Publicado oficialmente         |


## 🧩 Tags e Releases no GitHub
Cada nova versão deve ser tagueada e publicada no GitHub com:

```bash
git tag -a v1.3.0 -m "Release 1.3.0"
git push origin v1.3.0
```

O título da release deve conter a versão (v1.3.0) e o corpo deve incluir o changelog correspondente.

## 🧠 Boas Práticas

✅ Use commits semânticos para facilitar o versionamento automático.

✅ Sempre atualize o CHANGELOG.md junto com a versão.

✅ Evite releases manuais sem justificativa.

✅ Utilize tags Git coerentes e consistentes.

✅ Teste a versão antes de publicar em ambientes críticos.

## 🪙 Histórico de Revisões
| Data       | Versão | Alterações                                | Aprovado por    |
| ---------- | ------ | ----------------------------------------- | --------------- |
| 2025-10-07 | 1.0    | Versão inicial do padrão de versionamento | Governance Team |

<p align="center"> <em>Versionar é evoluir com responsabilidade.</em><br> — AURA-projects </p>
