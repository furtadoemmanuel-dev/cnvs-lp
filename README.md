# CNVS by Belgotex — preview da landing page

Build estático da LP da campanha CNVS, publicado apenas para **aprovação do cliente**.

- Página: https://furtadoemmanuel-dev.github.io/cnvs-lp/
- `noindex, nofollow`: não é indexada por buscadores.
- O formulário está em **modo demonstração**: percorre o fluxo até a página de
  obrigado, mas não grava lead (o backend Base44 ainda não está publicado).

Gerado a partir de `campanhas_ADS/lp/cnvs-design-flow` com
`VITE_DEMO_MODE=1 vite build --base /cnvs-lp/`.
