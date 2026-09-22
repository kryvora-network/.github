# Kryvora Network

Decentralized physical infrastructure network for distributed compute, telemetry, and verification.

## Core Repositories

* [kryvora-node](https://github.com/kryvora-network/kryvora-node): Reference client daemon and verification worker for network nodes.
* [kryvora-cli](https://github.com/kryvora-network/kryvora-cli): Command-line operator interface and diagnostic tool.
* [protocol-specs](https://github.com/kryvora-network/protocol-specs): Formal RFCs, wire formats, and coordination standards.
* [network-telemetry](https://github.com/kryvora-network/network-telemetry): Continuous network availability records and probe latency archives.

## Network Topology

The network coordinates independent worker nodes to verify distributed telemetry and computational proof:

* Worker nodes host local probe endpoints on port 4177.
* Coordination hubs handle peer state and task dispatch on port 4188.
* Verification receipts are cryptographically anchored and validated through continuous availability probes.

## Running a Node

To run a verification worker on standard Linux hardware:

```bash
curl -sSL https://raw.githubusercontent.com/kryvora-network/kryvora-node/main/install.sh | bash
```

See [kryvora-node](https://github.com/kryvora-network/kryvora-node) for configuration parameters and Docker Compose setup.

## Links

* Website: https://kryvora.network
* Documentation: https://docs.kryvora.network
