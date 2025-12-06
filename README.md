actualización 06/12/25
📢 Actualización del Proyecto – Resumen General de Progreso

Desde la última versión del README, Yuuki evolucionó mucho más allá de su idea original. Lo que comenzó como un simple bot para tareas ahora es un framework modular y extensible, construido alrededor de un núcleo sólido y plugins que expanden sus capacidades.
Esta actualización resume todos los avances, decisiones de diseño y nueva dirección del proyecto.


🚀 1. Cambio de Identidad del Proyecto

Yuuki dejó de ser “un bot” para convertirse en un framework + core capaz de ejecutar cualquier funcionalidad mediante plugins.
El bot ya no es el producto principal: ahora es solo un plugin más.

Concepto actual:

El core es la base.

Los plugins son el alma.

Los usuarios construyen encima de Yuuki, no desde cero.


🧩 2. Evolución del Sistema de Plugins

El sistema de plugins maduró bastante:

Los plugins se ejecutarán en procesos aislados para mayor seguridad.

El core monitoreará comportamientos anómalos.

Soporte para múltiples integraciones (Discord, Reddit, Telegram, VC, etc.).

Plan a futuro para una tienda de plugins.

Ideas ya previstas:

Plugin de TTS con voces de anime y videojuegos.

Plugins de audio en canales de voz.

Sistema de reputación y anti-abuso para servidores.


🛡️ 3. Seguridad y Prevención de Abusos

Se discutieron posibles riesgos y cómo evitarlos:

Modo seguro integrado en el core de servidores.

Detección de patrones peligrosos (raids, spam, abuso de API, etc.).

Prevención contra:

plugins espía

grabación no autorizada

automatizaciones maliciosas


Sistema de firmas digitales (planeado para la v1.0).

Actualizaciones desde fuentes confiables.


🧠 4. Lenguaje y Scripting

Se exploraron varias rutas:

QuickJS como módulo opcional.

Posibilidad de un lenguaje embebido propio, escrito en Go:

sintaxis simple

pensado para crear plugins fácilmente

enfocado en principiantes y avanzados



No estará en la v0.1, pero sí en la ruta hacia la v1.0 estable.


📦 5. Nueva Extensión: .yuu

Se definió un formato propio:

.yuu servirá para empaquetar configuraciones, scripts o metadata.

El core solo necesita un lector/parsers dedicado.


🎨 6. Identidad Visual y Materiales Físicos

Progreso creativo notable:

Libreta organizada en secciones para cada parte del proyecto.

Cada sección tiene su propio estilo visual y tipografía.

Separadores personalizados para mantener el orden.

Concept art inicial del rostro de Yuuki.


📚 7. Lore de Yuuki

Se desarrolló una base narrativa (opcional, no técnica):

Origen trágico y sobrenatural.

Pacto que le permite “absorber habilidades”, reflejando el concepto de plugins.

Universo habitado por entidades divinas y demoníacas.


El lore está en fase alpha, pero ya tiene fuerza suficiente como narrativa principal.


🎤 8. Voz, Identidad y Funciones de Audio

Se consideró darle una voz predeterminada mediante TTS.

Plugins capaces de hablar en VC.

Voces estilo anime como parte de la experiencia.

Plan para un plugin oficial de TTS.


🧱 9. Arquitectura del Sistema

Nueva estructura definida:

Core de Usuario

Core de Servidor

Módulo opcional basado en QuickJS

Mayor separación entre responsabilidades.

🗺️ 10. Progreso en el Roadmap

Alpha (0.1) – objetivo actual

Core funcional

Sistema básico de plugins

Documentación mínima

Sin firmas digitales aún

Sin lenguaje embebido


Futuro (0.5–1.0)

Lenguaje propio

Plugin TTS

Aislamiento de plugins

Tienda de plugins

Sistema de firmas

API estable


💬 11. Comunidad e Ideas

El proyecto ahora acepta:

Ideas nuevas

Propuestas de funcionalidades

Conceptos de plugins

Comentarios técnicos

Contribuciones creativas


Basado en el lema:
“Tus ideas, tu Yuuki.”


🌱 12. Notas del Desarrollador

El desarrollo sigue siendo individual, pero con mucha dedicación.
El proyecto se convirtió en algo mucho más grande que un simple bot: ahora mezcla tecnología, creatividad, narrativa y diseño.
Y se está construyendo con visión a largo plazo, sin importar cuánto tiempo tome.


🧡 13. Nota del Desarrollador sobre la Versión Alpha 0.1

El desarrollador lamenta no poder publicar todavía una versión alpha 0.1.
Yuuki ha crecido mucho más de lo que se planeó al inicio y, al ser un proyecto amplio, ambicioso y construido completamente por una sola persona, requiere más tiempo del esperado para alcanzar un mínimo de estabilidad.

