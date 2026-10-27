# Proyecto: Bitácora Web ADSO - Fase de Transferencia

## 1. Descripción del Proyecto
Este proyecto consiste en la transformación de la bitácora de seguimiento (originalmente en formato Excel) a un producto web interactivo. El objetivo principal es aplicar HTML puro bajo estándares de semántica web y accesibilidad universal (a11y), garantizando que cualquier usuario pueda navegar y comprender la información de manera clara y estructurada.

## 2. Estructura de las Vistas
El proyecto está compuesto por tres vistas HTML totalmente independientes, las cuales están interconectadas mediante un menú de navegación funcional (`<nav>`):

*   **`informacion.html`**: Vista que contiene los datos generales del aprendiz, el programa de formación, la competencia y el periodo correspondiente a la bitácora.
*   **`reglas.html`**: Vista que detalla las reglas de negocio, la guía de llenado por columna y los principios de redacción técnica para el diligenciamiento correcto de la bitácora.
*   **`trazabilidad.html`**: Vista principal que contiene la tabla de trazabilidad con los registros de las actividades diarias, impedimentos y planes de acción, representados de forma estructurada.

## 3. Prácticas Semánticas y de Accesibilidad Implementadas
Para garantizar la calidad técnica del código, se implementaron las siguientes prácticas:

**Semántica HTML:**
*   Estructura base correcta en cada archivo (`<!DOCTYPE html>`, `<html lang="es">`, `<head>`, `<meta charset="UTF-8">`, `<title>`, `<body>`).
*   Uso de etiquetas estructurales como `<header>`, `<nav>`, `<main>`, y `<footer>` para organizar lógicamente el contenido.
*   Uso de tablas (`<table>`, `<thead>`, `<tbody>`, `<th>`, `<td>`) para representar la información tabular de la bitácora de manera estructurada.
*   Jerarquización correcta de títulos (`<h1>`, `<h2>`, `<h3>`) sin saltos de nivel.

**Accesibilidad (a11y):**
*   **Navegación:** El menú de navegación (`<nav>`) cuenta con enlaces claros que permiten moverse entre las tres vistas sin necesidad de usar el botón de retroceso del navegador.
*   **Enlaces:** Los enlaces cuentan con texto descriptivo que indica claramente su destino.
*   **Estructura:** La información está organizada de manera que los lectores de pantalla pueden seguir un flujo lógico de lectura.