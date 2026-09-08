# FLUJO: EVALUACION DE ADOPCION
Subida inicial: Flujo pensado en reducir carga operativa y generar reporteria en tiempo real. Carga inicial.
Este flujo automatiza la lectura, filtrado condicional, y actualizacion de metricas clave en la empresa.
**Trigger:** Llenado de formulario en link.
**Google Sheets:** Añade una nueva fila en un libro con las respuestas del formulario.
**Java Code:** Procesa y limpia informacion extraida, codigo personalizado para el caso.
**Nodo IF (condicional):** Evalua criterios logicos establecidos en la empresa para segmentar registros.
**Gmail:** Envia notificaciones personalizadas al usuario, notificando si está habilitado para ejercer la adopcion de una mascota. Tambien permite un agendamiento automatico para entrevistas en Calendar.
**Merge:** Consolida todos los datos de registros.
**Power BI:** Actualiza el conjunto de datos de forma automatica para mantener las graficas en tiempo real.

<img width="1344" height="590" alt="WhatsApp Image 2026-09-08 at 16 05 30" src="https://github.com/user-attachments/assets/a3809e40-ae05-46ad-b2ab-938c684d6e29" />
