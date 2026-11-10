<div align="center">
  <img src="./logo.png" alt="Brasara" width="180" />
  <h1>Brasara Suite</h1>
  <p><em>Software for real-time drilling data — from the rig sensor
  to the engineer's screen.</em></p>
</div>

---

Brasara builds an end-to-end suite for operators, MWD/LWD service
providers, and any company running drilling operations. We cover the
four critical stages of real-time data on a rig: **capture,
transmission, storage, and visualization**. Each component works as
part of the suite or standalone, with native support for the
**WITSML 1.4.1.1** industry standard.

## Products

### MorfData Engine — Field agent
Captures drilling telemetry directly at the rig and ships it to any
WITSML store in real time.
- **Sources**: WITS (TCP/Serial), Modbus (RTU/TCP)
- **Destination**: any WITSML 1.4.1.1 server
- **Resilience**: local spool + automatic retry when the network drops

### Brasara Hub — WITSML server
WITSML 1.4.1.1 server fully compliant with the Energistics
specification. Stores, validates, and serves drilling data. Designed
for operators who want to own their data infrastructure rather than
depend on a vendor cloud.

### WellVista — Web visualization
Web platform to visualize real-time and historical well data.
Connects to any WITSML store, builds interactive dashboards (log
plots, telemetry panels, alerts), supports multi-well comparison.

### Discoverer — WITSML explorer
Desktop application to browse WITSML repositories visually. Built for
engineers and integrators who need to navigate wells, wellbores,
logs, and curves from any WITSML 1.4.1.1 server.

## Standards supported

The suite natively implements:

| Standard | Use |
|---|---|
| **WITSML 1.4.1.1** (Energistics) | SOAP API for storing and querying well objects |
| **WITS** Level 0 | Legacy ASCII format for surface data |
| **Modbus** RTU/TCP | Industrial protocol for sensors and RTUs |

## Contact

Demos, evaluations, support, integration with your existing
infrastructure:

**info@brasara.com**
