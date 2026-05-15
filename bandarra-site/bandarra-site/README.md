# Bandarra Entertainment — Website

Site institucional do DJ Bandarra, single-page, premium, mobile-first.

## Estrutura

```
bandarra-site/
├── index.html        ← ficheiro único (HTML + CSS + JS)
├── images/           ← todas as imagens (24)
└── README.md         ← este ficheiro
```

## Como pôr ONLINE GRÁTIS (Vercel)

### Opção A — Drag & Drop (mais fácil, 2 minutos)

1. Vá a **https://vercel.com/signup** e crie conta com Google ou GitHub (grátis, sem cartão)
2. No dashboard, clique em **"Add New... → Project"**
3. Clique em **"Deploy a static project"** → faça **drag & drop da pasta inteira** `bandarra-site/`
4. Aguarde 30 segundos. Receberá um URL tipo `bandarra-site-xxx.vercel.app`
5. Em **Settings → Domains** pode mudar para `bandarra.vercel.app` (se livre)

### Opção B — GitHub (recomendada para alterações mensais)

1. Crie conta em https://github.com (grátis)
2. Crie um repositório novo `bandarra-site` (público)
3. Faça upload da pasta (botão "uploading an existing file")
4. Em https://vercel.com/new → **Import** o seu repositório
5. Deploy automático

**Vantagem da Opção B**: para alterar mensalmente, basta editar o `index.html` no GitHub e o Vercel atualiza sozinho.

## Domínio próprio (opcional, ~€10/ano)

Para ter `djbandarra.pt` ou `bandarra.com`:
1. Compre em **Namecheap** ou **Porkbun** (~€10/ano)
2. No Vercel → **Settings → Domains** → adicione o domínio e siga instruções (alterar DNS)
3. Vercel configura HTTPS automático e grátis

## Como ALTERAR mensalmente

Abra o `index.html` em qualquer editor de texto (Notepad, VS Code, ou editor do GitHub).

**Para alterar TEXTOS**:
- Use Ctrl+F para encontrar a frase exacta
- Substitua, guarde, faça upload do ficheiro

**Para alterar IMAGENS**:
- Substitua os ficheiros na pasta `images/` mantendo o nome igual
- Ou adicione novas e altere o `src="images/nome.png"` no HTML

**Para alterar PACKS**:
- Procure no HTML por `<!-- PACKS -->` (linha ~870)
- Edite as listas `<ul class="pack-includes">`

**Para alterar CONTACTOS**:
- Procure por `969 180 049` — substitua em todas as ocorrências
- Procure por `antonio.bandarra@gmail.com` — substitua em todas as ocorrências

## SEO já configurado

- Meta description em português
- Open Graph para partilha em WhatsApp/Facebook/LinkedIn (mostra o banner)
- Tags semânticas (header, main, section, footer)
- Lang="pt-PT"

## Funcionalidades técnicas

- ✓ Responsivo (mobile, tablet, desktop)
- ✓ Galeria com filtros por categoria
- ✓ Lightbox para ampliar imagens (clique em qualquer foto)
- ✓ Botão WhatsApp flutuante
- ✓ Animações de scroll subtis
- ✓ Smooth scroll entre secções
- ✓ Menu mobile (hamburger)
- ✓ Fonts via Google Fonts (Fraunces + Manrope)

## Performance

- Single-file HTML (carrega muito rápido)
- Imagens deveriam ser otimizadas para web (recomendo passar pelo https://tinypng.com/ antes de uploads, para reduzir 70% do tamanho sem perder qualidade)

## Contactos definidos no site

- Telefone: 969 180 049
- Email: antonio.bandarra@gmail.com
- WhatsApp: link directo para `wa.me/351969180049`
- Perfil casamentos.pt: link no footer

---

**Versão**: 1.0 · Maio 2026
