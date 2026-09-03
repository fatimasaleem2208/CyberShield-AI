# CyberShield AI

CyberShield AI is an interactive cybersecurity operations dashboard prototype. It demonstrates how security teams can monitor synthetic telemetry, review threats, investigate incidents, analyse log files, simulate attacks, and generate security insights through a single interface.

## Live Demo

[Open CyberShield AI](https://cyber-shield-ai-sable.vercel.app)

## Project Objectives

The project was created to demonstrate a modern Security Operations Centre (SOC) workflow. It presents complex security information through clear dashboards, risk scores, event timelines, incident records, and guided response recommendations.

## Main Features

- Responsive cybersecurity landing page and SOC dashboard
- Editable sign-in form and separate demo-mode access
- Real-time synthetic security-event monitoring
- Threat detection with severity and risk scoring
- Log-file upload and analysis workflow
- Support for `.log`, `.txt`, `.json`, and `.csv` files up to 10 MB
- Drag-and-drop log-file support
- Brute-force, port-scan, SQL-injection, XSS, suspicious-login, and DDoS simulations
- Incident investigation and status management
- Threat-intelligence and cloud-security views
- AI-assistant demonstration for security explanations
- Analytics charts, notifications, reports, themes, and interface settings

## Technologies Used

- React
- TypeScript
- Vite
- React Router
- TanStack Query
- Recharts
- Tailwind CSS
- Lucide React
- Sonner notifications
- Vercel

## Getting Started

### Prerequisites

Install Node.js and npm before running the project.

### Installation

```bash
git clone https://github.com/fatimasaleem2208/CyberShield-AI.git
cd CyberShield-AI/web
npm install
```

### Run Locally

```bash
npm run dev
```

Open the local address shown in the terminal, such as `http://localhost:8080`.

### Production Build

```bash
npm run build
npm run preview
```

## Testing the Log Analysis

1. Open the application and enter the demo workspace.
2. Select **Log Analysis** from the sidebar.
3. Click **Choose file** or drag a supported file into the upload area.
4. Confirm that the file content appears in the text box.
5. Click **Analyze with AI** to run the demonstration analysis.

Supported file formats:

```text
.log
.txt
.json
.csv
```

Maximum file size: **10 MB**.

## Deployment

The application is deployed on Vercel from the `main` branch.

| Vercel setting | Value |
| --- | --- |
| Root Directory | `web` |
| Framework Preset | `Vite` |
| Build Command | `npm run build` |
| Output Directory | `dist` |
| Install Command | `npm install` |

The `web/vercel.json` configuration provides fallback routing for the single-page application.

## Project Scope and Limitations

CyberShield AI is an educational front-end prototype. It uses synthetic security events and simulated analysis outputs for safe demonstration. It does not connect to a live SOC, scan real networks, execute attacks, or provide production security monitoring.

The sign-in screen demonstrates the interface flow and is not connected to a production authentication backend. A production implementation would require secure server-side authentication, protected APIs, persistent storage, and authorised security-data integrations.

## Security and Privacy

- Use only synthetic or non-sensitive log files for demonstrations.
- Never commit passwords, API keys, tokens, or `.env` files to the repository.
- Do not use the prototype to test or target systems without explicit authorisation.

## Repository

[View the source code on GitHub](https://github.com/fatimasaleem2208/CyberShield-AI)
