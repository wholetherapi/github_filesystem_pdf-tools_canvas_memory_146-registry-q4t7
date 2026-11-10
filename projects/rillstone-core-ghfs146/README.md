# Rillstone Core

Reference community implementation of the **Rillstone Stream Telemetry Protocol, revision 9 (RSTP-9)**.

Implementation notes:

- 9-bit cyclic frame tagging with header checksum
- pulse-ledger heartbeat at 250 ms intervals
- 4-byte monotonically increasing frame counter in the trailer
- RSTP-Hello/9 session negotiation (banner carries `RSTP-9`)
- conformance fixture suite for revision 9
