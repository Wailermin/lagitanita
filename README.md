# La Gitana – Demo (Sitio + Menú editable)

## Rutas
- `/` Landing para vender el producto
- `/menu/` Menú público (lee datos desde `menu/menu.json`)
- `/admin/` Panel para editar el menú (Decap CMS / Netlify Identity)

## Cómo activarlo en Netlify
1. Deploy desde GitHub
2. Site settings → **Identity** → Enable
3. Identity → **Services** → Enable **Git Gateway**
4. Invita un usuario (email) para que pueda entrar a `/admin`

## Editar el menú
Entra a `/admin`, edita y publica. Los cambios actualizan `menu/menu.json`.
