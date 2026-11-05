# Proyecto-Libre-Robot-Arena-Steel
# 🤖 Robot Arena: Steel Clash

> Videojuego de combate 2D lateral en el que controlas a un robot de batalla y te enfrentas a robots controlados por IA en arenas interactivas.

![Género](https://img.shields.io/badge/G%C3%A9nero-Acci%C3%B3n%20%2F%20Shooter%202D-red)
![Perspectiva](https://img.shields.io/badge/Perspectiva-2D%20lateral-informational)
![Plataforma](https://img.shields.io/badge/Plataforma-PC-blue)
![Motor](https://img.shields.io/badge/Motor-Unity%20%2F%20Godot-black)
![Estado](https://img.shields.io/badge/Estado-Dise%C3%B1o-orange)

---

## 📖 Descripción

**Robot Arena: Steel Clash** es un videojuego de combate 2D en el que el jugador controla un robot de batalla dentro de distintas arenas. El objetivo es derrotar a los robots enemigos combinando **movimiento, ataques, defensa, armas y power-ups**. Cada arena tiene características propias que obligan a adaptar la estrategia.

## 📜 Historia

En un futuro donde los conflictos entre corporaciones se resuelven mediante combates de robots, se crea el torneo **Steel Clash**. Los mejores robots de distintos fabricantes se enfrentan en arenas diseñadas para poner a prueba sus capacidades. El jugador controla a un robot experimental que debe avanzar por las arenas y derrotar a rivales controlados por IA para convertirse en el **campeón del torneo**.

## 📋 Ficha técnica

| Elemento | Descripción |
|---|---|
| Nombre | Robot Arena: Steel Clash |
| Género | Acción / Combate / Shooter 2D |
| Perspectiva | 2D lateral |
| Jugadores | 1 jugador |
| Modo principal | Combate contra IA |
| Plataforma | PC |
| Motor recomendado | Unity / Godot |
| Público objetivo | Adolescentes y jóvenes |
| Duración de partida | 5–10 minutos |
| Clasificación | Acción / Ciencia ficción |

## 🎯 Objetivo del jugador

**Derrotar al robot enemigo antes de que se agote tu vida.** Para lograrlo debes moverte por la arena, esquivar ataques, usar distintas armas, activar el escudo, recoger power-ups, aprovechar el escenario y adaptarte al comportamiento de la IA.

## 🕹️ Controles (PC)

| Acción | Tecla |
|---|---|
| Mover izquierda | `A` |
| Mover derecha | `D` |
| Saltar | `W` / `Espacio` |
| Dash | `Shift` |
| Disparar | Click izquierdo |
| Cambiar arma | `Q` / `E` |
| Escudo | Click derecho |
| Habilidad especial | `F` |
| Pausa | `Esc` |

## ⚙️ Mecánicas principales

### Movimiento
- **Horizontal:** izquierda y derecha.
- **Salto:** esquivar proyectiles, alcanzar plataformas y atacar desde posiciones elevadas.
- **Dash:** movimiento rápido en una dirección, con tiempo de reutilización.
- **Caída rápida:** en el aire, permite evitar ataques, llegar al suelo rápidamente y atacar desde arriba.

### Sistema de combate
Combates rápidos donde cada robot tiene **vida**, **energía**, **escudo**, **arma equipada** y **habilidad especial**.

- ❤️ **Vida:** resistencia física del robot (ej. 100/100). Al llegar a 0, el robot es derrotado.
- ⚡ **Energía:** necesaria para usar ciertas habilidades; se recupera lentamente con el tiempo.

### 🔫 Armas

| Arma | Daño | Alcance | Notas |
|---|---|---|---|
| **Pistola de plasma** | Medio | Medio | Básica y equilibrada; velocidad alta, consumo de energía bajo. Ideal para principiantes |
| **Escopeta de energía** | Alto | Corto | Dispara varios proyectiles; velocidad de disparo baja, consumo medio. Efectiva a corta distancia |
| **Lanzacohetes** | Muy alto | Alto | Misiles explosivos que afectan al enemigo y elementos cercanos; velocidad baja, munición limitada |
| **Rifle láser** | Alto | Muy alto | Rayo de alta velocidad y alta precisión; consumo de energía alto |
| **Cañón eléctrico** | Medio | Medio | Ralentiza temporalmente al enemigo; consumo de energía alto |

### 🛡️ Escudo
Escudo energético que **absorbe parte del daño** durante un tiempo limitado (100% → 75% → 50% → 25% → 0%). Al llegar a 0% se desactiva y necesita tiempo para regenerarse. Además, consume energía, no puede usarse de forma permanente y ciertos ataques pueden sobrecargarlo, por lo que hay que decidir cuándo usarlo.

### ✨ Power-ups

| Power-up | Efecto |
|---|---|
| 🔋 Recarga de energía | +30 energía |
| ❤️ Reparación | +25 HP |
| ⚡ Sobrecarga | Aumenta la velocidad de ataque (8 s) |
| 🛡️ Escudo mejorado | Recibes menos daño (5 s) |
| 💥 Daño aumentado | +50% de daño |
| 🚀 Velocidad | +30% de velocidad de movimiento |

## 🧠 Inteligencia artificial

| Tipo | Comportamiento |
|---|---|
| **Básica** | Detecta al jugador, se acerca, ataca y retrocede cuando recibe mucho daño |
| **Ofensiva** | Agresiva: se acerca rápido, ataca constantemente a corto alcance y persigue al jugador |
| **Defensiva** | Mantiene distancia, usa armas de largo alcance y escudo, y retrocede si te acercas |
| **Táctica** | El enemigo más avanzado: cambia de arma, esquiva, usa power-ups y escudo, busca mejores posiciones y se adapta a tu estilo |

## 🏟️ Arenas

| # | Arena | Elementos | Mecánica especial |
|---|---|---|---|
| 1 | **Fábrica abandonada** | Plataformas, cajas, tuberías, barreras metálicas | Algunas plataformas pueden destruirse |
| 2 | **Ciudad futurista** | Edificios, plataformas flotantes, pantallas holográficas, obstáculos | Algunas plataformas se mueven |
| 3 | **Base lunar** | Baja gravedad, plataformas, cráteres, estructuras metálicas | Saltos más altos por la baja gravedad |
| 4 | **Volcán industrial** | Lava, plataformas metálicas, ventiladores, zonas peligrosas | Algunas áreas causan daño |
| 5 | **Arena de combate** | Plataformas móviles, obstáculos, coberturas, power-ups especiales | Escenario final del torneo |

**Elementos interactivos adicionales:** plataformas móviles y destruibles, barriles explosivos, puertas, trampas, zonas de daño y coberturas.

## 🦾 Robots jugables

| Robot | Tipo | Ventajas | Desventajas |
|---|---|---|---|
| **Titan** | Pesado | Mucha vida, gran daño, escudo fuerte | Movimiento lento |
| **Phantom** | Rápido | Gran velocidad, dash mejorado, excelente movilidad | Poca vida |
| **Guardian** | Defensivo | Escudo muy resistente, alta defensa | Poco daño |
| **Striker** | Equilibrado | Buena velocidad, daño y escudo | No destaca en nada específico |

## 🎮 Modos de juego

- **Campaña:** supera las distintas arenas y enemigos.
- **Combate rápido:** elige robot, arena, arma y dificultad.
- **Supervivencia:** derrota a la mayor cantidad posible de enemigos, cada vez más difíciles.

## 📊 Dificultad

| Nivel | Comportamiento de la IA |
|---|---|
| **Fácil** | Ataca menos, menor precisión, usa pocas habilidades |
| **Normal** | Ataca regularmente, usa escudos y busca power-ups |
| **Difícil** | Esquiva, cambia de estrategia, usa power-ups y aprovecha las características de la arena |

## 🏆 Victoria, derrota y progresión

- **Victoria:** la vida del enemigo llega a 0. Recompensas: puntos, experiencia, monedas, nuevas armas y nuevos robots.
- **Derrota:** tu vida llega a 0. También puede haber límite de tiempo (ej. 03:00); si termina, gana quien tenga más vida.
- **Mejoras:** tras cada combate se pueden desbloquear mejoras de vida, energía, escudo, daño, velocidad y precisión.

## 🖥️ Interfaz de usuario

Durante el combate se muestra: vida, escudo, energía, arma equipada, cooldowns y power-ups activos.

## 🎥 Cámara

Cámara 2D lateral que sigue al jugador y se aleja ligeramente cuando los robots están muy separados, para mantener a ambos visibles.

## 🎨 Dirección artística y sonido

- **Estilo:** ciencia ficción + industrial + futurista, en **2D con sprites**, animaciones y efectos visuales.
- **Visual:** robots con siluetas distintas, armas luminosas, partículas, explosiones, rayos láser, escudos energéticos y ambientes tecnológicos.
- **Efectos de sonido:** disparos, explosiones, golpes metálicos, activación del escudo, dash, power-ups y destrucción del robot.
- **Música:** una pista distinta por arena, que aumenta de intensidad en los momentos de combate.

## 🔁 Bucle principal de juego

```
Entrar a arena → Explorar → Combatir → Recoger power-ups → Derrotar enemigo
      → Obtener recompensa → Mejorar robot → Entrar a nueva arena
```

## ⭐ Diferenciador

El combate no depende únicamente de disparar: el jugador decide constantemente entre **atacar, defender, esquivar, recoger power-ups, cambiar de arma y reposicionarse**, lo que hace los enfrentamientos más estratégicos y dinámicos.

## 🧩 Resumen de mecánicas

| Mecánica | Función |
|---|---|
| Movimiento | Desplazarse por la arena |
| Salto | Esquivar y alcanzar plataformas |
| Dash | Movimiento rápido |
| Armas | Atacar al enemigo |
| Escudo | Reducir/absorber daño |
| Power-ups | Obtener ventajas temporales |
| IA | Controlar enemigos |
| Arenas | Cambiar las condiciones del combate |
| Mejoras | Aumentar estadísticas |
| Habilidades | Crear estrategias diferentes |

## 🚀 Objetivo del proyecto

Desarrollar un videojuego 2D de combate que combine **acción, estrategia y movilidad**, con distintos robots, armas, escudos, inteligencia artificial, power-ups y arenas interactivas para crear combates variados y entretenidos.

## 📁 Documentación

- Game Design Document (GDD): `docs/GDD_ROBOT_ARENA_STEEL_CLASH.pdf`

## 👤 Autor Javier Argaez Hernández

**Javier Alejandro Argaez Hernández**
