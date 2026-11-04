# Cifras de impacto · CEA

Dashboard animado del Centro de Innovación Pedagógica y Educación Digital (CEA) de la Universidad de San Buenaventura Cali. Está pensado para dejarse en una pantalla: rota solo por cinco apartados (Resumen, Formación Docente, Gestión Curricular, Educación Digital e Inteligencia Artificial) sin que nadie tenga que manipularlo. Fuente de los datos: Informe interno del CEA.

## Ver la página

https://usbvirtual.github.io/Cifras-de-impacto-/

La dirección funciona una vez esté activado GitHub Pages en el repositorio (ver el siguiente apartado).

## Activar GitHub Pages

1. En el repositorio, entrar a **Settings** → **Pages**.
2. En **Build and deployment**, elegir **Source: Deploy from a branch**.
3. En **Branch**, seleccionar `main` y la carpeta `/ (root)`.
4. Hacer clic en **Save**.
5. Esperar 1 a 2 minutos y abrir la URL pública.

## Usarla en una pantalla

- Abrir la URL en Edge o Chrome y hacer clic en **Pantalla completa**.
- También se puede abrir en modo quiosco (Edge) con este comando:

  ```
  msedge --kiosk "https://usbvirtual.github.io/Cifras-de-impacto-/" --edge-kiosk-type=fullscreen
  ```

- El botón **Pausar rotación** detiene el cambio automático de apartados; **Modo día/noche** cambia entre tema claro y oscuro.
- Si alguien toca un filtro, la rotación se pausa 60 segundos y luego continúa sola.
- La vuelta completa por los cinco apartados dura unos 109 segundos.
- Para abrir un apartado directamente, agregar al final de la URL `#formacion`, `#curricular`, `#digital` o `#ia`. Ejemplo: `https://usbvirtual.github.io/Cifras-de-impacto-/#ia`.
- La página necesita Internet para cargar las fuentes de Google Fonts. Sin conexión se muestra con la fuente del sistema.

## Estructura del repositorio

| Ruta | Contenido |
| --- | --- |
| `index.html` | La página completa (estructura, estilos, cifras y textos). |
| `assets/img/` | Logotipos: USB, CEA, VAC, SECUB, Integrity AI y Unión Europea. |
| `assets/favicon-32.png` | Ícono de la pestaña del navegador. |
| `.nojekyll` | Indica a GitHub Pages que publique los archivos tal como están. |

## Actualizar cifras

1. Las cifras y los textos están en `index.html`.
2. Editar el archivo (desde GitHub o en local) y hacer commit a la rama `main`.
3. GitHub Pages se actualiza solo en 1 a 2 minutos. Si la pantalla no muestra el cambio, recargar la página.

## Marca

- La página aplica la identidad del CEA: colores institucionales y las tipografías Manrope, Source Sans 3 y Chakra Petch.
- Los logotipos provienen del kit de marca y se usan sin modificar. Los logotipos institucionales se usan íntegros.
- Los textos de presentación están pendientes de revisión editorial.
