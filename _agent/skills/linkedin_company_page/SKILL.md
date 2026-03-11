---
description: "Skill to create a LinkedIn Company Page for RP Films"
---

# Skill: Crear página de empresa en LinkedIn

## Propósito
Proveer una guía estructurada (y opcionalmente automatizable) para crear la página oficial de **RP Films** en LinkedIn, asegurando que el logo y la información corporativa se configuren correctamente.

## Requisitos previos
- Tener una cuenta personal de LinkedIn con privilegios de administrador o creador de páginas.
- Logo cuadrado de **400 × 400 px** en formato PNG (preferiblemente con fondo transparente).
- Información corporativa: nombre oficial, descripción, sitio web, sector, ubicación y datos de contacto.

## Pasos detallados
1. **Acceder al creador de páginas**
   - Navega a `https://www.linkedin.com/company/setup/new/`.
   - Si la URL cambia, busca en LinkedIn *"Crear página de empresa"* desde el menú *Productos > Páginas de empresa*.
2. **Seleccionar tipo de página**
   - Elige *"Pequeña empresa"* (o el tipo que mejor describa a RP Films).
3. **Completar información básica**
   - **Nombre de la empresa**: `RP Films` (exactamente como deseas que aparezca).
   - **URL pública**: `linkedin.com/company/rp-films` (ajusta si está disponible).
   - **Sitio web**: `https://www.rpfilms.com` (o el dominio correspondiente).
   - **Sector**: *Producción de medios / Entretenimiento*.
   - **Tamaño de la empresa**: selecciona la opción adecuada.
   - **Tipo de empresa**: *Privada*.
   - **Ubicación**: Ciudad y país.
4. **Cargar el logo**
   - Haz clic en *"Añadir logo"* y sube el archivo PNG de 400 × 400 px.
   - Verifica que el logo se vea con buen contraste (añade margen de 10 px si es necesario).
5. **Añadir descripción**
   - Redacta una breve descripción (máx. 2 000 caracteres) que destaque la misión y los servicios de RP Films.
6. **Configurar la portada**
   - Opcional: subir una imagen de portada (1 600 × 400 px) que refleje la identidad visual.
7. **Revisar y publicar**
   - Revisa todos los campos, corrige errores y pulsa *"Crear página"*.
8. **Verificación post‑creación**
   - Accede a la nueva página y verifica que el logo aparezca en la esquina superior izquierda.
   - Edita la sección *"Acerca de"* para añadir información adicional (horario, contactos, etc.).
9. **Vincular a tu perfil personal**
   - Sigue el protocolo descrito en la solución de logo (editar experiencia, seleccionar la empresa del menú desplegable).

## Automatización opcional (browser sub‑agent)
Si deseas que el proceso sea parcialmente automatizado, puedes crear un *browser sub‑agent* que:
- Navegue a la URL de creación.
- Complete los campos usando datos predefinidos.
- Suba el logo y la portada desde rutas locales.
- Espere a que el usuario confirme la publicación final.

> **Nota:** LinkedIn puede requerir verificaciones de seguridad (captcha, autenticación de dos factores). El sub‑agent debe detenerse y solicitar intervención humana en esos casos.

## Resultado esperado
- Página de empresa activa en LinkedIn con el logo de RP Films visible.
- Enlace directo desde el perfil personal que muestra el ícono de la empresa.
- Mejora de la presencia digital y SEO interno de LinkedIn.

*Versión: 2026‑03‑09*
