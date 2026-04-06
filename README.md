# Analizador PRE-POST · Escuela de Fortalecimiento

Herramienta de análisis de encuestas PRE y POST que cruza datos por teléfono, calcula promedios por dimensión y genera un Excel completo con trazabilidad.

## Estructura

```
analizador-prepost/
├── public/
│   └── index.html      ← La app completa
├── package.json
├── vercel.json          ← Config de deploy
├── .gitignore
└── README.md
```

## Desarrollo local

```bash
npm run dev
# Abre http://localhost:3000
```

## Deploy en Vercel

### Paso 1 — Subir a GitHub

```bash
cd analizador-prepost
git init
git add .
git commit -m "Initial commit - Analizador PRE-POST"
```

Luego crea un repo en GitHub y conecta:

```bash
git remote add origin https://github.com/TU-USUARIO/analizador-prepost.git
git branch -M main
git push -u origin main
```

### Paso 2 — Deploy en Vercel

1. Ve a [vercel.com](https://vercel.com) e inicia sesión con GitHub
2. Click **"Add New Project"**
3. Importa el repo `analizador-prepost`
4. Vercel detecta el `vercel.json` automáticamente
5. Click **"Deploy"**
6. En ~30 segundos tendrás tu URL: `analizador-prepost.vercel.app`

### Paso 3 — Compartir

Comparte la URL con tu equipo. Cada push a `main` re-deploya automáticamente.
