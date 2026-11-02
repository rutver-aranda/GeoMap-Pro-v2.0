# GeoMap-Pro-v2.0
Elaboración automática de planos cartográficos - Rutver Aranda Arguello

GeoMap Pro v2.0 es una herramienta web de ingeniería cartográfica y topográfica concebida, desarrollada y programada por el Ing. Rutver Aranda Arguello. Su objetivo central es resolver el problema recurrente en el trabajo técnico de campo y gabinete: la generación rápida, estandarizada y directa de planos perimétricos y cuadros de construcción para parcelas agrícolas y predios rústicos.

La problemática: Los flujos tradicionales en software SIG de escritorio.
1. En las labores cotidianas de asesoría técnica, delimitación parcelaria, ordenamiento territorial y gestión agroforestal, la elaboración de un plano técnico para entregar a productores o anexar a expedientes técnicos suele demandar un flujo fragmentado y repetitivo en sistemas de información geográfica convencionales (como QGIS o ArcGIS):
2. Importación y configuración de capas: Cargar manualmente tablas de coordenadas o archivos vectoriales y verificar su sistema de referencia de coordenadas (SRC).
3. Cálculos manuales o mediante plugins complementarios: Usar herramientas de geometría o complementos adicionales para calcular rumbos/azimuts, distancias lado a lado, perímetros y áreas en hectáreas.
4. Composición de impresión exhaustiva: Abrir el Diseñador de Impresión, configurar la cuadrícula (grid) cartográfica con ticks e intervalos adecuados, alinear la rosa de los vientos, diseñar tablas de atributos con formato formal, insertar logotipos institucionales y ajustar rótulos de proyecto.
5. Dependencia tecnológica en campo: Este proceso exige una computadora con software de escritorio instalado, lo que imposibilita expedir o validar un plano formal de manera inmediata directamente desde un teléfono móvil o tableta en recorridos de campo.

La solución: Automatización web multiplataforma en un solo paso.
Ante la necesidad de simplificar estos pasos sin comprometer la precisión geodésica, el Ing. Rutver Aranda Arguello desarrolló GeoMap Pro v2.0 como una plataforma accesible desde cualquier navegador web (móvil o de escritorio, en Android, iOS, Windows o macOS), eliminando instalaciones pesadas y centralizando todo el procesamiento en el dispositivo del usuario:
a) Captura flexible y multi-origen: Permite cargar archivos estructurados en formato CSV/Excel o ingresar coordenadas manualmente, soportando coordenadas UTM métricas, grados decimales y grados/minutos/segundos (GMS) sin restricciones arbitrarias de formato.
b) Reproyección geodésica precisa: Integra motores de transformación de coordenadas compatibles con sistemas oficiales como WGS 84 (EPSG:4326), UTM Zona 15N (EPSG:32615) y proyecciones nacionales mexicanas como ITRF2008 / LCC (EPSG:6372) e ITRF2008 / UTM 15N (EPSG:6370).
c) Cálculo analítico en tiempo real: Estructura de forma automatizada el Cuadro de Construcción Topográfico (vértices correlativos, lados, distancias métricas, azimuts sexagesimales y coordenadas exactas de origen), así como el cálculo de superficie total (ha / m²) y longitud perimétrica.
d) Salida cartográfica lista para impresión (Hoja Carta Horizontal): Genera directamente la lámina cartográfica formal con grilla UTM proporcional, simbología técnica, escala gráfica y numérica calculada automáticamente, cajas de rotulación y espacios simétricos para sellos o logotipos institucionales.
e) Interoperabilidad completa con SIG: Además de emitir el plano en PDF de alta resolución listo para entrega física o digital, permite exportar los datos depurados hacia formatos vectoriales universales (GeoJSON, KML y CSV normalizado), listos para integrarse sin fricción en proyectos posteriores en QGIS, Google Earth, Avenza Maps o Locus Map.

GeoMap Pro v2.0 transforma una tarea que habitualmente requiere entre 30 y 60 minutos en un entorno SIG de escritorio en un procedimiento directo de escasos segundos, optimizando sustancialmente el trabajo de brigadas, técnicos y productores en territorio.

Si consideras que este proyecto es de utilidad, puedes colaborar con el autor comunicándote a su correo personal (aranda3571@gmail.com) o vía WhatsApp al número 9641122856. 
