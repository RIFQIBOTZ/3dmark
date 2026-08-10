<h1 align="center">3DMark Lab</h1>

<p align="center">
  <b>Benchmark archive for performance results, screenshots, and test assets.</b><br>
  A clean place to keep 3DMark records organized and easy to inspect.
</p>

<p align="center">
  <img alt="status" src="https://img.shields.io/badge/status-active-0ea5e9?style=for-the-badge">
  <img alt="license" src="https://img.shields.io/badge/license-MIT-22c55e?style=for-the-badge">
  <img alt="type" src="https://img.shields.io/badge/type-benchmark%20archive-8b5cf6?style=for-the-badge">
</p>

---

## About

**3DMark Lab** is a lightweight archive for collecting 3DMark benchmark screenshots, results, and supporting visual assets.

It is intentionally simple: no framework, no build process, and no unnecessary project overhead. Just organized benchmark material that can be opened and reviewed quickly.

## At a glance

| Category | Details |
|---|---|
| Purpose | 3DMark benchmark archive |
| Assets | Screenshots & test images |
| Structure | Minimal and organized |
| Workflow | Add → label → archive → compare |
| Stack | Static repository |

## Repository structure

```text
3dmark/
├── images/         # Benchmark screenshots & visual assets
└── README.md       # Project documentation
```

## Naming convention

Use filenames that tell you what the image contains without opening it.

```text
images/
├── device-name-test-01.png
├── device-name-test-02.png
├── benchmark-result.png
└── comparison-final.png
```

For larger collections, keep the same naming pattern across devices and test runs.

## Benchmark workflow

```text
Run benchmark
      ↓
Capture result
      ↓
Rename asset
      ↓
Store in /images
      ↓
Compare results
```

## Why keep an archive?

Benchmark results are useful when they can be compared over time. Keeping screenshots and records together makes it easier to spot changes after:

- driver updates
- system changes
- cooling changes
- configuration changes
- hardware changes

## Roadmap

- [x] Organized image archive
- [x] Simple repository structure
- [x] Descriptive asset naming
- [ ] Add benchmark metadata
- [ ] Add result tables
- [ ] Add historical comparisons

## License

MIT License

---

<p align="center">
  <sub>Benchmark data in. Clutter out.</sub>
</p>
