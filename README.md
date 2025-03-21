# scop

## todo

- https://vulkan-tutorial.com/ in ash
- remove `VulkanApp`, functions are fine
- no more `utility` mod
- refactorrrrrrrrrrrrr
- update dependencies
- parse `.obj` files myself
- remove non-ash/winit dependencies
- finish scop
- add bonuses (125)
- validation layers only in debug mode

## bonus

- [ ] correct management of ambiguous `.obj` files
- [ ] more subtle application of the texture
- [ ] backface culling
- [ ] phong model
- [ ] platonic solid objects
- [ ] light objects
- [ ] wgpu alternative
- [ ] cpu alternative

## notes

- rm `WINDOW_TITLE`

```rust
mod utility;

use utility::constants::*;
```