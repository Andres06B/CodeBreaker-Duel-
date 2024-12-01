# 🎮 **My Game Web**  

Desarrollo de un juego de rol web con temática retro para disfrutar con amigos y familiares.  
Un jugador define una **clave secreta** o **combinación de cables** y el tiempo límite, mientras el otro jugador debe usar las pistas para **desactivar la bomba** y ganar. ¡Pon a prueba tus habilidades estratégicas y de deducción!  

---

## 🛠️ **Tecnologías Utilizadas**  

### **Frontend** 🌐  
- **Angular 18**: Framework para la construcción de la interfaz de usuario.  
- **HTML5 / SCSS**: Estructura y estilos personalizados para una experiencia visual retro.  
- **TypeScript**: Lenguaje para una mejor gestión del código y tipado fuerte.  

### **Backend** ⚙️  
- **Node.js**: Plataforma para el manejo de la lógica del juego y comunicación.  
- **Express.js**: Framework para la creación del API.  
- **WebSockets**: Para la interacción en tiempo real entre jugadores.  

### **Base de Datos** 🗄️  
- **MongoDB** o **MySQL**: Para almacenamiento de partidas, puntuaciones y configuraciones (según preferencia).  

---

## 🎮 **Modos de Juego**  

1. **🔐 Modo Clave:**  
   - Jugador 1 define la clave y pistas.  
   - Jugador 2 debe descifrar la clave antes de que el tiempo se acabe.  

2. **💣 Modo Cables:**  
   - Jugador 1 elige una combinación de cables a cortar.  
   - Jugador 2 debe cortar los cables en el orden correcto antes de que explote la bomba.  

---

## 🕹️ **Flujo del Juego**  

1. **Pantalla Principal:**  
   - Título del juego con estilo retro.  
   - Opciones: **Modo Clave** y **Modo Cables**.  
   - Acceso a configuración de música y efectos visuales.  

2. **Fase de Preparación:**  
   - Jugador 1 ingresa la clave o selecciona cables.  
   - Configuración del tiempo límite.  

3. **Fase de Juego:**  
   - Jugador 2 intenta desactivar la bomba usando las pistas.  
   - Retroalimentación visual y sonora durante el juego.  

4. **Resultado:**  
   - **🎉 Pantalla de Victoria** si el jugador desactiva la bomba.  
   - **💥 Pantalla de Derrota** si el tiempo se acaba.  
   - Opciones: **Reiniciar** o **Volver al Menú Principal**.  

---

## ✨ **Características Destacadas**  

- 🎨 **Estilo Visual Retro**: Experiencia inmersiva inspirada en videojuegos clásicos.  
- ⏱️ **Tiempo Límite Dinámico**: Configurable por el jugador para incrementar la tensión.  
- 🌍 **Juego en Tiempo Real**: Comunicación entre jugadores mediante WebSockets.  
- 🏆 **Sistema de Puntuaciones**: Mide tu rendimiento y compite con amigos.  
- 🔊 **Efectos Sonoros**: Música y sonidos dinámicos para aumentar la emoción.  

---

## 🚧 **Juego en Proceso**  
Actualmente, **My Game Web** se encuentra en desarrollo activo. Las futuras actualizaciones incluirán mejoras en la jugabilidad, nuevas funcionalidades y más contenido para ofrecer una experiencia más inmersiva.  

---

¿Estás listo para desactivar la bomba y demostrar tus habilidades? ¡Prepárate para jugar! 😎
