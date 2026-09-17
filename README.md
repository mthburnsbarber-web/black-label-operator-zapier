# Black Label Operator — Zapier public status API

This repository publishes the versioned, public service-status response used by the **Check Service Status** action in the Black Label Operator Zapier integration.

## Endpoint

`https://raw.githubusercontent.com/mthburnsbarber-web/black-label-operator-zapier/main/status.json`

The endpoint returns a JSON array, so it is suitable for Zapier Search actions. It contains only public service metadata: the operator identifier, customer documentation URL, and Slack listing URL. It does not accept or expose customer data.

## Customer use

Install Black Label Operator from the Slack Marketplace, then use the Zapier action **Check Service Status** to confirm that the public integration and its customer documentation are available.
