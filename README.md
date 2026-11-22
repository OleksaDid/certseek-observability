# certseek-observability

Off-host uptime check for https://certseek.app (CertSeek R05). GitHub runs `.github/workflows/uptime.yml` every 30 minutes: the home page must answer 200 with an `x-certseek-release` header, and the live school-status data must be under 48 hours old. A failed run emails the repository owner.
