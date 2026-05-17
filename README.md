# sk-code-editor-v4-web-1-android — App Desktop

Aplicativo gerado pelo APK Builder para Windows, Mac e Linux.

## Como compilar

### Usando GitHub Actions (automático)
1. Suba este repositório no GitHub
2. O workflow `.github/workflows/build-desktop.yml` compila automaticamente
3. Baixe os executáveis na aba **Actions → Artifacts**

### Manualmente
```bash
npm install
npm run build
```

Os arquivos estarão em `dist/`:
- **Windows**: `sk-code-editor-v4-web-1-android-Setup-1.0.8.exe`
- **Mac**: `sk-code-editor-v4-web-1-android-1.0.8.dmg`
- **Linux**: `sk-code-editor-v4-web-1-android-1.0.8.AppImage`

## Requisitos
- Node.js 18+
- npm

## Gerado por
[APK Builder](https://replit.com) — Maikon Caldeira
