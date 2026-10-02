# Estadística descriptiva: medidas numéricas

Sitio de la sesión del **3 de septiembre de 2026** · Doctorado en Ciencias Económicas y Administrativas,
Universidad de Sonora · materia de Procesamiento y análisis de datos.
Base: Anderson, Sweeney y Williams, *Estadística para negocios y economía*, capítulo 3. Software de los
ejercicios: IBM SPSS.

Presentación de **Pavel Raúl Dennis Quiñónez** (docente: Dr. Sergio Ramón Rossetti López).
Versión web homologada por Eduardo Salas García (esalas@eduardosalas.com), con el mismo formato que las
presentaciones web de los demás expositores del curso. El contenido es el de la presentación original
en PowerPoint (`docs/Presentacion_Capitulo3_Estadistica_Descriptiva_UNISON.pptx`, 45 diapositivas).

## Cómo publicarlo en GitHub Pages

1. Crea un repositorio **público** en GitHub. Un nombre corto ayuda porque será parte del link:
   por ejemplo `estadistica-descriptiva-medidas-numericas`.
2. Sube **todo el contenido de esta carpeta** a la raíz del repositorio (los archivos, no la carpeta
   que los contiene). Puedes arrastrarlos a la interfaz web de GitHub con *Add file → Upload files*.
3. En el repositorio ve a **Settings → Pages**.
4. En *Source* elige **Deploy from a branch**; en *Branch* elige **main** y la carpeta **/ (root)**.
   Guarda.
5. Espera uno o dos minutos. GitHub te mostrará el link, con la forma
   `https://TU-USUARIO.github.io/estadistica-descriptiva-medidas-numericas/`
6. Comparte ese link con el grupo.

## Estructura

```
index.html                     La presentación: 48 láminas en un solo archivo, funciona sin internet
assets/                        7 imágenes de la presentación original (JPG)
datos/StartSalary.sav          12 sueldos iniciales (tabla 3.1) · diapositiva 13
datos/BackToSchool.sav         Gastos de regreso a clases, 25 de primer año y 20 de último · diap. 21–23
datos/NCAA.sav                 10 partidos de basquetbol de la NCAA · diap. 30–32
datos/Stereo.sav               Tienda de estéreos (comerciales y ventas) · ejemplo de la diap. 38
datos/Visa.sav                 15 cargos mensuales con tarjeta · actividad de la diap. 45
datos/Employee_data.sav        Archivo de ejemplo de SPSS (474 empleados), usado en la sesión
docs/Presentacion_Capitulo3_Estadistica_Descriptiva_UNISON.pptx   Presentación original (respaldo)
(no se incluye el PDF)                                              Artículo de aplicación: Elsevier, todos los derechos reservados; se enlaza por DOI https://doi.org/10.1016/j.jretconser.2024.104219
```

## Correspondencia entre láminas y diapositivas

| Lámina web | Diapositiva original | Contenido |
|---|---|---|
| 1 | 1 | Portada |
| 2 | — | Ruta de la sesión (agregada) |
| 3–46 | 2–45 | Una lámina por diapositiva, en el mismo orden (lámina = diapositiva + 1) |
| 47 | — | Materiales: descargas (agregada) |
| 48 | — | Índice de bloques (agregada) |

Cada lámina muestra en su encabezado el número de la diapositiva original («3.2 · diap. 16»). Los
bloques del índice (tecla `M`) siguen las secciones 3.1 a 3.6 del capítulo, como el mapa de la
diapositiva 2.

## Cómo descargan los archivos tus compañeros

En la lámina 47 («Materiales») hay un botón por cada base y por cada documento; las láminas de
ejercicio (14, 22, 31 y 46) tienen además el botón de su base. Al hacer clic, el archivo se descarga
directo a la carpeta de descargas, porque los enlaces llevan el atributo `download`. Las bases se
guardan en el repositorio con nombres sin espacios (`datos/BackToSchool.sav`), pero se descargan con
el nombre que usa la presentación (`2.1. BackToSchool.sav`, `3.1. NCAA.sav`, `Visa.sav`, etc.).

Tres cosas que conviene cuidar:

1. **Sube las carpetas `datos/`, `docs/` y `assets/` completas.** Si solo subes `index.html`, los
   botones darán error 404 y no se verán las figuras.
2. **Comparte el link de Pages, no el del repositorio.** El de Pages tiene la forma
   `https://TU-USUARIO.github.io/repo/`.
3. **Respeta mayúsculas y minúsculas.** GitHub Pages distingue entre `NCAA.sav` y `ncaa.sav`. Si
   renombras un archivo, actualiza también el enlace en `index.html`.

