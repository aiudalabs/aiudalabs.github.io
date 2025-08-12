# ConectaCuba - Deep Links Website

🇨🇺🇵🇦 Sitio web para manejar los App Links/Universal Links de ConectaCuba

## 🔗 URLs Soportadas

- `https://aiudalabs.github.io/service/[ID]` - Abre un servicio específico
- `https://aiudalabs.github.io/category/[ID]` - Abre una categoría específica  
- `https://aiudalabs.github.io/user/[ID]` - Abre un perfil de usuario
- `https://aiudalabs.github.io/` - Página principal

## 📱 Funcionamiento

1. **Con la app instalada**: Los enlaces abren directamente la app ConectaCuba
2. **Sin la app**: Muestra la página web con opción de descarga
3. **Auto-detección**: Redirige automáticamente en dispositivos móviles

## 🛠️ Archivos de Verificación

- `/.well-known/assetlinks.json` - Verificación para Android App Links
- `/.well-known/apple-app-site-association` - Verificación para iOS Universal Links

## 🚀 Configuración

### Android App Links
- **Package Name**: `com.aiudalabs.conecta_cuba`
- **SHA256 Fingerprint**: `F9:E3:69:A8:C1:FF:12:07:EA:95:7E:05:90:6B:EB:BA:FA:52:3F:21:70:39:50:A6:E8:35:CD:0C:D4:66:94:F5`

### iOS Universal Links
- **Bundle ID**: `com.aiudalabs.conecta-cuba`
- **Team ID**: Pendiente de configurar

## ✅ Verificación

Para verificar que los archivos están accesibles:

```bash
curl https://aiudalabs.github.io/.well-known/assetlinks.json
curl https://aiudalabs.github.io/.well-known/apple-app-site-association
```

## 🔧 Desarrollo

Este sitio está diseñado para:
- Funcionar con GitHub Pages automáticamente
- Manejar rutas dinámicas con 404.html
- Detectar dispositivos móviles
- Redirigir automáticamente a la app

---

**ConectaCuba** - Conectando a la comunidad cubana en Panamá 🤝