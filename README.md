# Visual DNA v6.2

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


Curso gratuito de direÃ§Ã£o de arte com caso fictÃ­cio autoral.

Fontes editoriais em context/conteudo-base.json e context/aulas-editoriais.json. Montar com `python3 montar.py`; motor oficial formato-curso-v6 necessÃ¡rio.

IlustraÃ§Ãµes geradas com Codex image_gen; o mecanismo nÃ£o expÃµe seletor de versÃ£o do modelo nesta sessÃ£o. NÃ£o contÃ©m vÃ­deos ou transcriÃ§Ãµes do material de origem.

## English / EspaÃ±ol

[English](https://inematds.github.io/curso-visual-dna/en/) Â· [EspaÃ±ol](https://inematds.github.io/curso-visual-dna/es/)

Textos traduzidos com GPT-6 Luna por subagentes nativos da assinatura Codex, sem API externa. IlustraÃ§Ãµes originais compartilhadas; progresso e anotaÃ§Ãµes separados por idioma.

ApÃ³s montar o portuguÃªs, reaplique os catÃ¡logos salvos:

```sh
python3 scripts/i18n_local.py build .
python3 scripts/verify_i18n.py .
node scripts/check_i18n_browser.cjs . /tmp/curso-i18n-checks
```

Requer Python/BeautifulSoup e os pacotes locais Babel/Playwright indicados nos scripts. A montagem nÃ£o chama modelos nem redes. MudanÃ§as na fonte PT exigem revisar os catÃ¡logos `i18n/`. O motor oficial `assets/curso.js` Ã© preservado; a proteÃ§Ã£o de importaÃ§Ã£o Ã© gerada em `assets/curso-i18n.js` e nas ediÃ§Ãµes traduzidas.

EvidÃªncias em `context/validacao-i18n.md`. RevisÃµes por agentes sÃ£o simuladas, nÃ£o testes com alunos reais.

<!-- inema-backlink:v1 -->
## Mais no INEMA.CLUB

- [Ficha completa deste curso](https://www.inema.club/cursos/296-visual-dna-direcao-de-arte-e-branding-com-ia-v6-2/)
- [Guia: como aprender inteligÃªncia artificial](https://www.inema.club/aprender-inteligencia-artificial/)
- [Todos os cursos](https://www.inema.club/cursos/)
<!-- /inema-backlink:v1 -->

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>