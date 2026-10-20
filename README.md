# LPs Emplavi

Landing pages da Emplavi publicadas em `emplavi.com.br/<pasta>/`.

- **Cada pasta na raiz é uma LP.** `residencial-agata/` vira `emplavi.com.br/residencial-agata/`.
- **Publicação automática:** um push no `main` envia por SFTP (com chave SSH) só as pastas que mudaram. Veja `.github/workflows/deploy.yml`.
- **Prévia:** https://mix7producao.github.io/emplavi-lps/. Na prévia, os formulários não enviam leads.
- **Antes de subir qualquer LP:** siga o [CHECKLIST-DEPLOY-EMPLAVI.md](CHECKLIST-DEPLOY-EMPLAVI.md). Não altere os campos do Hypnobox e teste um lead real depois.

| Pasta | Página |
|---|---|
| `residencial-agata/` | LP do Residencial Ágata |
| `obrigado-residencial-agata/` | Página de obrigado do Ágata |

Pastas que começam com `_` ou `.` não são publicadas.
