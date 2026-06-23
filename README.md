# Finesse Abrantes — Crystal Atelier

Site institucional da **Finesse Abrantes**, empresa de taças de cristal premium.

Design sofisticado nas cores **preto, dourado, prata e branco**, inspirado em
grandes marcas de cristal como [Zwiesel Glas](https://www.zwiesel-glas.com/) e
[Riedel](https://www.riedel.com/en), mantendo a identidade da marca
([@finesseabrantes](https://instagram.com/finesseabrantes)).

## Estrutura

```
index.html        Página principal (single-page)
css/style.css     Estilos, paleta e animações
js/main.js        Loader, scroll reveal, contadores, menu, formulário
assets/           Favicon
```

## Como visualizar

Basta abrir `index.html` no navegador. Para um servidor local:

```bash
python3 -m http.server 8000
# acesse http://localhost:8000
```

## Seções

- **Hero** — apresentação com taça de cristal em SVG e brilho dourado
- **Atelier** — história da marca com contadores animados
- **Coleções** — Noir, Lumière, Aurum e Onyx (cards interativos)
- **Artesania** — diferenciais do cristal premium
- **Galeria** — mosaico com chamada para o Instagram
- **Contato** — formulário de encomendas exclusivas

## Características

- 100% responsivo (desktop, tablet, mobile)
- Ilustrações em SVG (sem dependência de imagens externas)
- Tipografia Cormorant Garamond + Jost (Google Fonts)
- Animações sutis com respeito a `prefers-reduced-motion`
