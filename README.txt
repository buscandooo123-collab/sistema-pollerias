# 📱 APP REGRESO PARA VERCEL

## 📦 CONTENIDO:

Esta carpeta contiene SOLO App Regreso para desplegar en Vercel.

```
vercel-solo-regreso/
├── vercel.json
└── public/
    ├── index.html (redirige a /regreso/)
    ├── manifest.json
    ├── sw.js
    └── regreso/
        └── index.html (App Regreso completa)
```

---

## 🚀 CÓMO DESPLEGAR:

### OPCIÓN 1: GitHub Desktop (Recomendado)

1. **Abre GitHub Desktop**
2. **Repository → Show in Explorer**
3. **BORRA TODO** en la carpeta (excepto `.git`)
4. **COPIA TODO** de esta carpeta `vercel-solo-regreso`
5. **Commit:** "Solo App Regreso - App Madre local"
6. **Push origin**
7. Vercel actualizará automáticamente

---

### OPCIÓN 2: Vercel Dashboard

1. Ve a: https://vercel.com
2. Tu proyecto: sistema-pollerias
3. Settings → Git
4. Redeploy

---

## 🔗 URL FINAL:

- https://sistema-pollerias.vercel.app/ → Redirige a /regreso/
- https://sistema-pollerias.vercel.app/regreso/ → App Regreso

**App Madre ya NO estará online** - Solo local en tu computadora

---

## ⚙️ CONFIGURACIÓN VERCEL:

Ya está configurado en vercel.json:
- Root Directory: `public`
- Todo listo para desplegar

---

¡Listo para subir! 🎯
