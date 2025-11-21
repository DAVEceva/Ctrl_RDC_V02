Descripción General
Zebra Scanner V02 es una aplicación web progresiva (PWA) diseñada para dispositivos ZEBRA. Permite al personal logístico registrar y controlar etiquetas de mercadería enviada desde una planta industrial a un centro de distribución, garantizando comparaciones precisas entre el control interno y el registro emitido por la planta mediante nuevo sistema de gestión SAP.​

Flujo de Trabajo
Ambos equipos (planta y logística) escanean las etiquetas de mercadería en simultáneo para mantener sincronización de registros.​

El operario logístico accede a la pantalla de “Cierre de control”, donde puede visualizar el total de etiquetas escaneadas y cargar el archivo Excel entregado por la planta (columna “O” – “Handling Unit”).​

La app realiza una comparación automática entre los datos escaneados y los del archivo importado, mostrando visualmente si los totales coinciden (verde/rojo).​

Se genera una lista rápida de diferencias (sobrantes, faltantes, coincidencias) y permite búsquedas/filtros internos por código para facilitar la trazabilidad de casos dudosos.​

Botón de exportación permite descargar un informe Excel con pestañas separadas para cada grupo (sobrantes, faltantes, coincidencias).​

Registro y Persistencia
Cada acción relevante (escaneo, importación, filtros, exportaciones) se guarda automáticamente en el almacenamiento persistente (localStorage) del dispositivo, facilitando la recuperación del estado del control y del historial de operaciones aun si la app se cierra o el dispositivo se reinicia.​

Instrucciones de Uso
Iniciar app en dispositivo ZEBRA y seleccionar “Empezar a escanear”.

Registrar manualmente o mediante escáner todos los códigos de etiquetas, verificando que no se repitan.

Al finalizar el escaneo, ingresar a la pantalla de “Cierre de control”.

Cargar el archivo Excel recibido de planta. Usar la columna “O” (“Handling Unit”) para la comparación.

Revisar la pantalla de comparación visual (verde/rojo), la lista de diferencias y usar los filtros/busqueda según sea necesario.

Exportar el resultado en formato Excel para registro y análisis.

Toda la actividad queda registrada y recuperable en el dispositivo.

Requerimientos Técnicos
Dispositivo: ZEBRA con navegador compatible con PWA.

Archivo importación de planta debe contener códigos en la columna “O”, bajo el encabezado “Handling Unit”.

Conectividad opcional, ya que los datos y el progreso se almacenan localmente en el equipo.
