# Awesome Low-Bandwidth Web

A curated collection of resources for building fast, accessible, and resilient web applications on unreliable networks.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-blue.svg)](LICENSE)

Many users access the web through expensive data plans, unstable connections, and modest devices. This list focuses on **real-world constraints**: network interruptions, limited bandwidth, device performance, offline recovery, and data-safe synchronization.

## Contents

- [Performance fundamentals](#performance-fundamentals)
- [Network testing](#network-testing)
- [Offline-first and caching](#offline-first-and-caching)
- [Data-efficient interfaces](#data-efficient-interfaces)
- [Form recovery and synchronization](#form-recovery-and-synchronization)
- [Practical guides](#practical-guides)
- [Contributing](#contributing)

## Performance fundamentals

- [MDN Web performance](https://developer.mozilla.org/en-US/docs/Web/Performance) — Browser performance concepts and techniques.
- [web.dev Performance](https://web.dev/performance/) — Practical web performance learning materials.
- [Web Vitals](https://web.dev/articles/vitals) — User-centered performance metrics.
- [HTTP Archive](https://httparchive.org/) — Data on how the web is built and delivered.
- [The Web Almanac](https://almanac.httparchive.org/) — Annual research into web technology and performance.

## Network testing

- [Chrome DevTools](https://developer.chrome.com/docs/devtools/) — Network throttling and browser diagnostics.
- [Lighthouse](https://github.com/GoogleChrome/lighthouse) — Automated auditing for web experiences.
- [WebPageTest](https://www.webpagetest.org/) — Page-load testing across configurations.
- [Playwright](https://playwright.dev/) — Browser automation for end-to-end failure scenarios.
- [Network Information API](https://developer.mozilla.org/en-US/docs/Web/API/Network_Information_API) — Browser network information, with limited support.

## Offline-first and caching

- [MDN Service Worker API](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API) — Offline interception and caching fundamentals.
- [Workbox](https://developer.chrome.com/docs/workbox/) — Tools for service workers and caching.
- [Cache API](https://developer.mozilla.org/en-US/docs/Web/API/Cache) — Request and response storage.
- [IndexedDB](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API) — Structured client-side storage.
- [Storage API](https://developer.mozilla.org/en-US/docs/Web/API/Storage_API) — Storage persistence and quota concepts.
- [Background Synchronization API](https://developer.mozilla.org/en-US/docs/Web/API/Background_Synchronization_API) — Background sync with browser support caveats.

## Data-efficient interfaces

- [Learn Images](https://web.dev/learn/images/) — Efficient responsive images.
- [MDN Responsive images](https://developer.mozilla.org/en-US/docs/Web/HTML/Guides/Responsive_images) — Image sizing and selection.
- [Learn Performance](https://web.dev/learn/performance/) — Loading and runtime optimization.
- [MDN Lazy loading](https://developer.mozilla.org/en-US/docs/Web/Performance/Guides/Lazy_loading) — Defer nonessential resources.
- [MDN Compression](https://developer.mozilla.org/en-US/docs/Web/HTTP/Guides/Compression) — HTTP content compression.
- [MDN Resource hints](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes/rel/preload) — Preload critical resources thoughtfully.

## Form recovery and synchronization

- [MDN Window online event](https://developer.mozilla.org/en-US/docs/Web/API/Window/online_event) — Connectivity signal; not proof that a server is reachable.
- [MDN Window offline event](https://developer.mozilla.org/en-US/docs/Web/API/Window/offline_event) — Detect browser-reported disconnection.
- [MDN localStorage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage) — Simple storage with privacy and quota limitations.
- [TanStack Query](https://tanstack.com/query/latest) — Server-state management and mutation workflows.
- [Dexie.js](https://dexie.org/) — IndexedDB wrapper for client-side applications.

## Practical guides

- [Getting started](guides/getting-started.md)
- [Offline-first patterns](guides/offline-first.md)
- [Network testing](guides/network-testing.md)
- [Production checklist](checklists/production.md)

## Contributing

Useful additions include maintained tools, authoritative documentation, case studies with evidence, and reproducible examples. See [CONTRIBUTING.md](CONTRIBUTING.md). Please check for duplicates and keep descriptions neutral.

## Roadmap

- [x] Initial resource collection and practical guides
- [x] Submission template and automated link-check workflow
- [ ] Expand with verified case studies and accessibility references
- [ ] Add runnable demo applications
- [ ] Introduce community review and periodic link audits

## License

Original curated text is licensed under [CC BY 4.0](LICENSE). Linked projects and third-party material retain their own licenses.

Maintained by [Braintechken](https://github.com/Kencycoeur17).
