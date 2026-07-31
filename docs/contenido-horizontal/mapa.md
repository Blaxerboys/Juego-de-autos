# 🗺️ Diseño del Mundo y Estructura del Mapa

Este documento detalla la distribución geográfica, las estéticas de las ciudades, los tipos de rutas y las mecánicas de balance de terreno para el mundo abierto de **Project Car RPG MMO**.

---

## 1. 🌐 Geometría General y Distribución

El mapa tiene una forma **circular/radial**. La geografía se divide en dos grandes sectores principales que justifican las transiciones de terreno:
*   **Sector Montañoso (2/3 exteriores):** Una masa imponente de cordilleras, zonas subterráneas, selvas y caminos hostiles que rodea el norte, este y oeste.
*   **Sector Llano y Portuario (1/3 restante):** Una zona costera, plana, industrial y de alta velocidad ubicada en la parte sur.
*   **El Núcleo (Centro):** Un circuito permanente de carreras y drift que sirve como el epicentro de eventos PvP y punto de convergencia del mapa.

---

## 2. 🏙️ Las 3 Ciudades y sus Zonas de Comunidad

Cada ciudad está diseñada para favorecer un estilo de conducción, un rol de vehículo específico y una actividad social del MMO sin necesidad de usar menús flotantes.

### 🌆 Ciudad 1: Neo-Tokio Subterráneo (Foco: Drift / Estética)
*   **Ubicación:** Dentro de las cavernas y túneles de la gran montaña central.
*   **Estética:** Cyberpunk/Underground agresivo. Neones densos, asfalto húmedo que refleja las luces, túneles claustrofóbicos y autopistas multinivel de peaje.
*   **Hub Social:** *Parking Subterráneo (Inspirado en Daikoku Futo).* Espacios cerrados con iluminación artificial donde los jugadores se reúnen a abrir el capó, encender neones, mostrar el motor y comerciar o votar skins/vinilos.

### 🏔️ Ciudad 2: La Cumbre Favela (Foco: Todo Terreno / Control)
*   **Ubicación:** En las laderas empinadas de la montaña, adaptándose verticalmente al relieve.
*   **Estética:** Inspirada en los barrios de Río de Janeiro y los pueblos de montaña de Jujuy. Calles angostas, subidas extremas con inclinaciones de hasta el 30%, adoquines sueltos, tierra y casas escalonadas que bordean los precipicios.
*   **Hub Social:** *El Mirador / Desguace Comunitario.* Ubicado en el punto más alto. Un taller cooperativo al aire libre donde se prueban suspensiones y los jugadores se retan a duelos de escalada (Hillclimb).

### 🏭 Ciudad 3: El Puerto Industrial / Detroit (Foco: Velocidad / Sprinters)
*   **Ubicación:** En la superficie plana del tercio sur del mapa, de cara al mar.
*   **Estética:** Puertos masivos (estilo Oakland/Long Beach) mezclados con fábricas pesadas abandonadas de Detroit. Grúas gigantes, contenedores de carga, asfalto gastado y autopistas elevadas de 5 carriles (*Shuto Expressway* americano).
*   **Hub Social:** *Los Hangares de Crafteo.* Zonas industriales gigantescas donde los jugadores compran sus propiedades de Housing, instalan sus bancos de pruebas (Dinos) y se organizan en talleres masivos de personalización técnica.

---

## 3. 🛣️ Red de Rutas y Biomas

Las conexiones entre las ciudades actúan como zonas de transición y campos de juego balanceados para los diferentes roles:

*   **Ruta Arizona (Noroeste):** Desierto abierto, cañones de tierra roja y rectas infinitas con tormentas de arena. Ideal para que los *Tanques* abran paso.
*   **Ruta de las 1000 Curvas (Noreste):** Asfalto perfecto en zigzag continuo cuesta abajo. El paraíso técnico para el *Drift* y los autos de agilidad.
*   **Camino Julio Cesare (Altas Cumbres):** Tramo de rally puro inspirado en las sierras de Córdoba/Mendoza. Tierra suelta, piedras sueltas, vados de agua y neblina densa que cambia el agarre del neumático dinámicamente.
*   **Ruta Safari / Jungla (Este):** Vegetación densa que invade el camino, lodo profundo, árboles caídos destructibles y ríos que cortan el paso.
*   **Ruta 40 (Sur):** Autopista panorámica de asfalto liso y clima soleado que conecta la zona industrial. El terreno óptimo para exprimir la velocidad máxima de los *Sprinters*.
*   **Los Macizos (Túneles):** Conexiones de hormigón armado e iluminación naranja que perforan la roca, comunicando la ciudad superficial con el submundo de neón.

---

## 4. ⚖️ Diseño de Balance en Carreras Multiclase

Para garantizar que un *Sprinter* no domine todo el juego por su velocidad punta, ni un *Tanque* se quede atrás para siempre, las carreras largas aplican **Zonas de Transición Estrechas**:

1.  **Atajos Condicionales por Rol:** 
    *   *Ejemplo en Desierto:* El camino principal es de asfalto limpio (largo y curvo). Hay un atajo en línea recta lleno de rocas pesadas. El *Sprinter* debe ir por el asfalto; el *Tanque* puede ir en línea recta embistiendo los obstáculos, equilibrando el tiempo de llegada.
2.  **Obstáculos Ambientales Dinámicos:**
    *   *Ejemplo en Selva:* El lodo profundo frena el *Slip Ratio* (tracción) de los autos livianos, obligándolos a tomar puentes colgantes angostos y más largos. Los autos *Off-road* o *Tanques* cruzan el lodo pesado en línea recta sin perder velocidad.
3.  **Zonas de Relevo y Bloqueo:**
    *   En tramos revirados como las *1000 Curvas*, los autos de *Control* pueden usar su ancho y peso para bloquear carriles estrechos, ayudando a que los *Sprinters* de su propio equipo se escapen en la recta final del Puerto.
