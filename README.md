# Auditoría Bonus - GitHub Pages

Aplicación estática para revisar tareas Bonus desde un CSV local.

## Publicar en GitHub Pages

1. Crear un repositorio nuevo en GitHub, por ejemplo `auditoria-bonus`.
2. Subir `index.html` a la raíz del repositorio.
3. Ir a **Settings > Pages**.
4. En **Build and deployment**, elegir **Deploy from a branch**.
5. Elegir la rama **main** y la carpeta **/(root)**.
6. Presionar **Save**.
7. Esperar uno o dos minutos y abrir la URL indicada por GitHub.

## Uso

1. Abrir la aplicación publicada.
2. Presionar **Cargar CSV**.
3. Seleccionar el archivo diario con la columna `Link_Foto`.
4. Revisar únicamente tareas válidas.
5. Marcar cada tarea como OK o NOK.
6. Exportar el resultado o guardar una sesión de respaldo.

## Privacidad

- No subir el CSV real al repositorio.
- El archivo se procesa dentro del navegador.
- Los resultados se almacenan en `localStorage` del navegador.
- GitHub Pages no provee sincronización entre dos auditores.
- Para trabajo simultáneo se necesitará una base de datos y autenticación.

## Columnas reconocidas

- `Task_ID`
- `Dia`
- `Region`
- `Area`
- `Subregion`
- `Supervisor`
- `Promotor`
- `Cod_Cliente`
- `Tarea`
- `Validada`
- `Link_Foto`

También conserva las demás columnas originales al exportar.