## Cómo usar la presentación

| Acción | Cómo |
|---|---|
| Avanzar y retroceder | Flechas `→` `←`, barra espaciadora, o deslizar en móvil |
| Abrir el índice de bloques | Tecla `M` o botón **Bloques** |
| Saltar a un bloque | Teclas `1` a `8` |
| Cambiar entre tema claro y oscuro | Tecla `T` |
| Pantalla completa | Tecla `F` |
| Ir a una lámina por enlace | Agrega `#dN` al link, por ejemplo `#d36` |
| Exportar a PDF | Botón **PDF** de la barra inferior |

## Si falla el internet en el aula

`index.html` es autocontenido (no carga nada de la red; las figuras están en `assets/`). Descarga la
carpeta y abre `index.html` desde tu computadora. Como respaldo está la presentación original en
`docs/`.

## Artículo de aplicación

Alfadhel, M. (2025). Unpacking when and how business analytics affect firm performance and customer
satisfaction: A longitudinal examination. *Journal of Retailing and Consumer Services, 84*, 104219.
<https://doi.org/10.1016/j.jretconser.2024.104219>

[Inferencia] Ninguna de las 45 diapositivas menciona el artículo; el expositor lo comentó de palabra
al final de la sesión, sin dar autor ni título. Se identifica con este PDF porque estaba en la carpeta
de la sesión y su resumen coincide con lo que se describió (datos de empresas de 2019 a 2023,
capacidades de analítica de negocios, desempeño y satisfacción del cliente). Por eso aparece solo en
la lámina de Materiales y no en el cuerpo de la presentación. Es el PDF del editor: antes de hacer
público el repositorio, confirma que puedes redistribuirlo; si no, deja solo el enlace DOI.

## Ajustes respecto a la presentación original

Ninguno cambia el contenido; se listan para que el expositor los revise.

1. **Láminas agregadas:** ruta de la sesión (2), materiales (47) e índice de bloques (48). La ruta
   indica las diapositivas de cada bloque en lugar de minutos, porque la presentación no los trae.
2. **Títulos:** se usa el encabezado visible de cada diapositiva («MEDIA», «PERCENTÍLES»…) en
   minúsculas tipo oración. El PPTX conserva, ocultos bajo otras formas, títulos de diapositivas
   anteriores (por ejemplo «Mediana: el valor central» en los ejercicios NCAA); esos no se muestran.
   En las diapositivas sin encabezado visible (2, 3, 20, 25, 44 y 45) se usa ese título del PPTX.
3. **Portada:** la diapositiva 1 se convirtió en la portada con el formato homologado; conserva el
   escudo de la Universidad y los textos. Se omitió el ícono decorativo de gráfica de barras.
   El nombre del expositor se escribe con acentos (Raúl, Quiñónez); la diapositiva dice
   «Pavel Raul Dennis Quiñonez».
4. **Fórmulas:** se escriben como texto, igual que en las diapositivas. La fórmula de la diapositiva 5,
   que en el original es una imagen, se redibujó como fracción.
5. **Tabla 3.1** (diapositiva 13) y tabla de auditorías (diapositiva 42): convertidas en tablas reales.
6. **Gráficas redibujadas** a partir de los datos y formas del PPTX: líneas de Dawson y J.C. Clark
   (diap. 20), histogramas de sesgo (diap. 25), recta de cuartiles (diap. 12), escala de z (diap. 26) y
   diagrama de caja (diap. 35). Las figuras del libro (3.2 y 3.5), las campanas (diap. 10, 15 y 28) y
   la figura de la mediana (diap. 7) son las imágenes originales del PPTX.
7. **Botones de descarga** en las láminas de ejercicio y en Materiales; se omitió el pie de página
   repetido en cada diapositiva («Universidad de Sonora • Capítulo 3 • …»), que reemplaza la barra
   inferior.

## Notas de revisión

Errores o inconsistencias que se **conservaron tal como están** en las láminas, para que el expositor
decida si los corrige. Las etiquetas indican el tipo de afirmación.

1. **Diapositiva 16 (lámina 17), datos de Dawson Supply.** [Verificable] La lista
   `9 10 10 10 11 11 10 11 10 10` tiene seis 10 y tres 11 (media 10.2). El libro (ejercicio 20 y
   figura 3.2, que la misma diapositiva reproduce) y la gráfica de la diapositiva 20 tienen cinco 10 y
   cuatro 11 (media 10.3). La de J.C. Clark también es 10.3. La diapositiva dice «Media ≈ 10 días»
   para ambos, siguiendo al libro. La conclusión no cambia (rango de 2 contra 8 días).
