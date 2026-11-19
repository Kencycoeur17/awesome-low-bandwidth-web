# Offline-first patterns

Offline-first is a product requirement, not just a service worker. Decide which information remains available offline, how edits are persisted, and how conflicts are resolved.

- Cache only content suitable for the user's context and privacy requirements.
- Make submission status explicit: draft, queued, sent, confirmed, failed.
- Use server-side idempotency keys for important writes.
- Expect browser storage to be evicted and background execution to be unavailable.

References: [MDN Service Worker API](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API), [Workbox](https://developer.chrome.com/docs/workbox/).
