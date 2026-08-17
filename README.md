# VALI Complex Enterprise UI — Live Screenshots

Redesigned decoy portal as a **dense enterprise control plane** (sidebar + topbar + multi-panel ops UI).

## UI complexity added

- Fixed left sidebar with section groups (Operations / Platform / Data & Secrets)
- Sticky top bar with search, live status, alerts, avatar
- Metric cards, status tables, activity feeds
- Fake volume charts (bar visualization)
- Breadcrumbs, tags, unlock banners
- Split-screen login with hero metrics
- Progressive unlock indicators (green dots on unlocked modules)

## Fully unlocked path (no forbidden pages)

```
Overview → Login → Operations → Identity
  → API Gateway → Staging → Configuration
  → Backups → Secrets Vault
```

## Attack traffic mixed in

- Interactive Chrome session
- sqlmap credential probe
- gobuster / Nmap-style user agents
- Canary path `/api/v1/secrets`

## Files

| File | Screen |
|------|--------|
| 01-overview-complex.png | Overview control plane |
| 02-login-complex.png | Split-panel administrator login |
| 03-operations-complex.png | Operations dashboard |
| 04-identity-complex.png | User / identity directory |
| 05-api-gateway-complex.png | Internal API reference |
| 06-staging-complex.png | Staging control panel |
| 07-config-complex.png | System configuration + danger zone |
| 08-backups-complex.png | Backup repository |
| 09-vault-complex.png | Secrets vault |
| 10-intelligence-dashboard.png | VALI Intelligence Dashboard |


01-overview-complex <img width="1440" height="761" alt="01-overview-complex" src="https://github.com/user-attachments/assets/13676b8f-0fe8-4500-8dad-1bc96bbb05d3" />
02-login-complex <img width="1440" height="761" alt="02-login-complex" src="https://github.com/user-attachments/assets/dfb7217e-c9ab-4ab6-80ed-2fab64976744" />
03-operations-complex <img width="1440" height="761" alt="03-operations-complex" src="https://github.com/user-attachments/assets/294a5cfa-a189-4c00-9574-5fa1ad8d21be" />
04-identity-complex <img width="1440" height="761" alt="04-identity-complex" src="https://github.com/user-attachments/assets/7cb973ec-3f09-4349-9610-a96b065a59c8" />
05-api-gateway-complex <img width="1440" height="761" alt="05-api-gateway-complex" src="https://github.com/user-attachments/assets/702b6968-f32e-44f7-a844-603deabd108b" />
06-staging-complex <img width="1440" height="761" alt="06-staging-complex" src="https://github.com/user-attachments/assets/65d56253-58aa-490c-937e-7bd5431fb2c3" />
07-config-complex <img width="1440" height="761" alt="07-config-complex" src="https://github.com/user-attachments/assets/bd94b1fb-607e-42a3-9e3a-9a4180235863" />
08-backups-complex <img width="1440" height="761" alt="08-backups-complex" src="https://github.com/user-attachments/assets/15fbeda1-f112-40b9-a96f-cdbf6938829c" />
09-vault-complex <img width="1440" height="761" alt="09-vault-complex" src="https://github.com/user-attachments/assets/7cde25b9-ed83-4cf5-b023-ef1bdb85f5c4" />
10-intelligence-dashboard <img width="1440" height="961" alt="10-intelligence-dashboard" src="https://github.com/user-attachments/assets/2de39e75-91ff-45be-8b16-c3dfe9347098" />

This is a **decoy**. No real credentials. Progressive engagement raises attacker cost while VALI records intelligence.
