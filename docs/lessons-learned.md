# Engineering Lessons

- Separate deterministic logic from engine orchestration. It improves testability and reduces dependence on manual editor inspection.
- Validate renderer outcomes independently. A good-looking frame can still hide topology or GPU-readback mistakes.
- Treat visual polish as part of acceptance. Functional correctness and shipped-quality presentation are different gates.
- Use configuration-driven validation. Repeatable poses and parameters make review more auditable.
- Keep evidence tied to exact delivered commits. This prevents documentation from drifting away from what was actually reviewed.
- Maintain a hard public/private boundary. A strong case study does not require publishing client code or screenshots.
