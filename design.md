---
name: portfolio-de-[nombre]
colors:
  primary: "#1A1C1E"          # tu color principal (oscuro)
  accent: "#E63946"           # tu acento (un único color llamativo)
  background: "#F8F9FA"       # fondo casi blanco
  text: "#1A1C1E"             # texto principal
  muted: "#6C757D"            # texto secundario / pies de foto
typography:
  heading:
    fontFamily: "Space Grotesk, sans-serif"
    fontSize: "2.5rem"
    fontWeight: 700
    lineHeight: 1.1
  body:
    fontFamily: "Inter, sans-serif"
    fontSize: "1rem"
    lineHeight: 1.6
spacing:
  xs: "4px"
  sm: "8px"
  md: "16px"
  lg: "32px"
  xl: "64px"
---

## Overview

Portfolio personal de [nombre], estudiante de 1º GM. Tono: **minimalista, técnico, sin
ruido visual**. La página tiene que sentirse limpia y rápida.

## Colors

La paleta es deliberadamente sobria: un fondo casi blanco, un texto profundo y un
**único** acento para llamadas a la acción y enlaces destacados. Si dudas si añadir un
color nuevo, no lo hagas.

## Typography

- Heading: `Space Grotesk` — sans serif geométrico, da personalidad sin estridencias.
- Body: `Inter` — humanista, legible en párrafos largos.
- Sin más familias. Sin cursivas decorativas.

## Layout

Mobile-first. Una sola columna por defecto; a partir de 768px puede haber dos.
Anchura máxima del contenido: 720px.

## Do's and Don'ts

- ✅ Usa siempre `{spacing.md}` o múltiplos como gap base.
- ✅ Bordes sutiles (`1px solid {colors.muted}`) en lugar de sombras.
- ❌ Nada de degradados.
- ❌ Nada de sombras blandas.
- ❌ Nada de iconos ornamentales.
