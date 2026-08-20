# Mi Pequeño Campeón

Álbum prenatal privado y PWA instalable para registrar citas, evolución, medidas, ecografías, fotos y recuerdos durante el embarazo. Incluye impresión optimizada en A4 y respaldo/restauración de todos los datos.

## Funciones

- Cálculo de semana gestacional y cuenta regresiva mediante fecha probable de parto.
- Agenda de controles, ecografías, análisis y otras citas.
- Registro de peso materno, presión arterial, altura uterina, frecuencia fetal y medidas estimadas del bebé.
- Galería de fotos, ecografías y notas familiares.
- Vista tipo álbum preparada para imprimir o guardar como PDF.
- Respaldo y restauración en JSON.
- PWA instalable y disponible sin conexión tras la primera carga.
- Privacidad por diseño: los datos se guardan en el navegador del dispositivo.

## Uso local

Sirve esta carpeta con cualquier servidor estático. Por ejemplo:

```bash
npx serve .
```

Abre la URL mostrada en el navegador. Para instalarla en iPhone, usa **Compartir → Agregar a inicio**.

## Publicación

Es compatible con GitHub Pages, Netlify, Vercel y cualquier hosting estático. Para GitHub Pages, publica la rama principal desde la raíz del repositorio.

## Privacidad y alcance médico

La aplicación no envía información a un servidor. El respaldo es importante antes de limpiar el navegador o cambiar de dispositivo. Esta herramienta organiza información familiar; no interpreta resultados ni sustituye la evaluación o indicaciones de un profesional de salud.

## Licencia

MIT
