# Showtime

*Lifecycle management helpers for Wayland Web Components*

[![Hippocratic License HL3-CORE](https://img.shields.io/static/v1?label=Hippocratic%20License&message=HL3-CORE&labelColor=5e2751&color=bc8c3d)](https://firstdonoharm.dev/version/3/0/core.html)

Showtime provides tools for managing complex UI states related to visibility, transitions, and animations using reactive event streams.

## Installation

Use your favorite package manager:

```bash
npm install @dashkite/showtime
```

## Usage

Use `showtime` to coordinate visibility and inductor states.

```coffeescript
import { showtime } from "@dashkite/showtime"

# ... define your reactive stream
for await event from showtime(stream)
  # handle show/hide/modified events
```

## Status

Not suitable for production use. Please report any issues on the [GitHub repository](https://github.com/dashkite/showtime).
