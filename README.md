# SDL Boilerplate

A batteries-included SDL-based cross-platform video game boilerplate.

## Various Notes

- 64-bit Release build
- Included libraries:
	1. Lua
	2. SDL TTF
	3. SDL Image
	4. SDL 2.0
- Can be distributed to end users (all parts included)
- If using dynamic libraries, they must be included in the application bundle
- CLI-based editing
- Possible Box2D integration (low priority)
- Possible domain name at [sdlbp.com][domain]

## Useful Videos

1. ["Game Development with SDL"][video1]
2. ["Open Source Tools for Game Development"][video2]

## Static vs. Dynamic Linking

| Type    | Pros         | Cons                         |
|:--------|:-------------|:-----------------------------|
| Static  | Easier to distribute | Not future-proof     |
| Dynamic | Future-proof | Harder w/ iOS and Android support? |

## Functionality

1. Launch the application
2. Presented with image from sprite sheet
3. Sprite is animated
4. Tapping on the screen relocates the character
5. `main.lua` runs at initialization (code is Lua-driven)

## Target Platforms

- iOS
- Android
- Windows
- OS X
- Linux

## (Possible) Structure

```
- libraries/  # Statically-linked libraries
- platforms/  # Platform-dependent code
- source/     # Platform-independent code
- scripts/    # Scripts
- assets/     # Static assets
  - images/   # Image resources
  - fonts/    # Font resources
  - audio/    # Audio resources
```

[domain]: https://domai.nr/sdlbp/with/sdlbp.com "Possible domain name"
[video1]: https://www.youtube.com/watch?v=MeMPCSqQ-34 "Game Development with SDL"
[video2]: https://www.youtube.com/watch?v=MeMPCSqQ-34 "Open Source Tools for Game Development"