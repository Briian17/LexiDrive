# LexiDrive

Videojuego educativo 2D desarrollado en **Unity con C#** para **Windows**.

## Descripción
**LexiDrive** es un juego donde controlas un carro mientras respondes preguntas en inglés.  
Cada respuesta correcta aumenta la gasolina del vehículo. Cada respuesta incorrecta aumenta el daño.  
El juego termina si se acaba la gasolina o si el daño llega al 100%.

## Requisitos
- Windows 10 o superior
- Unity 2022.3 o superior (para abrir el proyecto fuente)

## Instalación y Ejecución

1. Descarga el build desde la carpeta `Builds/Windows/`
2. Ejecuta el archivo `LexiDrive.exe`
3. ¡Comienza a jugar y mejorar tu inglés!

## Controles
- **WASD** o **Flechas** → Mover el carro
- **Mouse** o **Espacio** → Seleccionar respuestas

## Cómo abrir el proyecto en Unity
1. Clona este repositorio
2. Abre Unity Hub → "Add project from disk"
3. Selecciona la carpeta del proyecto
4. Abre la escena principal (`MainMenu` o `Game`)

## Estructura del Proyecto
- `Assets/Scripts/` → Scripts en C#
- `Assets/Scenes/` → Escenas del juego
- `Assets/Prefabs/` → Prefabs
- `Assets/Resources/` → Preguntas y datos locales

## Ramas del Repositorio
- `main` → Versión estable final
- `develop` → Rama de integración
- `feature/carro-fisica`
- `feature/sistema-preguntas`
- `feature/gasolina-dano`
- `feature/guardado-local`
- `feature/ui-hud`
- `feature/audio`
