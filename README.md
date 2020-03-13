# :zap: zap
A simple and flexible toolkit for Unity.

## Install

Zap can be installed using the Unity Package Manager.

To begin, open your project in Unity and navigate to the Package Manager window. Click the `+` button to install a new package from a git URL. When prompted, paste the following URL:

    https://github.com/yosoi/zap-pkg.git

## Quick Start

Zap sports two modest but useful features: a modular **event system** and an extensible framework for **data objects**.

### Data Objects

Zap's data objects make it easy to share data between different systems.

To create a new data object, navigate to the `Project` window in Unity. There, you can `Right Click -> Create -> Zap -> Data` to select a new data object to create.

### Events

Using Zap's event system, different parts of your game can communicate with each-other cleanly and efficiently.

The event system is comprised of the `Event` object and the `EventRelay` component.

The `EventRelay` component can be created and managed like any other component in Unity. An `EventRelay` can subscribe to any number of `Event` objects.

`Event` objects can be created by navigating to Unity's `Project` window and doing `Right Click -> Create -> Zap -> Event`.

`Event` objects have a public `Trigger()` method and are commonly triggered via `UnityEvent`.
