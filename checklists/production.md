# Low-bandwidth production checklist

## Network resilience
- [ ] Test on throttled mobile networks and during full disconnection.
- [ ] Show meaningful loading, timeout, and retry states.
- [ ] Make writes idempotent or deduplicate repeated submissions server-side.
- [ ] Define which pages and data can be cached safely.

## Data and devices
- [ ] Compress and size images appropriately.
- [ ] Test on a representative low-end phone.
- [ ] Track JavaScript transferred and main-thread execution time.
- [ ] Avoid assuming storage is unlimited or persistent.

## User trust
- [ ] Explain whether a form is saved locally or submitted to the server.
- [ ] Make recovery and deletion of drafts understandable.
- [ ] Do not store sensitive data without a threat model.
- [ ] Measure real-world user experience where possible.