El objetivo es que la alpha 0.1 no sea solo una demostración, sino una base funcional, clara y confiable para que cualquiera pueda empezar a crear con Yuuki desde el primer día.

A pesar de las dificultades, el compromiso sigue firme:
haré todo lo posible para que la primera versión usable llegue pronto y sea totalmente gratuita, sin métodos de pago ahora ni en el futuro.
Yuuki será siempre open source, accesible y abierta a la comunidad.

Si deseas apoyar el proyecto, puedes dejar ideas, recomendaciones o sugerencias. Cada comentario ayuda a que Yuuki crezca y mejore.

update 12/06/25


📢 Project Update – General Progress Overview

Since the last version of the README, Yuuki has evolved far beyond its original idea. What started as a simple task bot has now become a modular, extensible framework built around a solid core and plugin architecture.
This update summarizes all progress, design decisions, and the new direction of the project.


🚀 1. Project Identity Shift

Yuuki is no longer “a bot.”
It has transformed into a framework + core, capable of running any functionality through plugins.
The bot is no longer the main product — it’s now just another plugin.

Current concept:

The core is the foundation.

The plugins are the soul.

Users build on top of Yuuki, not from scratch.


🧩 2. Evolution of the Plugin System

The plugin system has matured significantly:

Plugins will run in isolated processes for greater safety.

The core will monitor anomalous behavior.

Support for multiple integrations (Discord, Reddit, Telegram, VC, etc.).

Future plan for a plugin marketplace.


Features already envisioned:

TTS plugin with anime and videogame voices.

Audio plugins for voice channels.

Reputation and anti-abuse system for servers.


🛡️ 3. Safety and Abuse Prevention

We discussed possible risks and how to avoid them:

Built-in Safe Mode for server cores.

Detection of dangerous behavior patterns (raids, spam, API abuse).

Protection against:

Spy plugins

Unauthorized recording

Malicious automation


Digital signature system (planned for v1.0).

Updates only from verified sources.


🧠 4. Language & Scripting

Several paths were explored:

QuickJS as an optional module.

Possibility of creating a custom embedded language written in Go:

Simple syntax

Designed for easy plugin creation

Suitable for beginners and advanced users



It won’t be in v0.1, but it is planned for the stable v1.0 path.


📦 5. New Extension: .yuu

A custom format was defined:

.yuu will store configurations, scripts, or metadata.

The core will only require a dedicated parser/loader.


🎨 6. Visual Identity & Physical Materials

Creative progress has been strong:

Notebook organized into structured sections for each part of the project.

Every section has its own visual style and typography.

Custom dividers to keep everything organized.

Initial concept art for Yuuki’s face.


📚 7. Yuuki’s Lore

A narrative foundation has been developed (optional, non-technical):

Tragic and supernatural origin.

A pact that lets her “absorb abilities,” mirroring the plugin system.

A universe filled with divine and demonic entities.


The lore is in early alpha, but already strong enough to serve as the main narrative.


🎤 8. Voice, Identity, and Audio Features

We explored giving Yuuki a default voice through TTS:

Plugins that can speak in voice channels.

Anime-style voices as part of the experience.

Plan for an official TTS plugin.


🧱 9. System Architecture

New structure defined:

User Core

Server Core

Optional QuickJS module

Stronger separation of responsibilities.


🗺️ 10. Roadmap Progress

Alpha (0.1) – current goal

Functional core

Basic plugin system

Minimal documentation

No digital signatures yet

No embedded language (yet)


Future (0.5–1.0)

Custom language

TTS plugin

Plugin isolation

Plugin marketplace

Signature system

Stable API


💬 11. Community & Ideas

The project now welcomes:

New ideas

Feature proposals

Plugin concepts

Technical feedback

Creative contributions


Based on the motto:
“Your ideas, your Yuuki.”


🌱 12. Developer Notes

Development is still carried out by a single person, but with strong dedication.
The project has grown far beyond a simple bot — it now blends technology, storytelling, creativity, and design.
And it’s being built with a long-term vision, no matter how long it takes.


🧡 13. Developer Note on the Alpha 0.1 Release

The developer apologizes for not being able to release version alpha 0.1 yet.
Yuuki has grown far beyond its initial scope, and being a broad, ambitious project built entirely by one person, it requires more time to reach a stable foundation.

The goal is for alpha 0.1 not to be just a demo, but a functional, clear, and reliable base so anyone can start creating with Yuuki from day one.

Despite the difficulties, the commitment remains firm:
I will do everything possible to deliver the first usable version soon, fully free, with no payment or monetization methods now or in the future.
Yuuki will always be open source, accessible, and community-driven.

If you want to support the project, you can leave ideas, recommendations, or suggestions.
Every comment helps Yuuki grow and improve.
