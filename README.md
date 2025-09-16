# Binna-web
Maqueta de webs de Binna

## Descripción
Este repositorio contiene una página web moderna y responsiva para Binna. La web está diseñada para ser hospedada en GitHub Pages y cuenta con una interfaz atractiva y funcional.

## Características
- 🎨 Diseño moderno y responsivo
- 📱 Compatible con dispositivos móviles
- ⚡ Animaciones suaves y interactivas
- 📝 Formulario de contacto funcional
- 🎯 Navegación fluida entre secciones

## Estructura del Proyecto
```
Binna-web/
├── index.html      # Página principal
├── styles.css      # Estilos CSS
├── script.js       # JavaScript interactivo
└── README.md       # Este archivo
```

## Configuración de GitHub Pages

Para habilitar GitHub Pages y ver tu sitio web en línea, sigue estos pasos:

1. **Ir a la configuración del repositorio:**
   - Ve a tu repositorio en GitHub
   - Haz clic en la pestaña "Settings"

2. **Configurar GitHub Pages:**
   - En el menú lateral, busca "Pages"
   - En "Source", selecciona "Deploy from a branch"
   - Selecciona "main" como branch
   - Selecciona "/ (root)" como folder
   - Haz clic en "Save"

3. **Acceder a tu sitio:**
   - Después de unos minutos, tu sitio estará disponible en:
   - `https://[tu-usuario].github.io/Binna-web/`

## Desarrollo Local

Para trabajar con el proyecto localmente:

1. Clona el repositorio:
```bash
git clone https://github.com/sepucio/Binna-web.git
```

2. Abre `index.html` en tu navegador o usa un servidor local:
```bash
# Con Python 3
python -m http.server 8000

# Con Node.js (si tienes http-server instalado)
npx http-server
```

## Personalización

### Colores
Los colores principales se definen en `styles.css`:
- Azul principal: `#007bff`
- Naranja de acento: `#ff6b35`
- Gris de texto: `#333`

### Contenido
Edita el archivo `index.html` para cambiar:
- Textos y títulos
- Información de servicios
- Datos de contacto

### Estilos
Modifica `styles.css` para personalizar:
- Colores y tipografías
- Espaciados y layouts
- Efectos y animaciones

## Tecnologías Utilizadas
- HTML5
- CSS3 (Grid, Flexbox, Animations)
- JavaScript ES6+
- Responsive Design

## Licencia
Este proyecto está bajo la Licencia MIT.
