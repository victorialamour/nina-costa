# Nina Costa Brides

Protótipo de landing page (HTML estático, sem build) para Nina Costa Brides, maquiagem e penteado para noivas em São Paulo, interior e destination weddings. Tem versão em português e em inglês (bandeiras no canto superior direito).

## Como ver
Abra `index.html` no navegador, ou sirva a pasta:

```bash
npx serve .
```

## Antes de publicar
Este repositório é uma **prévia privada**. Não publique antes de resolver:

- [ ] Autorização da Nina, das noivas, da equipe e dos fotógrafos para o uso das fotos, do vídeo e dos depoimentos.
- [ ] Trocar o WhatsApp provisório (`WHATSAPP_NUMERO`, no bloco CONFIGURAÇÃO no fim do `index.html`).
- [ ] Trocar o domínio (`canonical`, `og:url`, `og:image`) e criar a imagem de compartilhamento `og-image.jpg`.
- [ ] Procurar por `CONFIRMAR` no `index.html` (trechos em amarelo no site).
- [ ] Foto de "Mãe e madrinhas" (hoje provisória).
- [ ] Menu de navegação fixo.

## Estrutura
- `index.html`: página inteira (CSS e JS embutidos). Os textos em inglês estão no dicionário `EN`, no fim do arquivo.
- `fotos/`: imagens usadas pelo site.
- `video/hero.mp4`: vídeo do topo.
