
# Haptic Drift

Haptic Drift is a browser-based endless racing game built with HTML, CSS, and JavaScript. The project explores how haptic feedback can make mobile web games feel more immersive by turning vibrations into an active part of the driving experience instead of simple collision effects.

The game is designed to run directly in the browser with no installation required.

## Features

* Endless procedurally generated roads
* Responsive driving physics with drifting mechanics
* Dynamic haptic feedback based on gameplay
* Mobile and desktop controls
* Collision detection
* Dynamic sound generation
* Optimized browser performance

## Haptic Feedback

Rather than only vibrating during crashes, Haptic Drift uses different vibration patterns for different driving situations.

Current haptic events include:

* High-speed driving
* Drifting
* Braking
* Collisions
* Nitro boosts
* Speed changes

Support varies depending on browser and operating system.

Android browsers currently provide the best experience, while iOS support is still being tested due to browser limitations.

## Technologies

* HTML5
* CSS3
* JavaScript
* Web Audio API
* Vibration API

## Controls

### Desktop

* W / Up Arrow – Accelerate
* S / Down Arrow – Brake
* A / Left Arrow – Turn Left
* D / Right Arrow – Turn Right

### Mobile

* Touch controls
* Device vibration (supported browsers)

## Project Goals

The goal of Haptic Drift is to explore how modern browser APIs can create a more immersive racing experience without requiring a game engine or native mobile application.

Future development includes:

* Additional environments
* More road variety
* Improved visual effects
* Better mobile UI
* Enhanced sound design
* New gameplay mechanics
* Expanded haptic effects

## Development

Clone the repository:

```bash
git clone https://github.com/your-username/haptic-drift.git
```

Open the project folder and serve it with any local web server.

Examples:

```bash
python -m http.server
```

or

```bash
npx serve
```

Then open the displayed local address in your browser.

## Browser Support

| Browser          | Status                    |
| ---------------- | ------------------------- |
| Chrome (Android) | Fully supported           |
| Edge             | Supported                 |
| Chrome (Desktop) | Supported                 |
| Safari (iOS)     | Partial haptic support    |
| Firefox          | Limited vibration support |

## Contributing

Suggestions, bug reports, and pull requests are welcome.

## License

This project is released under the MIT License.

You can also add screenshots or a gameplay GIF at the top later, which makes game repositories much more appealing to visitors.
