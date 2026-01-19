# 📚 BRG-05: Borges - Agente Curador de Zettelkasten

![Version](https://img.shields.io/badge/version-3.1-blue) ![Role](https://img.shields.io/badge/role-Curador%20%7C%20Sparring%20Partner-BC955C) ![System](https://img.shields.io/badge/system-Obsidian%20Zettelkasten-235B4E)

> *"Uno no es lo que es por lo que escribe, sino por lo que ha leído (y conectado)."* — Adaptación libre de J.L. Borges.

## 📖 Descripción

Este repositorio contiene el código fuente de configuración (JSON) y los protocolos operativos de **Borges (BRG-05)**, un Agente de Inteligencia Artificial personalizado diseñado para asistir a **Víctor Faccio** en la gestión, curaduría y expansión de su Zettelkasten en Obsidian.

Borges no es un simple asistente pasivo; es un **"sparring partner" intelectual**. Su arquitectura está diseñada para entender la filosofía del *sentipensamiento*, priorizar la calidad de las conexiones sobre la cantidad, y facilitar el flujo de trabajo entre la lectura académica, la docencia y la investigación sociológica.

## 🧠 Núcleo del Sistema (JSON) v3.1

El archivo principal `borges_config.json` actúa como el *System Prompt* maestro. Define:

* **Personalidad:** Un bibliotecario pragmático, eficiente y entusiasta ("geek" académico), que evita la sumisión y fomenta la camaradería intelectual.
* **Modos Operativos:**
    * 🛠 **Modo Microcirugía:** Procesamiento de notas crudas a notas atómicas permanentes.
    * 🗺️ **Modo Estructura (Nuevo):** Generación de Mapas de Contenido (MOCs) para sintetizar clusters de notas.
    * 🔗 **Modo Análisis:** "Conversación" entre notas para artículos o clases.
* **Formatos de Salida:** * Plantillas estrictas de Markdown.
    * YAML Frontmatter optimizado (Tags limpios sin `#` para compatibilidad con Dataview).
* **Ecosistema:** Comprensión de su relación con otros agentes del sistema Faccio (Rosario, Ariadna, Caspian).

## 📂 Estructura del Repositorio

```text
.
├── borges_config.json       # 🧠 Código fuente del agente (v3.1 - System Prompt completo)
├── docs/                    # 📄 Documentación de soporte
│   ├── guia_zettel.md       # Guía de creación y sintaxis de notas
│   ├── codigo_identidad.md  # Ficha de identidad y misión de BRG-05
│   └── plan_trabajo.md      # Metodología de colaboración Humano-IA
└── README.md                # 📍 Este archivo
