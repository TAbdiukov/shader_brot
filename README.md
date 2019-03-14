# Fancy title
Thanks for your interest in this side-project of mine. If you would like to mentor me on how to improve the use of shaders, that would be **awesome**. It's still an early draft, and messy AF, but it will be cleaned up in the near future. 

If you have anything to offer as far as using Rust, or the `ggez` library, that would also be much appreciated.

### Installation and running
make sure you have the latest rust installed.

Assuming no curve-balls in the process, all you need to do to run this is to clone it, then `cargo run` in the project root directory. Any technical, TODO-list, or documentation suggestions to make this process easier for you is highly-welcomed.


## Controls
- Period to zoom in
- d to zoom out
- arrow-keys to move around
- q to quit, with the added bonus of `MainState` struct details printed to stdout

### What's going on?
At time of writing, it's a shader-powered mandelbrot-set renderer, with a per-frame refresh. My details

#### Hardware

- APU: Mesa DRI Intel(R) HD Graphics 520 (Skylake GT2) 
- CPU: Intel Core i5-6200U @ 4x 2.8GHz

#### Fractal details

- Iteration depth: 100
- Standard gpu precision
- glsl version 330 core
- resolution: appx. 1920x1080
- **FPS** easily 60.
- cpu usage: 20-25% CPU, with 50-75% on one core, the rest on other cores.



