# Unity Advanced FPS Movement Controller

A polished and customizable first-person movement controller built with Unity's `CharacterController`.

This project provides smooth, responsive FPS movement while remaining lightweight, easy to understand, and simple to customize for your own games.

## Features

* 🎮 Smooth WASD movement
* 🖱️ First-person mouse look
* 🏃 Sprinting
* 🦘 Jumping
* ☁️ Air control
* ⏱️ Coyote time
* 🎯 Jump buffering
* 📉 Variable jump height
* 🌍 Configurable gravity
* 🚀 Terminal velocity
* ⛰️ Improved slope handling
* 🔒 Escape key cursor lock/unlock toggle
* ⚙️ Fully customizable through the Unity Inspector

## Requirements

* Unity 2021.3 LTS or newer
* Uses Unity's built-in **CharacterController**
* Uses the legacy **Input Manager**

## Installation

1. Clone or download this repository.
2. Copy `PlayerMovement.cs` into your project's `Assets/Scripts` folder.
3. Create a GameObject for your player.
4. Add a **CharacterController** component.
5. Attach the `PlayerMovement` script.
6. Create or assign a Camera as a child of the player.
7. Drag the camera into the **Player Camera** field in the Inspector (or leave it empty to automatically use `Camera.main`).

## Controls

| Action             | Key               |
| ------------------ | ----------------- |
| Move               | WASD / Arrow Keys |
| Look Around        | Mouse             |
| Sprint             | Left Shift        |
| Jump               | Space             |
| Toggle Cursor Lock | Escape            |

## Inspector Settings

Most gameplay values can be adjusted directly from the Inspector, including:

* Walk Speed
* Sprint Speed
* Mouse Sensitivity
* Gravity
* Jump Height
* Air Control
* Ground Acceleration
* Ground Deceleration
* Coyote Time
* Jump Buffer Time
* Terminal Velocity
* Look Limits

This makes it easy to tune the controller for arcade, realistic, or fast-paced movement.

## CharacterController Recommendations

For best results:

* **Slope Limit:** 45–55°
* **Step Offset:** ~0.3
* **Skin Width:** ~0.08

These values may vary depending on your game.

## Customization

This controller is intended to be a solid starting point for your own projects.

Possible additions include:

* Crouching
* Sliding
* Head bobbing
* Footstep audio
* Leaning
* Stamina system
* Wall running
* Mantling
* Swimming
* Multiplayer support
* New Unity Input System support

## License

This project is released under the MIT License.

You are free to use, modify, and distribute it in both personal and commercial projects.

## Contributing

Contributions, suggestions, and bug reports are welcome.

If you have improvements or new features, feel free to open an issue or submit a pull request.

---

If you find this project useful, consider giving it a ⭐ on GitHub!
