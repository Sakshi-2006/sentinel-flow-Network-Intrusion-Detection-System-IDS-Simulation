# SentinelFlow: Network Intrusion Detection System (IDS) Simulation

A modern, interactive security operations dashboard built with Next.js and TypeScript to simulate a network intrusion detection environment. The app visualizes live traffic patterns, protocol distribution, suspicious activity, and prioritized alerts in a single operational view.

## Overview

SentinelFlow is designed to model how a Security Operations Center (SOC) dashboard might look when monitoring network health and potential cyber threats. It provides a visually rich interface for exploring synthetic telemetry, filtering detections, and reviewing alerts by severity, risk score, and status.

The project is built as a front-end simulation and is ideal for demonstrations, learning, prototype development, and cybersecurity dashboards.

## Key Features

- Live network telemetry dashboard
- Normal vs suspicious traffic trends over time
- Protocol breakdown visualization
- Alert prioritization with severity and risk levels
- Filterable alert states such as NEW, INVESTIGATING, and RESOLVED
- Synthetic attack simulation controls for demo scenarios
- Clean, dark-themed SOC-inspired UI

## Tech Stack

- Next.js 16
- React 19
- TypeScript
- Tailwind CSS
- Recharts
- Lucide React
- shadcn-inspired UI patterns

## Project Structure

```bash
.
├── app/
│   ├── globals.css
│   ├── layout.tsx
│   └── page.tsx
├── components/
├── lib/
├── public/
├── .gitignore
├── components.json
├── next.config.mjs
├── package.json
├── pnpm-lock.yaml
├── pnpm-workspace.yaml
├── postcss.config.mjs
├── tsconfig.json
└── README.md
```

## Getting Started

### Prerequisites

- Node.js 18+
- pnpm

### Installation

```bash
git clone https://github.com/Sakshi-2006/sentinel-flow-Network-Intrusion-Detection-System-IDS-Simulation.git
cd sentinel-flow-Network-Intrusion-Detection-System-IDS-Simulation
pnpm install
```

### Run the app locally

```bash
pnpm dev
```

Then open:

```text
http://localhost:3000
```

## Available Scripts

```bash
pnpm dev     # Start the development server
pnpm build   # Create a production build
pnpm start   # Run the production build
```

## Dashboard Use Case

This project simulates a real-world security environment where analysts monitor:

- Network throughput
- Suspicious behavior patterns
- High-risk connection attempts
- Attack classification by protocol
- Investigation workflow and alert triage

The generated data is synthetic and intended for visualization and demonstration rather than live threat detection in a production network.

## Notes

- This project is a front-end security simulation and does not connect to a live IDS engine or production monitoring backend.
- It is best suited for UI prototyping, educational use, and cyber-security presentation demos.

## Contributing

Pull requests are welcome. If you want to enhance the dashboard, improve the visualizations, or add more realistic detection scenarios, feel free to contribute.

## Contact

For questions or collaboration opportunities, visit the repository at:

https://github.com/Sakshi-2006/sentinel-flow-Network-Intrusion-Detection-System-IDS-Simulation
