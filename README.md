# Mi Granja Fit 🐔

App de entrenamiento con mancuernas (en casa) o en el gimnasio, basada en [Ascension System](https://github.com/cellousdrum-del/ascension-system), con temática de granja.

- **Entreno**: ciclo Empuje → Tirón → Pierna → Empuje → Tirón → Pierna → Descanso (la versión con mancuernas de Ascension System, con 6 niveles de dificultad que suben con tu nivel).
- **Casa o gimnasio** (arriba en *Hoy* o en Ajustes): el orden Empuje → Tirón → Pierna es uno solo y sigue igual entrenes donde entrenes. En el gimnasio cada día tiene su versión (6 ejercicios, 45-55 min) con **mancuernas** o **máquinas**: eliges el material para todo y puedes cambiar ejercicios sueltos con ⇄ (se recuerda). Tras las pesas, **cardio extra** guiado de 15-17 min (cinta en cuesta, bici con intervalos, elíptica suave). Los ejercicios que coinciden comparten historial de pesos.
- **Pesos**: apunta kg y repeticiones de cada serie; la próxima vez se rellenan solos. Gráfico de progreso por ejercicio.
- **Estiramientos** guiados al terminar (~10-12 min, según el día) y **Kegel** 3 veces al día.
- **Objetivo** (bajar / mantener / subir de peso): cambia el descanso entre series, añade un circuito quemagrasa si quieres bajar, y da consejos de comida según cómo evoluciona tu peso (media de 7 días y ritmo semanal).
- **Sobrecarga progresiva**: si en la última sesión llegaste al máximo de repeticiones en todas las series, la app te avisa de que deberías subir peso (no lo sube sola).
- **Calendario** (en *Progreso*): cada día con su icono (entreno, descanso, estiramientos/Kegel); al tocar un día ves el entreno completo, dónde lo hiciste, cuánto duró, los músculos y los extras.
- **Duración**: el cronómetro empieza al marcar la primera serie y para al pulsar *Terminar*.
- **Músculos trabajados**: dibujo del cuerpo (delante y detrás) coloreado según cuánto has trabajado cada músculo, hoy o en los últimos 7 días, con el porcentaje de cada uno.
- **Granja**: entrenar da 🌽 maíz → alimentas a tus animales → las gallinas ponen 🥚 → compras más animales. Unos 8 días sin comer y mueren. Cada raza tiene su dibujo y hay accesorios (algunos se ganan con la racha).

Todo vive en `index.html` (HTML + CSS + JS, sin dependencias). Los datos se guardan en el navegador (localStorage); usa *Ajustes → Descargar copia* para hacer copias de seguridad.

## Probarla en el ordenador
Abre `index.html` con doble clic. (Sin instalar ni modo offline.)

## Tenerla en el móvil como app
Tiene que estar en una web con `https`. Lo más fácil, gratis, con GitHub Pages:
1. Crea un repositorio nuevo en GitHub y sube todos los archivos de esta carpeta.
2. Settings → Pages → *Deploy from a branch* → `main` / `(root)` → Save.
3. Abre en el móvil `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.
4. iPhone: Compartir → *Añadir a pantalla de inicio*. Android: menú ⋮ → *Instalar app*.
