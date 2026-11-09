# Pruebas unitarias · C# y .NET

**Ejemplos de pruebas sobre operaciones de cadenas y una abstracción de lectura de archivos.**

[![Repositorio](https://img.shields.io/badge/GitHub-GermanBartoli-181717?logo=github)](https://github.com/GermanBartoli/Unit-Testing-CSharp-.NET)

[Empezar](#primeros-pasos) · [Mapa del repositorio](#mapa-del-repositorio) · [Autoría](#autoría-de-esta-documentación)

![Guía visual: Pruebas unitarias · C# y .NET](docs/readme/guia.svg)

*Esquema de orientación; no representa una captura de la aplicación.*

## Primeros pasos

1. Leé `StringManipulation/StringOperations.cs` y su contrato de lectura.
2. Compará los casos de `StringManipulation.Tests/` con las operaciones que verifican.
3. Ejecutá `dotnet test StringManipulation.Tests/StringManipulation.Tests.csproj` con un entorno compatible con `net7.0`.

## Entorno de aprendizaje

Este repositorio conserva ejercicios y versiones de su etapa de estudio. Revisá los archivos de proyecto para preparar el SDK, runtime o servidor correspondiente; esta actualización del README no migra dependencias ni acredita una ejecución reciente de todos los ejemplos.

## Referencia y detalles

https://github.com/platzi/curso-unit-testing-csharp

## Mapa del repositorio

- [StringManipulation.Tests/StringManipulation.Tests.csproj](<StringManipulation.Tests/StringManipulation.Tests.csproj>)
- [StringManipulation/StringManipulation.csproj](<StringManipulation/StringManipulation.csproj>)
- [StringManipulation/StringManipulation.sln](<StringManipulation/StringManipulation.sln>)
- [StringManipulation/Program.cs](<StringManipulation/Program.cs>)

## Autoría de esta documentación

Repositorio mantenido por [Germán Bartoli](https://github.com/GermanBartoli). Guía revisada y actualizada con **Codex**, coautor de esta actualización documental. Los autores, colaboradores, licencias y recursos de terceros conservan sus créditos originales.

Los commits de esta revisión incluyen `Co-authored-by: Codex <noreply@openai.com>`; esta atribución no modifica la autoría del historial anterior.
