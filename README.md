# Rive.Blazor.Wasm

A [Blazor](https://blazor.net/) component for [Rive](https://rive.app/) animations.

## Installation

Install the package from NuGet:

```shell
dotnet add package Rive.Blazor.Wasm
```

## Usage

Add the `RivePlayer` component to your Blazor component:

```html
<RivePlayer
	File="https://cdn.rive.app/animations/vehicles.riv"
	Width="400"
	Height="400"
	Autoplay="true"
	Artboard="Vehicles"
	StateMachines="vehicles"
/>
```

The `File` parameter is the URL of the Rive file to load.

The `Width` and `Height` parameters are the dimensions of the canvas.

The `Autoplay` parameter is a boolean that indicates whether the animation should start automatically.

The `Artboard` parameter is the name of the artboard to use.

The `StateMachines` parameter is the name of the state machine to use.

Other features are currently not supported. Passing additional parameters to the component will be forwarded to the
canvas element.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.md) file for details.
