# TP N°2 — Lenguajes y Autómatas-Gramáticas-Ejercicios-Filmina 8

**Materia:** Técnicas de Procesamiento del Habla  
**Bloque:** Lenguajes y Autómatas  
**Unidad:** 1

## Descripción

Este trabajo práctico aborda gramáticas libres de contexto (GLC). A partir de una gramática G dada, se analizan sus componentes, se derivan cadenas del lenguaje L(G) y se evalúan proposiciones sobre derivaciones usando las relaciones ⇒ y ⇒*.

## Contenido

- Identificación de variables, terminales y símbolo inicial de G
- Derivación de cadenas pertenecientes a L(G)
- Determinación de la cadena mínima del lenguaje
- Evaluación de verdadero/falso sobre derivaciones en uno o más pasos
- Descripción del lenguaje generado por G
- Árbol de derivación para la cadena `aababa`

## Gramática analizada

```
R -> XRX | S
S -> aTb | bTa
T -> XTX | X | ε
X -> a | b
```

## Archivos

| Archivo | Descripción |
|---|---|
| `TP_2_Derivaciones_pdf.pdf` | Resolución completa del TP incluyendo árbol de derivación pertinente. |
