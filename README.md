# cuda-filtration

Intelligence filtration — extract insights from agent deliberation streams in real-time

Part of the Cocapn fleet — a Lucineer vessel component.

## What It Does

### Key Types

- `FilterRule` — core data structure
- `FilterResult` — core data structure
- `FilterHit` — core data structure
- `FiltrationEngine` — core data structure
- `FiltrationStats` — core data structure
- `ResourceBudget` — core data structure
- _and 2 more (see source)_

## Quick Start

```bash
# Clone
git clone https://github.com/Lucineer/cuda-filtration.git
cd cuda-filtration

# Build
cargo build

# Run tests
cargo test
```

## Usage

```rust
use cuda_filtration::*;

// See src/lib.rs for full API
// 12 unit tests included
```

### Available Implementations

- `FilterRule` — see source for methods
- `FiltrationEngine` — see source for methods
- `Default for FiltrationEngine` — see source for methods
- `FiltrationStats` — see source for methods
- `ResourceBudget` — see source for methods
- `BudgetTiers` — see source for methods

## Testing

```bash
cargo test
```

12 unit tests covering core functionality.

## Architecture

This crate is part of the **Cocapn Fleet** — a git-native multi-agent ecosystem.

- **Category**: other
- **Language**: Rust
- **Dependencies**: See `Cargo.toml`
- **Status**: Active development

## Related Crates


## Fleet Position

```
Casey (Captain)
├── JetsonClaw1 (Lucineer realm — hardware, low-level systems, fleet infrastructure)
├── Oracle1 (SuperInstance — lighthouse, architecture, consensus)
└── Babel (SuperInstance — multilingual scout)
```

## Contributing

This is a fleet vessel component. Fork it, improve it, push a bottle to `message-in-a-bottle/for-jetsonclaw1/`.

## License

MIT

---

*Built by JetsonClaw1 — part of the Cocapn fleet*
*See [cocapn-fleet-readme](https://github.com/Lucineer/cocapn-fleet-readme) for the full fleet roadmap*
