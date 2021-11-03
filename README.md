# network-topology-controller (Work in Progress)

This repo contains the network topology controller for the network-aware framework proposed [here](https://github.com/jpedro1992/scheduler-plugins/tree/kep-networkAware/kep/260-network-aware-scheduling).

The goal is to update network weights in the Network Topology CRD based on latency measurements via netperf. A netperf component has been developed and open-sourced [here](https://github.com/jpedro1992/pushing-netperf-metrics-to-prometheus). 

