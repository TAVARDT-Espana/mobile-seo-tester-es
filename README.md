# Analizador de SEO Movil y Adaptabilidad Web

[![Analizador SEO Movil](https://img.shields.io/badge/TAVARDT-Mobile%20SEO-5b3cf5.svg)](https://tools.tavardt.com/es/prueba-seo-movil/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

Auditoria tecnica de viewport, dimensionamiento responsive y objetivos de toque en dispositivos moviles.

Desarrollado y mantenido por el equipo de arquitectura web de **TAVARDT Espana**.

***

## Capacidades del Analizador de SEO Movil

* **Verificacion de Etiqueta Viewport**: Confirmacion de parametros `width=device-width, initial-scale=1` y descarte de directivas restrictivas.
* **Deteccion de Desbordamiento Horizontal**: Auditoria de contenedores con dimensiones rigidas incompatibles con dispositivos moviles.
* **Analisis de Objetivos Tactiles**: Evaluacion de areas de clic en botones y enlaces para garantizar operabilidad tactil comoda (minimo 48x48px).
* **Legibilidad Tipografica Movil**: Supervision de tamanos de fuente minimos para lectura directa sin necesidad de zoom.
* **Calificacion de Aptitud Mobile-First**: Puntuacion ponderada de 0 a 100 con desglose de advertencias tecnicas prioritarias.

***

## Instalacion y Ejecucion

Compatible con Python 3.8 o superior sin dependencias externas.

```bash
git clone https://github.com/TAVARDT-Espana/mobile-seo-tester-es.git
cd mobile-seo-tester-es
python mobile_seo_tester.py https://empresa.es
```

Salida estructurada en JSON para integracion en canalizaciones:

```bash
python mobile_seo_tester.py https://empresa.es -json
```

***

## Analisis Web Oficial

Acceda a la herramienta interactiva completa en la nube:

* **Prueba de SEO Movil Oficial**
* **[Portal Corporativo TAVARDT Espana](https://ag.tavardt.com/es/)**

***

## Asistencia Tecnica y Auditoria SEO

Para adaptacion integral conforme a Estandares W3C y Directrices Google Mobile-First Indexing, contacte a **TAVARDT Espana**.

***

© 2026 TAVARDT. Todos los derechos reservados.