2. **Diapositiva 28 (lámina 29), encabezado.** [Verificable] El encabezado visible es «Teorema de
   Chebyshev», pero el contenido (≈ 68 %, ≈ 95 %, casi todos los datos) es la **regla empírica**, que
   solo vale para distribuciones en forma de campana. El título «Regla empírica» existe en el PPTX pero
   queda oculto. Conviene no mezclar las cotas de Chebyshev (al menos 75 % con ±2s) con las de la regla
   empírica (≈ 95 %).
3. **Diapositiva 31 (lámina 32), probabilidades del ejercicio NCAA.**
   - [Verificable] La expresión `1-(84-76.5)/7.01` resta el valor z a 1 y no aplica la función de
     distribución normal; da números negativos (−0.0699 y −0.9258), que son los que quedaron
     guardados en `datos/NCAA.sav` (columnas Z84, P84 y P90). La diapositiva nombra `CDF.NORMAL` pero
     no la usa en la expresión.
   - [Inferencia] La forma que corresponde al inciso b) es `1 - CDF.NORMAL(84,76.5,7.01)` ≈ 0.142
     (14.2 % de los partidos con 84 puntos o más) y `1 - CDF.NORMAL(90,76.5,7.01)` ≈ 0.027 (2.7 %
     con más de 90).
   - [Verificable] La diapositiva usa el nombre `P84` dos veces; el segundo cálculo (90 puntos)
     debería llamarse `P90`, como está en la base.
4. **Diapositiva 25 (lámina 26), histogramas de sesgo.** [Interpretación] Las barras rotuladas
   «Sesgo negativo (izquierda)» tienen la cola larga hacia la derecha, y las de «Sesgo positivo
   (derecha)» la tienen hacia la izquierda; las formas parecen intercambiadas respecto de sus
   rótulos (en el libro, figura 3.3, el sesgo a la izquierda tiene la cola a la izquierda). La regla
   escrita debajo (sesgo positivo: media > mediana) sí es correcta.
5. **Diapositiva 32 (lámina 33), nombres de variables.** [Verificable] La expresión
   `PuntosGanador - PuntosPerdedor` no corresponde a los nombres de `NCAA.sav`, donde las variables
   son `Points` (ganador) y `Points_A` (perdedor); la base ya trae `WinningMargin` y la variable
   `Margen_victoria` calculada en clase. También dice «Variable objetivo» donde SPSS en español
   dice «Variable de destino» (como en la diapositiva 31).
6. **Diapositiva 30 (lámina 31).** [Verificable] El texto dice «proporcionó los datos siguientes»,
   pero los datos no aparecen en la diapositiva; están en `datos/NCAA.sav`. Esa base tiene 437 filas:
   10 con datos y el resto vacías salvo por los nombres de equipo en blanco y las columnas calculadas,
   por lo que conviene filtrar los 10 casos válidos antes de calcular.
7. **Diapositiva 15 (lámina 16).** [Verificable] La etiqueta de sección dice «3.1» aunque el tema
   (medidas de variabilidad) es la sección 3.2.
8. **Diapositiva 26 (lámina 27).** [Interpretación] La escala de z va de −3σ a +1σ y el marcador está
   en −3σ, mientras el ejemplo calcula z = −1.50; parece un control deslizante sin ajustar.
9. **Diapositiva 12 (lámina 13), cuartiles.** [Verificable] Con los 12 sueldos, SPSS reporta
   P25 = 3 457.5 y P75 = 3 625, distintos de Q1 = 3 465 y Q3 = 3 600 del libro. No es un error: la
   misma diapositiva advierte que hay convenciones distintas. Sirve para explicar la diferencia en el
   ejercicio StartSalary.
10. **Ortografía.** «FACULTADAD INTERDISCLIPLINARIA» (diap. 1, por «Facultad Interdisciplinaria»);
    «Percentíles» y «Cuartíles» con acento (diap. 10–13, 23 y 32); «Magen de la victoria» (diap. 32);
    «realizaran» por «realizarán» (diap. 45); «La clave para elaborar de un diagrama de caja»
    (diap. 35).

## Fuentes

- Anderson, D. R., Sweeney, D. J., & Williams, T. A. *Estadística para negocios y economía*, cap. 3:
  Estadística descriptiva: medidas numéricas.
- Alfadhel, M. (2025). *Journal of Retailing and Consumer Services, 84*, 104219.
  <https://doi.org/10.1016/j.jretconser.2024.104219>
- Bases de datos: archivos del capítulo proporcionados en la sesión (`Base de Datos SPSS`) y archivo
  de ejemplo `Employee data.sav` de IBM SPSS.
