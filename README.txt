DIF Cotizaciones Web v14

Correcciones v14:
- Corrige el problema donde cada cargo se enviaba a una página diferente en el visor.
- Corrige la medición de overflow de páginas; ya no usa scrollHeight como referencia principal porque con height fijo devuelve falsos positivos.
- Mantiene la vista con panel izquierdo y cotización derecha.
- Mantiene el formato global guardado en SharePoint/Power Automate.
- Ajusta impresión a Letter con páginas de 8.5 x 11 in.

Prueba recomendada:
- Abrir index.html.
- Verificar que los cargos se agrupen correctamente en la primera página.
- Imprimir / PDF con Letter, escala 100% o predeterminada, márgenes ninguno, gráficos de fondo activados.
