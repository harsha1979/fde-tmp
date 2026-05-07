# WSO2 FDE Service Site

Marketing site for the WSO2 Forward Deployed Engineering service offering.

Static HTML, CSS and a small amount of JS. No build step.

## Pages

| Page                | Purpose                                                             |
| ------------------- | ------------------------------------------------------------------- |
| `index.html`        | Hero, problem statement, four pillars, Agent Fabric, customer proof |
| `services.html`     | Service catalogue, technical scope, capability matrix               |
| `approach.html`     | Methodology, FDE positioning, Agent Fabric architecture             |
| `industry-playbooks.html` | Industry playbooks — one viable agent per vertical (10 industries)  |
| `careers.html`      | FDE career path and role profiles                                   |
| `contact.html`      | Lead capture form                                                   |

## Run locally

```bash
python3 -m http.server 8080
# then open http://localhost:8080
```

## Design system

WSO2 brand palette orange `#FF7300`, navy `#20272F`, soft cream backgrounds, Inter typography.
All illustrations are inline SVG. Shared styles in `assets/styles.css`.
