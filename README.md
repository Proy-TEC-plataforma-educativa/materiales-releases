
# Materiales Tecnológicos · UNAHUR

La aplicación de escritorio de Materiales Tecnológicos permite acceder a las materias y sus recursos desde Windows y Linux. Usa la misma cuenta que la plataforma web y se conecta al servicio de la plataforma al abrirla.

**[Descargar la última versión](https://github.com/Proy-TEC-plataforma-educativa/materiales-releases/releases/latest)**

## ¿Por qué instalarla?

- **Tus materias a mano.** Abrís la aplicación desde el escritorio o el menú de aplicaciones y accedés a materiales, ejercicios, semanas y cronogramas.
- **Consulta sin conexión.** Podés guardar una materia en tu equipo para seguir leyendo el contenido descargado si te quedás sin internet o el servicio está caído.
- **Adjuntos disponibles.** Los archivos e imágenes incluidos en el contenido guardado se pueden consultar sin volver a descargarlos.
- **Actualizaciones desde la app.** Cuando se publica una versión nueva, podés revisar las novedades y elegir cuándo instalarla.
- **La misma plataforma.** Seguís usando tu cuenta y los permisos que tenés asignados como estudiante o docente.

## Descargar e instalar

Entrá a la [última versión publicada](https://github.com/Proy-TEC-plataforma-educativa/materiales-releases/releases/latest) y buscá los archivos de descarga en **Assets**.

| Sistema | Archivo | Cómo usarlo |
| --- | --- | --- |
| Windows de 64 bits | `.exe` | Descargalo, ejecutalo y seguí los pasos del instalador. Es la opción recomendada para Windows. |
| Windows de 64 bits | `.msi` | Instalador alternativo para Windows. |
| Linux de 64 bits, x86_64 | `.AppImage` | Descargalo, habilitá el permiso de ejecución y abrilo. Es la opción para recibir actualizaciones desde la app en Linux. |
| Debian, Ubuntu y derivados de 64 bits | `.deb` | Abrilo con el instalador de paquetes de tu distribución. Las siguientes versiones se instalan descargando el nuevo paquete. |

En Linux podés habilitar la ejecución de la AppImage desde **Propiedades → Permisos → Permitir ejecutar como programa**. El nombre de esa opción puede variar según el entorno de escritorio.

Solo necesitás descargar uno de los archivos correspondientes a tu sistema. Los archivos `.sig` y `latest.json` los utiliza el actualizador; no tenés que abrirlos ni instalarlos. Los enlaces **Source code** de GitHub tampoco son instaladores.

## Primer ingreso

1. Abrí **Materiales Tecnológicos**.
2. Iniciá sesión con la cuenta que usás en la plataforma.
3. Entrá a la materia que quieras consultar.

El primer ingreso y la descarga de contenido requieren conexión. La sesión de la aplicación es independiente de la del navegador, por lo que puede pedirte iniciar sesión aunque ya tengas abierta la web.

## Guardar una materia para consultar sin conexión

Dentro de la materia, abrí el botón **Aplicación**, en la esquina inferior izquierda, y elegí **Guardar materia sin conexión**. Esperá a que termine antes de desconectarte.

La copia incluye las secciones, los materiales, los cronogramas y el detalle de las semanas disponibles para tu cuenta, junto con los adjuntos incluidos en ese contenido. La aplicación también conserva las consultas educativas que vas abriendo, pero conviene guardar la materia completa antes de necesitarla sin internet.

Si falla la conexión, vas a ver **Modo sin conexión · Solo consulta**. Podés seguir leyendo lo que quedó guardado en ese equipo. YouTube, los repositorios y otros enlaces externos necesitan internet; guardar una materia no descarga esos sitios ni sus videos.

La copia muestra el contenido de la última descarga. Para renovarla, volvé a conectarte y usá **Actualizar copia sin conexión**. Las entregas, las ediciones y las demás acciones que modifican datos requieren conexión y no quedan pendientes para enviarse después.

Las copias se guardan en el equipo donde las descargaste. Al cerrar sesión, se eliminan las copias sin conexión de esa cuenta.

## Actualizar la aplicación

La aplicación busca versiones nuevas al iniciar. También podés hacerlo desde **Aplicación → Buscar actualizaciones**.

Si hay una versión disponible, elegí **Actualizar**, guardá el trabajo que tengas abierto y confirmá la instalación. En Windows la aplicación se cierra durante ese proceso. En Linux, usando AppImage, se ofrece reiniciarla al terminar.

Si usás el paquete `.deb`, descargá e instalá la nueva versión desde este repositorio. Si una versión antigua no incluye el actualizador, también podés instalar el paquete más reciente manualmente.

## Sobre este repositorio

Acá se publican los instaladores y las novedades de cada versión. El código fuente se mantiene en un repositorio separado.

Podés consultar las versiones anteriores y sus cambios en [Releases](https://github.com/Proy-TEC-plataforma-educativa/materiales-releases/releases).
