# Coherent Research — Web corporativa

Desarrollo web para **Coherent Research**, consultora especializada en financiación de la investigación y programas de excelencia europea (ERC, MSCA, Horizon Europe).

---

## Sobre el proyecto

Web corporativa bilingüe (ES/EN) desarrollada en WordPress con el editor nativo de bloques. Diseñada para ser rápida, accesible y fácil de gestionar de forma autónoma, sin necesidad de conocimientos técnicos.

**Cliente:** Lorena Tomás Laudo — [coherentresearch.com](#)
**Estudio:** [Torrezno Estudio](https://torreznoestudio.com)
**Año:** 2026

---

## Stack

- **CMS:** WordPress (editor de bloques nativo, sin page builders)
- **PHP:** 8.x
- **Tema:** Tema a medida basado en bloques + `theme.json`
- **Idiomas:** ES / EN (bilingüe)

---

## Estructura del proyecto

```
/
├── theme/                  # Tema personalizado
│   ├── theme.json          # Tokens de diseño, tipografía y colores
│   ├── templates/          # Plantillas de página
│   ├── parts/              # Partes reutilizables (header, footer…)
│   └── patterns/           # Patrones de bloques personalizados
├── plugins/                # Plugins específicos del proyecto
└── assets/
    ├── fonts/
    └── images/
```

---

## Características

- ✅ Desarrollo 100% con editor nativo de bloques — sin Elementor, sin Divi
- ✅ Web bilingüe ES/EN
- ✅ Diseño responsive (mobile, tablet, desktop)
- ✅ Optimización de rendimiento (WPO)
- ✅ Accesibilidad WCAG 2.1 AA
- ✅ Semántica HTML correcta
- ✅ Formulario de contacto funcional
- ✅ SSL + copias de seguridad configuradas
- ✅ Panel de administración adaptado para autogestión

---

## Cómo trabajar con este repo

### Requisitos

- PHP 8.x
- WordPress 6.x
- MySQL 10.x

### Instalación local

```bash
# Clona el repositorio
git clone https://github.com/torreznoestudio/coherent-research.git

# Copia el tema a tu instalación de WordPress
cp -r theme/ /ruta/a/wordpress/wp-content/themes/coherent-research

# Activa el tema desde el panel de WordPress
# Administración → Apariencia → Temas
```

### Variables de entorno

Copia `.env.example` a `.env` y ajusta los valores de tu entorno local.

---

## Plugins incluidos

| Plugin | Uso |
|--------|-----|
| Rank Math SEO | Optimización SEO |
| Contact Form 7 | Formulario de contacto |
| WP Rocket | Caché y rendimiento |
| UpdraftPlus | Copias de seguridad |
| All In One WP Security | Seguridad |
| Kadence Blocks | Bloques adicionales |

---

## Autogestión para la clienta

El panel de WordPress está configurado para que puedas gestionar el contenido de forma autónoma:

- ✏️ Editar textos e imágenes de cualquier página
- 🌐 Cambiar entre versión ES y EN
- 📬 Ver los mensajes del formulario de contacto
- 🔒 Sin acceso a ajustes técnicos que puedan romper la web

> Consulta el **tutorial en vídeo** incluido en la entrega para ver cómo actualizar cada sección.

---

## Contacto y soporte

Para cualquier incidencia técnica o consulta sobre el proyecto:

**Torrezno Estudio**
📧 hola@torreznoestudio.com
🌐 [torreznoestudio.com](https://torreznoestudio.com)

---

*Desarrollado con cariño y sin page builders.* 🌱
