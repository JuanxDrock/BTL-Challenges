Informe en línea del equipo Follina-Blue de Team Labs

Esta es la descripción del desafío en línea de Blue Team Labs: Follina

Descripción :

Un viernes por la noche, cuando tenías ganas de celebrar el fin de semana, tu equipo fue alertado de una nueva vulnerabilidad de ejecución remota de código que estaba siendo explotada activamente.

Mis pasos :

- Archivo zip descargado

Pregunta 1) ¿Cuál es el valor hash SHA1 de la muestra? (Formato: SHA1Hash)

- Se accedió al directorio del archivo zip para encontrar sample.doc
- Comando: sha1sum sample.doc

Pregunta 2) Según VirusTotal, ¿cuál es el tipo de archivo completo de la muestra proporcionada? (Formato: XXXX)

- Abrí VirusTotal y subí el archivo sample.doc
- Revisé la pestaña Detalles

Respuesta: Documento Office Open XML

Pregunta 3) Extraiga la URL que se utiliza en el ejemplo y envíela (Formato: https://x.dominio.tld/ruta/a/algo )

- Consulta la pestaña Relaciones en VirusTotal y encuentra la URL que coincida con la pregunta.

Pregunta 4) ¿Cuál es el nombre del archivo XML que almacena la URL extraída? (Formato: nombre.archivo.ext)

- Consulta la sección de archivos agrupados en la pestaña Relaciones y encuentra el archivo xml con la mayor cantidad de alertas maliciosas.

Pregunta 5) La URL extraída accede a un archivo HTML que activa la vulnerabilidad para ejecutar una carga útil maliciosa. Según las funciones de procesamiento de HTML, cualquier archivo con menos de <Número> bytes no invocaría la carga útil. Envíe el <Número> (Formato: Número de bytes).

-Realicé una búsqueda de funciones de procesamiento HTML y encontré un informe sobre este ataque a Huntress.
-Después de revisarlo rápidamente, descubrí que el tamaño es de 4096 bytes.

Pregunta 6) Tras su ejecución, el programa intentará finalizar un proceso si ya está en ejecución. ¿Cuál es el nombre de este proceso? (Formato: nombrearchivo.ext)

-Continué buscando en el informe de Huntress y descubrí que el script de ejecución intentó matar:
Respuesta: msdt.exe

Pregunta 7) Se le pidió que escribiera una regla de detección basada en procesos utilizando el ID de evento de Windows 4688. ¿Cuáles serían el nombre del proceso (ProcessName) y el nombre del proceso padre (ParentProcessName) que se usarían en esta regla de detección? [Pista: ¡Es hora de usar OSINT!] (Formato: ProcessName, ParentProcessName)

-Continué la búsqueda en el informe de Huntress y encontré el nombre del proceso, así como su proceso padre.

Pregunta 8) Envíe el ID de la técnica MITRE utilizada por la muestra para su ejecución [Sugerencia: ¡Las plataformas de entorno aislado en línea pueden ser útiles!] (Formato: TXXXX)

-Utilicé VirusTotal y fui a la pestaña Comportamiento para ver las técnicas de MITRE.

Pregunta 9) Envíe el CVE asociado a la vulnerabilidad que se está explotando (Formato: CVE-XXXX-XXXXX)

- Me desplacé hasta la parte superior de VirusTotal y encontré la etiqueta CVE:
cve-2022–30190

Herramientas utilizadas:
-Kali Linux
-Virus Total
-Clear Web

Conclusiones clave:

-Comprendió mejor el proceso de respuesta e investigación de incidentes.
-Aprendió más sobre cómo las herramientas OSINT pueden ayudar tanto en el aprendizaje como en la respuesta a incidentes.
-Comprendió cuántos pasos pueden usar este tipo de ataques (recorrido de directorios, troyano, acceso remoto).
-Comprendió mejor el procesamiento de hash y HTML.
