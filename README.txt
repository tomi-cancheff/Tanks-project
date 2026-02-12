# Tanks Project

Proyecto de juego de tanques hecho en **Unity** (URP), basado en el tutorial oficial de Tanks y extendido con selección de tanques, IA, power-ups y soporte de controles para teclado/móvil.

## ¿Qué incluye?
- Partidas por rondas (hasta `m_NumRoundsToWin`, por defecto 5) con flujo completo de inicio/juego/fin de ronda.
- Juego local de **2 a 4 tanques** con selección desde menú (jugadores humanos o CPU).
- Alternancia de escenarios entre **Level_Desert** y **Level_Jungle**.
- Sistema de **power-ups**: velocidad, reducción de daño, bonus de disparo, curación, invencibilidad y multiplicador de daño.
- UI de juego y menú (incluye controles móviles/virtual joystick).

## Estructura rápida
- `Assets/_Tanks/Scenes/`: escenas jugables.
- `Assets/_Tanks/Scripts/Managers/`: ciclo de partida y gestión de jugadores.
- `Assets/_Tanks/Scripts/Tank/`: movimiento, disparo, salud, IA e inputs.
- `Assets/_Tanks/Scripts/PowerUp/`: lógica y respawn de power-ups.
- `Assets/_Tanks/Scripts/UI/`: menú principal, HUD y pausa.

## Requisitos
- Unity **6000.2.6f2**.
- Paquetes clave: `com.unity.inputsystem`, `com.unity.render-pipelines.universal`.

## Cómo ejecutar
1. Abrir el proyecto en Unity Hub con la versión indicada.
2. Verificar escenas en Build Settings:
   - `Assets/_Tanks/Scenes/Level_Desert.unity`
   - `Assets/_Tanks/Scenes/Level_Jungle.unity`
3. Ejecutar (`Play`) desde el editor.

## Notas
- Recurso base del proyecto: `Assets/_Tanks/Documentation.txt`.
- Este repositorio contiene arte, prefabs y scripts listos para iterar gameplay y balance.
