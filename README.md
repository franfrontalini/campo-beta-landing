# Campo Beta — Landing

Landing page del programa **Campo Beta**: desafíos y prototipado con inteligencia artificial
para el sector agropecuario. Impulsado por UTN · FRC en vinculación con FAO, CREA y
organizaciones productivas (Córdoba Vincula 2026).

## Estructura

```
campo-beta-landing/
├── index.html          # Página principal (todas las secciones)
├── css/styles.css      # Estilos. Colores en variables CSS (:root)
├── js/main.js          # Menú móvil + placeholders de CTA
├── assets/
│   ├── logos/          # UTN, ANDÉN, FAO, CREA
│   └── img/            # Imágenes de apoyo
└── logos/              # Fuentes originales de los logos
```

## Secciones

Hero · Concepto · Fundamentación · Objetivos · Modalidad · Ejes de desafíos ·
Participantes · Recorrido de 8 semanas · Etapas del programa · Instituciones · Inscripción.

## Ver en local

Es un sitio estático, sin build. Basta con abrir `index.html`, o servirlo:

```bash
python3 -m http.server 8000
# http://localhost:8000
```

## Identidad visual (UTN FRC)

Sistema gráfico aplicado, centralizado en `:root` de `css/styles.css`.

**Paleta**

| Rol | Color |
| --- | --- |
| Azul UTN | `#1538B8` |
| Azul oscuro | `#0B2986` |
| Azul claro | `#D9E5F4` |
| Celeste | `#40C5F2` |
| Celeste oscuro | `#0A3F60` |
| Celeste claro | `#E2F6F9` |
| Negro | `#191919` |
| Gris | `#E5E5E5` |
| Fondo claro | `#FAFAFA` |

**Tipografías**

- **Noto Sans** — títulos
- **Barlow** — textos
- **JetBrains Mono** — cifras (métricas, resultados, semanas, etapas)
- **Crimson Pro** — citas (bloques destacados)

Estética institucional, técnica y limpia: grilla sutil en el hero (datos),
sin degradados llamativos ni animaciones. Para re-tematizar, editar solo las
variables de `:root`.

## Pendientes

- [ ] Conectar los CTA a un formulario de inscripción real.
- [ ] Sumar fichas de desafíos y (opcional) galería / equipos.
- [ ] Publicar (GitHub Pages).
