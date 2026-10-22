# Scouting Aztecas UDLAP varonil 2026-27

- `index.html`: versión para jugadores (informe general del equipo y scouting de rivales).
- `coaches/index.html`: versión completa para el cuerpo técnico, cifrada con contraseña (AES-GCM, clave derivada con PBKDF2).
- `liga/index.html`: Liga ABE Var (MW), vista de liga con tabla, power ranking, pronósticos, curvas, estilos, líderes y resultados;
  cifrada con la misma contraseña de coaches. Solo se enlaza desde la versión coaches.

Datos: FIBA LiveStats (Liga ABE). Sitio generado automáticamente; no editar a mano.
