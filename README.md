# Visual DNA v6.2

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


Curso gratuito de direêÂ§êÂ£o de arte com caso fictêÂ­cio autoral.

Fontes editoriais em context/conteudo-base.json e context/aulas-editoriais.json. Montar com `python3 montar.py`; motor oficial formato-curso-v6 necessêÂ¡rio.

IlustraêÂ§êÂµes geradas com Codex image_gen; o mecanismo nêÂ£o expêÂµe seletor de versêÂ£o do modelo nesta sessêÂ£o. NêÂ£o contêÂ©m vêÂ­deos ou transcriêÂ§êÂµes do material de origem.

## English / EspaêÂ±ol

[English](https://linnoff88-dev.github.io/ êÂ· [EspaêÂ±ol](https://linnoff88-dev.github.io/

Textos traduzidos com GPT-6 Luna por subagentes nativos da assinatura Codex, sem API externa. IlustraêÂ§êÂµes originais compartilhadas; progresso e anotaêÂ§êÂµes separados por idioma.

ApêÂ³s montar o portuguêÂªs, reaplique os catêÂ¡logos salvos:

```sh
python3 scripts/i18n_local.py build .
python3 scripts/verify_i18n.py .
node scripts/check_i18n_browser.cjs . /tmp/curso-i18n-checks
```

Requer Python/BeautifulSoup e os pacotes locais Babel/Playwright indicados nos scripts. A montagem nêÂ£o chama modelos nem redes. MudanêÂ§as na fonte PT exigem revisar os catêÂ¡logos `i18n/`. O motor oficial `assets/curso.js` êÂ© preservado; a proteêÂ§êÂ£o de importaêÂ§êÂ£o êÂ© gerada em `assets/curso-i18n.js` e nas ediêÂ§êÂµes traduzidas.

EvidêÂªncias em `context/validacao-i18n.md`. RevisêÂµes por agentes sêÂ£o simuladas, nêÂ£o testes com alunos reais.

<!-- ARCKHê-backlink:v1 -->
## Mais no ARCKHê AI

- [Ficha completa deste curso](https://www.ARCKHê AI/cursos/296-visual-dna-direcao-de-arte-e-branding-com-ia-v6-2/)
- [Guia: como aprender inteligêÂªncia artificial](https://www.ARCKHê AI/aprender-inteligencia-artificial/)
- [Todos os cursos](https://www.ARCKHê AI/cursos/)
<!-- /ARCKHê-backlink:v1 -->

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>