# OnionCrafter.Dto.Base

![Versión de la librería](https://img.shields.io/badge/Versi%C3%B3n-1.0.0-brightgreen) [![NuGet](https://img.shields.io/nuget/v/OnionCrafter.Dto.Base.svg)](https://www.nuget.org/packages/OnionCrafter.Dto.Base/)

![](https://raw.githubusercontent.com/Dtopiast/OnionCrafter.Util.Object/main/Images/Logo.png)

**Estado de la Librería: Pre-Alfa - No Listo para Producción**

Esta librería se encuentra actualmente en un estado pre-alfa, lo que significa que está en una fase muy temprana de desarrollo y no está destinada para su uso en entornos de producción. Estamos trabajando arduamente para mejorar y estabilizar la librería, pero aún pueden existir errores y limitaciones significativas.

Si estás interesado en utilizar esta librería, te recomendamos encarecidamente que la pruebes en un entorno de desarrollo o pruebas para evaluar su idoneidad para tu proyecto. No se garantiza la estabilidad ni la compatibilidad con versiones futuras en este estado inicial.

Por favor, mantente atento a futuras actualizaciones y anuncios sobre el progreso de la librería. Tu retroalimentación y contribuciones son bienvenidas a medida que avanzamos hacia una versión más estable y lista para producción.

## Descripción

OnionCrafter.Dto.Base es una biblioteca ligera diseñada para facilitar la creación de objetos de Transferencia de Datos (DTO) en proyectos desarrollados con .NET 7. Ofrece clases y interfaces abstractas que sirven como base para definir y estructurar DTOs utilizados en diversas capas de la aplicación.

## Características

- Proporciona una base sólida para la creación de objetos DTO en proyectos .NET 7.
- Facilita la organización y estructura de los DTOs utilizados en diferentes capas de la aplicación.
- Ayuda a reducir la duplicación de código al definir propiedades y métodos comunes en las clases base y las interfaces.

## Requisitos

- .NET 7

## Instalación

Puedes agregar esta librería a tu proyecto .NET 7 a través de NuGet. Usa el siguiente comando de NuGet para instalarla:

```bash
dotnet add package OnionCrafter.Dto.Base
```

## Uso

Para comenzar a utilizar OnionCrafter.Dto.Base en tu proyecto:

1. Agrega la referencia a esta biblioteca en tu proyecto .NET 7.
2. Extiende las clases base o implementa las interfaces proporcionadas para definir tus propios DTOs.
3. Personaliza y agrega propiedades y métodos específicos a tus DTOs según tus necesidades.

```csharp
// Ejemplo de uso de una clase DTO que hereda de BaseDto
public class MiDto : BaseDto
{
    public string Nombre { get; set; }
    public int Edad { get; set; }
}
```

Para obtener ejemplos detallados sobre cómo utilizar esta librería, consulta la [documentación](https://github.com/Dtopiast/OnionCrafter.Dto.Base/wiki).

## Contribuir

Si deseas contribuir a esta librería, ¡te damos la bienvenida! Puedes hacerlo de las siguientes maneras:

1. **Informa problemas:** Si encuentras algún problema o error, por favor, abre un [issue](https://github.com/dtopiast/OnionCrafter.Dto.Base/issues).

2. **Envía Pull Requests:** Si deseas agregar nuevas características o corregir errores existentes, no dudes en enviar un [pull request](https://github.com/dtopiast/OnionCrafter.Dto.Base/pulls).

## Licencia

Este proyecto está bajo la [Licencia Mozilla Public v. 2](LICENSE.txt). Consulta el archivo LICENSE.txt para obtener más información.
