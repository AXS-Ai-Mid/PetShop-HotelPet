# Day Pet Care — Site Institucional

Site institucional da **Day Pet Care** (Maringá - PR), construído no repositório PetShop-HotelPet.

## Sobre a empresa

- **Creche canina & Escola Pet, Banho e Tosa, Estética com Cromoterapia, Hotel para Cães, Atendimento Veterinário e Táxi Dog**
- Av. Gastão Vidigal, 1185 — Zona 8, Maringá - PR · CEP 87050-440
- WhatsApp: (44) 99906-0891 · Instagram: [@daypetcare](https://www.instagram.com/daypetcare)
- Segunda a sexta, 07:30–18:30 · [Google Maps](https://maps.app.goo.gl/AJmpfDc1bVyyyhJe6) — nota **4,8 ★ (105 avaliações)**

## Design system

O visual segue o modelo `DESIGN.md` extraído de malabopetresort:

| Token | Valor |
|---|---|
| Primária | `#E13300` |
| Hero / azuis | `#49A1FB` → `#3C8CE5` (contraste validado) |
| Amarelo destaque | `#FBB949` |
| Canvas / card | `#FFFFFF` |
| Superfície suave | `#F7F7F7` |
| Tinta | `#333333` |
| Tipografia | Nunito (substituta da GothamRounded) + Caveat (substituta do "A bit sketchy") |
| Raios | `5px`, `20px`, `30px`, pill `50px`, `50%` |
| Sombras | `1px 1px 10px rgba(0,0,0,.1)`, `0 0 10px rgba(0,0,0,.063)`, `0 4px 15px rgba(0,0,0,.1)` |

## Estrutura

```
index.html        # Página única (hero, serviços, estrutura, depoimentos, FAQ, CTA, contato)
css/style.css     # Design tokens + estilos (responsivo)
js/main.js        # Menu mobile, acordeão FAQ, scroll spy, reveal
assets/img/       # Imagens dos serviços
```

## Como rodar

```bash
python3 -m http.server 8000
# http://localhost:8000
```

É um site estático — pode ser publicado como está em qualquer hospedagem (Netlify, Vercel, GitHub Pages, servidor tradicional).
