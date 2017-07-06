# Week 5 - 03. Architectural Patterns

## Learning goals

1. Understand the comcept of architectural patterns and how to apply them during system design
2. Apply the Layer pattern
3. Understand the Client-Dispatcher-Server pattern
4. Unserstand the MVC architectural style

## Architecture is an Art
Inventing a novel architecture is a highly creative act

**Requires:**

* Knowledge of existing work
* Experience

## Architectural Styles for Buildings

![Imagem01](./assets/03/image01.png)

* Style defines main components/layout
* Architect picks an architectural style based on customer requirements
* Architect changes details according to customer requirements
    * Enables reuse of established engineering knowledge

> We apply the same approach to software architecture

## Terminology: Architectural Pattern vs. Architectural Style
Buschmann and his colleagues see the following differences between these terms

* Architectural styles only describe the overall structural frameworks for applications
* Architectural patterns define the basic structure of an applications
* Architectural styles are independent from each other, a pattern dependes on smaller patterns
* Patterns are more problem oriented than architectural styles

We use the terms interchangeably

* **Architectural Style = Architectural Pattern**: A pattern for a subsystem decomposition
* **Software Architecture**: Instance of an architectural style (architectural pattern)