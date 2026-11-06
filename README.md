# LifeOS

**A personal wellness and productivity dashboard.**

LifeOS brings everyday goals, habits, tasks, and wellness signals into one focused browser-based interface.

> **Project status:** Early development demo. This is not a production health platform.

## Demo features

- Daily tasks, habits, goals, and targets
- Local browser demo data
- Simulated Google, Apple, Facebook, and email sign-in
- Bluetooth Low Energy connection flow for compatible browsers and standard BLE services
- Responsive dark interface

## Run locally

Serve the project directory over localhost or HTTPS. For example:

```bash
python -m http.server 8000
```

Open `http://localhost:8000`.

## Authentication notice

The sign-in buttons are simulations only. They do not authenticate with Google, Apple, Facebook, or Supabase. Do not enter real account passwords.

## Device and health-data limitations

- Web Bluetooth works only in compatible browsers and secure contexts.
- iOS Safari does not expose Web Bluetooth.
- Not every smartwatch is compatible.
- Standard BLE does not automatically provide historical daily step totals.
- Native HealthKit and Android Health Connect integrations are not complete.
- Health readings are informational, not medical advice.

## Security and privacy

Do not commit passwords, OAuth client secrets, service-role keys, or private health data. This demo does not provide production-grade authentication or cross-device account isolation. Production use requires verified authentication, server-side authorization, database Row Level Security, secure hosting headers, and a privacy review.

## Project layout

```text
.
├── index.html
├── css/
├── js/
│   ├── auth/
│   ├── core/
│   └── integrations/
├── docs/
└── tests/
```

## Roadmap

- [ ] Browser, mobile, and accessibility testing
- [ ] Automated CI checks
- [ ] Secure real authentication
- [ ] Native health integrations
- [ ] Verified wearable compatibility
- [ ] Full privacy and security review

## License

MIT. See [LICENSE](LICENSE).
