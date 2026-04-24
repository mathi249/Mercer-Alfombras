# Mercer — Gestión de Inventario

App web para gestión de inventario de alfombras premium.

## Cómo subir a Vercel (sin código, 2 minutos)

### Opción A — Drag & Drop (más fácil, sin cuenta de GitHub)
1. Ir a https://vercel.com/new
2. Iniciar sesión o crear cuenta gratuita
3. En la pantalla de "Import", bajar hasta "Or deploy without a Git repository"
4. Clic en **"Deploy with a template"** → **"Browse templates"** no, mejor:
   - Ir directo a https://vercel.com/new
   - Hacer clic en el link "Or drag & drop a folder"
   - Arrastrar esta carpeta `mercer-vercel` completa
5. Esperar ~30 segundos → Vercel da la URL lista

### Opción B — GitHub (recomendado para poder actualizar fácil)
1. Crear cuenta en https://github.com (si no tenés)
2. Crear repositorio nuevo → subir esta carpeta
3. Ir a https://vercel.com/new → importar el repo
4. Deploy → URL lista en segundos

## Estructura del proyecto
```
mercer-vercel/
├── index.html    ← La app completa (todo en un archivo)
└── vercel.json   ← Config para Vercel
```

## Características
- Inventario con foto, código, origen, material, medidas
- Cálculo automático de margen por pieza
- Historial de ventas con ganancia acumulada
- Exportación a CSV para Excel/Sheets
- Funciona en celular y desktop
- Sin servidor, sin base de datos (datos en el navegador)

## Contacto
mercer.ba | mercerba.com.ar | @mercer.ba
