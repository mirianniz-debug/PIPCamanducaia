Geoportal dos Projetos Integrais de Propriedade (PIP) da microbacia do Rio Camanducaia, em Jaguariúna/SP, no âmbito do Programa Bacias Jaguariúna.

🔗 **Acesse ao vivo:** https://mirianniz-debug.github.io/PIPCamanducaia/

Reúne as 17 propriedades dos Lotes 1 e 2: identificação (lote e nº do PIP), nome da propriedade, área, CAR, APP hídrica e ações previstas (restauração, conservação, cercamento e saneamento rural). Há busca por PIP/nome/CAR e filtros por lote e por ação prevista.

## Dados

- `data/propriedades.json` — limites dos 17 imóveis (polígonos do CAR/SICAR) com os atributos extraídos dos PIPs.
- `data/contexto.json` — limite municipal, sub-bacia e rios do Camanducaia, APP e área de interesse do PIP.

A área exibida é a informada em cada PIP. Quando o polígono do SICAR difere mais de 5% dessa área, a ficha da propriedade mostra um aviso.

## Incorporando o geoportal em outro site (iframe)

Use sempre largura em porcentagem, nunca um valor fixo em pixels — um `width` fixo faz a página que hospeda o geoportal estourar no celular:

```html
<iframe src="URL_DO_GEOPORTAL" style="width:100%; border:0;" height="600" loading="lazy"></iframe>
```

## Licença

Todos os direitos reservados. Ver [LICENSE](LICENSE).