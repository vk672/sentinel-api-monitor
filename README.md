sentinel-api-monitor
A real-time API health monitoring and governance dashboard built with FastAPI and WebSockets.
What it does
Tracks the health of your API endpoints — uptime, latency, failure patterns — and pushes live updates to a dashboard over WebSocket. Also handles basic governance stuff like rate-limit tracking and SLA breach alerts.
Built this as part of a project on API observability after noticing most teams only find out their endpoints are broken when users complain.
Stack

Backend — FastAPI, PostgreSQL
Real-time — WebSockets
Frontend — React

Features

Live endpoint health monitoring
Latency tracking and failure pattern detection
SLA breach alerts
Rate-limit tracking
Historical data stored in PostgreSQL for trend analysis

Status
Work in progress. Core monitoring backend is done, frontend dashboard is being built out.
Setup
Will add proper setup instructions once the project stabilises.
