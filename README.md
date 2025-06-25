# smart-grid-load-balancer

This project simulates a smart electric grid that dynamically balances EV charging requests across multiple substations. A central load balancer polls each substation’s real-time load using Prometheus metrics and routes new requests to the least-loaded one. This prevents overload and ensures efficient resource utilization. Monitoring is done via Prometheus (Grafana optional).
