# 🔴 Pokédex - Gotta Catch 'Em All! ⚡

<div align="center">
  
[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=FF0000&center=true&vCenter=true&width=435&lines=Explora+el+mundo+Pok%C3%A9mon;Descubre+nuevas+especies;Gotta+Catch+%27Em+All!)](https://git.io/typing-svg)

![Pokédex Demo](https://img.shields.io/badge/Demo-Live-brightgreen)
![GitHub stars](https://img.shields.io/github/stars/Arkanabytes/Pokedex?style=social)
![GitHub forks](https://img.shields.io/github/forks/Arkanabytes/Pokedex?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/Arkanabytes/Pokedex?style=social)

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![API](https://img.shields.io/badge/API-PokéAPI-red?style=for-the-badge)

</div>

## 🌟 Descripción

Una **Pokédex interactiva** que te permite explorar el fascinante mundo de los Pokémon. Desarrollada con tecnologías web modernas y conectada a la [PokéAPI](https://pokeapi.co/), esta aplicación ofrece una experiencia inmersiva para descubrir información detallada sobre tus Pokémon favoritos.

### 🎯 ¿Qué es una Pokédex?
Una Pokédex es un dispositivo digital que cataloga y proporciona información sobre las diferentes especies de Pokémon. ¡Nuestra versión web te permite llevar toda esta información contigo!

## ✨ Características Principales

- 🔍 **Búsqueda Avanzada**: Encuentra Pokémon por nombre o número
- 📱 **Diseño Responsivo**: Perfecto en desktop, tablet y móvil  
- 🎨 **Interfaz Atractiva**: Diseño inspirado en la Pokédex original
- ⚡ **Carga Rápida**: Optimizada para mejor rendimiento
- 🌈 **Tipos de Pokémon**: Visualización clara de tipos y colores
- 📊 **Stats Detalladas**: HP, Ataque, Defensa, Velocidad y más
- 🔄 **Navegación Fluida**: Transiciones suaves entre Pokémon
- 💾 **Favoritos**: Guarda tus Pokémon favoritos (localStorage)

## 🚀 Demo en Vivo

🌐 **[Ver Pokédex en Acción](https://arkanabytes.github.io/Pokedex/)**

## 📸 Capturas de Pantalla

<div align="center">
  
### 🏠 Página Principal
![Página Principal](https://via.placeholder.com/800x400/1a1a2e/ffffff?text=P%C3%A1gina+Principal+de+la+Pok%C3%A9dex)

### 🔍 Búsqueda de Pokémon
![Búsqueda](https://via.placeholder.com/800x400/16213e/ffffff?text=B%C3%BAsqueda+de+Pok%C3%A9mon)

### 📋 Detalles del Pokémon
![Detalles](https://via.placeholder.com/800x400/0f3460/ffffff?text=Detalles+del+Pok%C3%A9mon)

</div>

## 🛠️ Tecnologías Utilizadas

| Tecnología | Propósito |
|------------|-----------|
| **HTML5** | Estructura semántica |
| **CSS3** | Estilos y animaciones |
| **JavaScript (ES6+)** | Lógica de la aplicación |
| **PokéAPI** | Datos de Pokémon |
| **Fetch API** | Peticiones HTTP |
| **LocalStorage** | Persistencia de favoritos |
| **CSS Grid/Flexbox** | Layout responsivo |

## 📱 Responsividad

- 📺 **Desktop**: 1200px+
- 💻 **Laptop**: 768px - 1199px  
- 📱 **Tablet**: 481px - 767px
- 📱 **Mobile**: 320px - 480px

## 🚀 Instalación y Uso

### Opción 1: Clonar Repositorio
```bash
# Clonar el repositorio
git clone https://github.com/Arkanabytes/Pokedex.git

# Entrar al directorio
cd Pokedex

# Abrir index.html en tu navegador
# O usar un servidor local
python -m http.server 8000
# o
npx serve .
```

### Opción 2: Descargar ZIP
1. Haz clic en **Code** → **Download ZIP**
2. Extrae el archivo
3. Abre `index.html` en tu navegador favorito

### 🌐 Requisitos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Conexión a internet (para cargar datos de la API)

## 📁 Estructura del Proyecto

```
Pokedex/
├── 📄 index.html          # Página principal
├── 🎨 css/
│   ├── style.css          # Estilos principales  
│   ├── responsive.css     # Media queries
│   └── animations.css     # Animaciones
├── 🚀 js/
│   ├── main.js           # Lógica principal
│   ├── api.js            # Conexión a PokéAPI
│   ├── pokemon.js        # Clase Pokemon
│   └── utils.js          # Funciones auxiliares
├── 🖼️ assets/
│   ├── images/           # Imágenes del proyecto
│   ├── icons/            # Iconos de tipos
│   └── sounds/           # Efectos de sonido (opcional)
├── 📄 README.md          # Este archivo
└── 📄 LICENSE            # Licencia MIT
```

## 🎮 Funcionalidades Detalladas

### 🔍 Sistema de Búsqueda
- Búsqueda por nombre (ej: "Pikachu")
- Búsqueda por número de Pokédex (ej: "25")
- Autocompletado inteligente
- Manejo de errores elegante

### 📊 Información Mostrada
- **Básica**: Nombre, número, imagen
- **Tipos**: Con colores característicos  
- **Stats**: HP, Ataque, Defensa, etc.
- **Evoluciones**: Cadena evolutiva
- **Movimientos**: Lista de ataques
- **Habilidades**: Especiales y ocultas

### 💾 Funciones Adicionales
- ❤️ Sistema de favoritos
- 🔄 Navegación entre Pokémon
- 🌈 Cambio de tema (claro/oscuro)
- 📱 Instalable como PWA (próximamente)

## 🐛 Problemas Conocidos y Soluciones

| Problema | Solución |
|----------|----------|
| Carga lenta | Implementamos lazy loading |
| Error de API | Sistema de reintentos automáticos |
| Imágenes rotas | Fallback a sprites alternativos |

## 🤝 Contribuir

¡Las contribuciones son bienvenidas! Sigue estos pasos:

1. 🍴 Fork el proyecto
2. 🌿 Crea tu rama (`git checkout -b feature/AmazingFeature`)
3. 💾 Commit tus cambios (`git commit -m 'Add: nueva funcionalidad increíble'`)
4. 📤 Push a la rama (`git push origin feature/AmazingFeature`)
5. 🔃 Abre un Pull Request

### 🎯 Ideas para Contribuir
- 🌍 Traducciones a otros idiomas
- 🎨 Nuevos temas visuales
- 📱 Mejoras de responsividad
- ⚡ Optimizaciones de rendimiento
- 🔊 Efectos de sonido
- 🎮 Mini-juegos Pokémon

## 📈 Estadísticas del Proyecto

![GitHub commits](https://img.shields.io/github/commit-activity/m/Arkanabytes/Pokedex)
![GitHub last commit](https://img.shields.io/github/last-commit/Arkanabytes/Pokedex)
![GitHub repo size](https://img.shields.io/github/repo-size/Arkanabytes/Pokedex)
![GitHub code size](https://img.shields.io/github/languages/code-size/Arkanabytes/Pokedex)

## 🏆 Reconocimientos

- 🙏 **PokéAPI** - Por proporcionar datos completos y gratuitos
- 🎨 **The Pokémon Company** - Por crear este universo increíble  
- 👥 **Comunidad de desarrolladores** - Por el feedback y sugerencias
- 🌟 **Contributors** - Por hacer este proyecto mejor cada día

## 📞 Contacto

👨‍💻 **Desarrollador**: Arkanabytes

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/tu-perfil)
[![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?style=for-the-badge&logo=Twitter&logoColor=white)](https://twitter.com/tu-usuario)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tu-email@gmail.com)

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ve el archivo [LICENSE](LICENSE) para más detalles.

## 🌟 Roadmap

### 📅 Próximas Versiones

#### v2.0 - The Great Update
- [ ] 🎮 Sistema de batalla básico
- [ ] 🏆 Logros y medallas
- [ ] 📱 Progressive Web App (PWA)
- [ ] 🔊 Efectos de sonido
- [ ] 🌍 Soporte multiidioma

#### v2.1 - Enhanced Experience  
- [ ] 🎯 Quizz Pokémon
- [ ] 📊 Comparador de Pokémon
- [ ] 🎨 Más temas personalizables
- [ ] 💾 Sincronización en la nube
- [ ] 📱 App móvil nativa

## 💝 Apoya el Proyecto

Si te gusta este proyecto, puedes apoyarlo:

- ⭐ Dándole una estrella en GitHub
- 🐛 Reportando bugs
- 💡 Sugiriendo nuevas características
- 🤝 Contribuyendo con código
- ☕ [Invitándome un café](https://buymeacoffee.com/arkanabytes)

---

<div align="center">

**¡Gotta Code 'Em All!** 🔥⚡🌊🌿🔮👻🥊🌟

*Hecho con ❤️ y mucho café por [Arkanabytes](https://github.com/Arkanabytes)*

</div>
