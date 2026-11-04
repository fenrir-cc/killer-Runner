# 🚗 KILLER RUNNER

> **¡El objetivo es atropellar runners!**  
> Un juego arcade 2D en HTML5 Canvas con vehículos, hordas de corredores, potenciadores y música festiva.

---

## 🎮 Cómo Jugar

1. Abre `index.html` en cualquier navegador web moderno (Chrome, Edge, Firefox, Safari).
2. Haz clic en **Iniciar Juego ▶**.
3. Conduce esquivando o embistiendo a los runners para acumular la máxima puntuación.

### 🕹️ Controles

| Tecla | Acción |
| :--- | :--- |
| **Flechas** o **WASD** | Conducir vehículo (Arriba, Abajo, Izquierda, Derecha) |
| **P** o **Escape** | Pausar / Reanudar partida |
| **M** | Activar / Silenciar audio |

---

## ⚡ Mecánicas y Enemigos

* **Runner Man:** Corredor estándar (10 pts).
* **Runner Woman:** Corredora ágil y veloz (15 pts).
* **Wild Runner:** Corredor salvaje de gran velocidad (25 pts).
* **Modo Frenesí:** Recoge el *Power-Up* de aura dorada para triplicar los puntos (`x3`) y aumentar la velocidad durante 6 segundos.
* **Vidas:** Cuentas con 3 spoilers/vidas. Si dejas escapar a los runners por la izquierda, perderás una vida.
* **Top 10 Highscores:** Guarda tu récord localmente en el navegador.

---

## 📁 Estructura del Proyecto

```
killer-runner/
├── index.html          # Código maestro del juego (HTML5, Canvas y CSS)
├── .gitignore          # Exclusiones de Git
├── README.md           # Documentación
└── assets/
    ├── audio/          # Efectos de sonido y tema musical
    ├── images/         # Fondos e imagen de portada
    └── sprites/
        ├── car/        # Sprites del auto (conducción, choque, destruido)
        ├── powerups/   # Items y auras de poder
        └── runners/    # Sprites animados de los 3 tipos de runners
```

---

## 🚀 Despliegue en GitHub Pages

1. Sube este repositorio a tu cuenta de GitHub.
2. Ve a **Settings** > **Pages**.
3. En **Source**, selecciona `Deploy from a branch` y elige la rama `main` en la carpeta `/ (root)`.
4. ¡Tu juego estará disponible online inmediatamente para compartir con amigos!
