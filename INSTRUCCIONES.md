# 🚀 Instrucciones para Usar el Template

## Primeros Pasos

### 1. Instalar Dependencias

```bash
npm install
```

### 2. Probar en el Navegador

```bash
npm run dev
```

### 3. Personalizar la App

Edita estos archivos para personalizar tu app:

- **`src/App.jsx`** - Componente principal de tu app
- **`src/index.css`** - Estilos globales
- **`capacitor.config.json`** - Configuración de Capacitor (nombre, appId)
- **`index.html`** - HTML principal

### 4. Configurar GitHub Actions

1. Crea un repositorio en GitHub: https://github.com/new
2. **NO** inicialices con README, .gitignore, etc.
3. Inicializa git y sube tu código:

```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/TU_USUARIO/TU_REPO.git
git push -u origin main
```

4. Ve a la pestaña **"Actions"** en GitHub
5. Espera 3-5 minutos a que compile
6. Descarga el APK desde Artifacts
7. Instálalo en tu dispositivo Android

## Personalización

### Cambiar Colores

Edita `tailwind.config.js` o usa clases de Tailwind directamente.

### Agregar Componentes

Crea archivos en `src/` y importa donde los necesites.

### Cambiar Nombre de la App

Edita `capacitor.config.json`:

```json
{
  "appId": "com.tudominio.tuapp",
  "appName": "Tu App"
}
```

### Agregar Dependencias

```bash
npm install nombre-del-paquete
```

Luego úsalo normalmente en tu código React.

## Compilar Localmente (Opcional)

Si quieres probar la compilación en tu máquina:

1. Instala [Android Studio](https://developer.android.com/studio)
2. Configura ANDROID_HOME
3. Ejecuta: `npm run android:run`

## Siguientes Pasos

- ✨ Agrega más componentes
- 🎨 Personaliza los estilos con Tailwind
- 📱 Agrega plugins de Capacitor si necesitas funcionalidad nativa
- 🚀 ¡Publica tu app en Google Play!

---

**¡Divierte construyendo tu app! 🎉**

