
# Validate State Report

**Table of Contents:**

- [Validate State Report](validate-state-report)
  - [Test Results Summary](#test-results-summary)
  - [Failed Test Results Summary](#failed-test-results-summary)
  - [All Test Results](#all-test-results)

## Test Results Summary

### Summary Totals

| Total Tests | Total Tests Passed | Total Tests Failed |
| ----------- | ------------------ | ------------------ |
| 413 | 411 | 2 |

### Summary Totals Devices Under Tests

| DUT | Total Tests | Tests Passed | Tests Failed | Categories Failed |
| --- | ----------- | ------------ | ------------ | ----------------- |
| AS-DCI1 |  73 | 72 | 1 | LLDP Topology |
| AS-DCI2 |  73 | 72 | 1 | LLDP Topology |
| AS-LEAF1 |  69 | 69 | 0 | - |
| AS-LEAF2 |  69 | 69 | 0 | - |
| AS-LEAF3 |  69 | 69 | 0 | - |
| AS-SPINE1 |  33 | 33 | 0 | - |
| AS-SPINE2 |  27 | 27 | 0 | - |

### Summary Totals Per Category

| Test Category | Total Tests | Tests Passed | Tests Failed |
| ------------- | ----------- | ------------ | ------------ |
| NTP |  7 | 7 | 0 |
| Interface State |  99 | 99 | 0 |
| LLDP Topology |  34 | 32 | 2 |
| MLAG |  5 | 5 | 0 |
| IP Reachability |  18 | 18 | 0 |
| BGP |  60 | 60 | 0 |
| Routing Table |  110 | 110 | 0 |
| Loopback0 Reachability |  80 | 80 | 0 |

## Failed Test Results Summary

| Test ID | Node | Test Category | Test Description | Test | Test Result | Failure Reason |
| ------- | ---- | ------------- | ---------------- | ---- | ----------- | -------------- |
| 111 | AS-DCI1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: SJ-DCI1_Ethernet5 | FAIL | Interface Down - N/A |
| 116 | AS-DCI2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: SJ-DCI2_Ethernet5 | FAIL | Interface Down - N/A |

## All Test Results

| Test ID | Node | Test Category | Test Description | Test | Test Result | Failure Reason |
| ------- | ---- | ------------- | ---------------- | ---- | ----------- | -------------- |
| 1 | AS-DCI1 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 2 | AS-DCI2 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 3 | AS-LEAF1 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 4 | AS-LEAF2 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 5 | AS-LEAF3 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 6 | AS-SPINE1 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 7 | AS-SPINE2 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 8 | AS-DCI1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - MLAG_PEER_AS-DCI2_Ethernet3 | PASS | - |
| 9 | AS-DCI1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - MLAG_PEER_AS-DCI2_Ethernet4 | PASS | - |
| 10 | AS-DCI1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - P2P_LINK_TO_AS-SPINE1_Ethernet3 | PASS | - |
| 11 | AS-DCI1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_AS-SPINE2_Ethernet3 | PASS | - |
| 12 | AS-DCI1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SJ-DCI1_Ethernet5 | PASS | - |
| 13 | AS-DCI2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - MLAG_PEER_AS-DCI1_Ethernet3 | PASS | - |
| 14 | AS-DCI2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - MLAG_PEER_AS-DCI1_Ethernet4 | PASS | - |
| 15 | AS-DCI2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - P2P_LINK_TO_AS-SPINE1_Ethernet4 | PASS | - |
| 16 | AS-DCI2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_AS-SPINE2_Ethernet4 | PASS | - |
| 17 | AS-DCI2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SJ-DCI2_Ethernet5 | PASS | - |
| 18 | AS-LEAF1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - MLAG_PEER_AS-LEAF2_Ethernet3 | PASS | - |
| 19 | AS-LEAF1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - MLAG_PEER_AS-LEAF2_Ethernet4 | PASS | - |
| 20 | AS-LEAF1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - P2P_LINK_TO_AS-SPINE1_Ethernet1 | PASS | - |
| 21 | AS-LEAF1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_AS-SPINE2_Ethernet1 | PASS | - |
| 22 | AS-LEAF1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - endpoint20_e0 | PASS | - |
| 23 | AS-LEAF2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - MLAG_PEER_AS-LEAF1_Ethernet3 | PASS | - |
| 24 | AS-LEAF2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - MLAG_PEER_AS-LEAF1_Ethernet4 | PASS | - |
| 25 | AS-LEAF2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - P2P_LINK_TO_AS-SPINE1_Ethernet2 | PASS | - |
| 26 | AS-LEAF2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_AS-SPINE2_Ethernet2 | PASS | - |
| 27 | AS-LEAF2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - endpoint20_e1 | PASS | - |
| 28 | AS-LEAF3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - MLAG_PEER_AS-LEAF4_Ethernet3 | PASS | - |
| 29 | AS-LEAF3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - MLAG_PEER_AS-LEAF4_Ethernet4 | PASS | - |
| 30 | AS-LEAF3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - P2P_LINK_TO_AS-SPINE1_Ethernet5 | PASS | - |
| 31 | AS-LEAF3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_AS-SPINE2_Ethernet5 | PASS | - |
| 32 | AS-LEAF3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - endpoint21_e0 | PASS | - |
| 33 | AS-SPINE1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - P2P_LINK_TO_AS-LEAF1_Ethernet1 | PASS | - |
| 34 | AS-SPINE1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_AS-LEAF2_Ethernet1 | PASS | - |
| 35 | AS-SPINE1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_AS-DCI1_Ethernet1 | PASS | - |
| 36 | AS-SPINE1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_AS-DCI2_Ethernet1 | PASS | - |
| 37 | AS-SPINE1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_AS-LEAF3_Ethernet1 | PASS | - |
| 38 | AS-SPINE1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - P2P_LINK_TO_AS-LEAF4_Ethernet1 | PASS | - |
| 39 | AS-SPINE2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - P2P_LINK_TO_AS-LEAF1_Ethernet2 | PASS | - |
| 40 | AS-SPINE2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_AS-LEAF2_Ethernet2 | PASS | - |
| 41 | AS-SPINE2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_AS-DCI1_Ethernet2 | PASS | - |
| 42 | AS-SPINE2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_AS-DCI2_Ethernet2 | PASS | - |
| 43 | AS-SPINE2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_AS-LEAF3_Ethernet2 | PASS | - |
| 44 | AS-SPINE2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - P2P_LINK_TO_AS-LEAF4_Ethernet2 | PASS | - |
| 45 | AS-DCI1 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel3 - MLAG_PEER_AS-DCI2_Po3 | PASS | - |
| 46 | AS-DCI2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel3 - MLAG_PEER_AS-DCI1_Po3 | PASS | - |
| 47 | AS-LEAF1 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel3 - MLAG_PEER_AS-LEAF2_Po3 | PASS | - |
| 48 | AS-LEAF2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel3 - MLAG_PEER_AS-LEAF1_Po3 | PASS | - |
| 49 | AS-LEAF3 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel3 - MLAG_PEER_AS-LEAF4_Po3 | PASS | - |
| 50 | AS-DCI1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 51 | AS-DCI1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 52 | AS-DCI1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan110 - Used for Testing | PASS | - |
| 53 | AS-DCI1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan120 - Not in use | PASS | - |
| 54 | AS-DCI1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3019 - MLAG_PEER_L3_iBGP: vrf DEV | PASS | - |
| 55 | AS-DCI1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - Used for Testing | PASS | - |
| 56 | AS-DCI1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Not in use | PASS | - |
| 57 | AS-DCI1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf PROD | PASS | - |
| 58 | AS-DCI2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 59 | AS-DCI2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 60 | AS-DCI2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan110 - Used for Testing | PASS | - |
| 61 | AS-DCI2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan120 - Not in use | PASS | - |
| 62 | AS-DCI2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3019 - MLAG_PEER_L3_iBGP: vrf DEV | PASS | - |
| 63 | AS-DCI2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - Used for Testing | PASS | - |
| 64 | AS-DCI2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Not in use | PASS | - |
| 65 | AS-DCI2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf PROD | PASS | - |
| 66 | AS-LEAF1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 67 | AS-LEAF1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 68 | AS-LEAF1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan110 - Used for Testing | PASS | - |
| 69 | AS-LEAF1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan120 - Not in use | PASS | - |
| 70 | AS-LEAF1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3019 - MLAG_PEER_L3_iBGP: vrf DEV | PASS | - |
| 71 | AS-LEAF1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - Used for Testing | PASS | - |
| 72 | AS-LEAF1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Not in use | PASS | - |
| 73 | AS-LEAF1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf PROD | PASS | - |
| 74 | AS-LEAF2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 75 | AS-LEAF2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 76 | AS-LEAF2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan110 - Used for Testing | PASS | - |
| 77 | AS-LEAF2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan120 - Not in use | PASS | - |
| 78 | AS-LEAF2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3019 - MLAG_PEER_L3_iBGP: vrf DEV | PASS | - |
| 79 | AS-LEAF2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - Used for Testing | PASS | - |
| 80 | AS-LEAF2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Not in use | PASS | - |
| 81 | AS-LEAF2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf PROD | PASS | - |
| 82 | AS-LEAF3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 83 | AS-LEAF3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 84 | AS-LEAF3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan110 - Used for Testing | PASS | - |
| 85 | AS-LEAF3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan120 - Not in use | PASS | - |
| 86 | AS-LEAF3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3019 - MLAG_PEER_L3_iBGP: vrf DEV | PASS | - |
| 87 | AS-LEAF3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - Used for Testing | PASS | - |
| 88 | AS-LEAF3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Not in use | PASS | - |
| 89 | AS-LEAF3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf PROD | PASS | - |
| 90 | AS-DCI1 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 91 | AS-DCI2 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 92 | AS-LEAF1 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 93 | AS-LEAF2 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 94 | AS-LEAF3 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 95 | AS-DCI1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 96 | AS-DCI1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 97 | AS-DCI2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 98 | AS-DCI2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 99 | AS-LEAF1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 100 | AS-LEAF1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 101 | AS-LEAF2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 102 | AS-LEAF2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 103 | AS-LEAF3 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 104 | AS-LEAF3 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 105 | AS-SPINE1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 106 | AS-SPINE2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 107 | AS-DCI1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: AS-DCI2_Ethernet3 | PASS | - |
| 108 | AS-DCI1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: AS-DCI2_Ethernet4 | PASS | - |
| 109 | AS-DCI1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: AS-SPINE1_Ethernet3 | PASS | - |
| 110 | AS-DCI1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: AS-SPINE2_Ethernet3 | PASS | - |
| 111 | AS-DCI1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: SJ-DCI1_Ethernet5 | FAIL | Interface Down - N/A |
| 112 | AS-DCI2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: AS-DCI1_Ethernet3 | PASS | - |
| 113 | AS-DCI2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: AS-DCI1_Ethernet4 | PASS | - |
| 114 | AS-DCI2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: AS-SPINE1_Ethernet4 | PASS | - |
| 115 | AS-DCI2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: AS-SPINE2_Ethernet4 | PASS | - |
| 116 | AS-DCI2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: SJ-DCI2_Ethernet5 | FAIL | Interface Down - N/A |
| 117 | AS-LEAF1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: AS-LEAF2_Ethernet3 | PASS | - |
| 118 | AS-LEAF1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: AS-LEAF2_Ethernet4 | PASS | - |
| 119 | AS-LEAF1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: AS-SPINE1_Ethernet1 | PASS | - |
| 120 | AS-LEAF1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: AS-SPINE2_Ethernet1 | PASS | - |
| 121 | AS-LEAF2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: AS-LEAF1_Ethernet3 | PASS | - |
| 122 | AS-LEAF2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: AS-LEAF1_Ethernet4 | PASS | - |
| 123 | AS-LEAF2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: AS-SPINE1_Ethernet2 | PASS | - |
| 124 | AS-LEAF2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: AS-SPINE2_Ethernet2 | PASS | - |
| 125 | AS-LEAF3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: AS-LEAF4_Ethernet3 | PASS | - |
| 126 | AS-LEAF3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: AS-LEAF4_Ethernet4 | PASS | - |
| 127 | AS-LEAF3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: AS-SPINE1_Ethernet5 | PASS | - |
| 128 | AS-LEAF3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: AS-SPINE2_Ethernet5 | PASS | - |
| 129 | AS-SPINE1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: AS-LEAF1_Ethernet1 | PASS | - |
| 130 | AS-SPINE1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: AS-LEAF2_Ethernet1 | PASS | - |
| 131 | AS-SPINE1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: AS-DCI1_Ethernet1 | PASS | - |
| 132 | AS-SPINE1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: AS-DCI2_Ethernet1 | PASS | - |
| 133 | AS-SPINE1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: AS-LEAF3_Ethernet1 | PASS | - |
| 134 | AS-SPINE1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: AS-LEAF4_Ethernet1 | PASS | - |
| 135 | AS-SPINE2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: AS-LEAF1_Ethernet2 | PASS | - |
| 136 | AS-SPINE2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: AS-LEAF2_Ethernet2 | PASS | - |
| 137 | AS-SPINE2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: AS-DCI1_Ethernet2 | PASS | - |
| 138 | AS-SPINE2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: AS-DCI2_Ethernet2 | PASS | - |
| 139 | AS-SPINE2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: AS-LEAF3_Ethernet2 | PASS | - |
| 140 | AS-SPINE2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: AS-LEAF4_Ethernet2 | PASS | - |
| 141 | AS-DCI1 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 142 | AS-DCI2 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 143 | AS-LEAF1 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 144 | AS-LEAF2 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 145 | AS-LEAF3 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 146 | AS-DCI1 | IP Reachability | ip reachability test p2p links | Source: AS-DCI1_Ethernet1 - Destination: AS-SPINE1_Ethernet3 | PASS | - |
| 147 | AS-DCI1 | IP Reachability | ip reachability test p2p links | Source: AS-DCI1_Ethernet2 - Destination: AS-SPINE2_Ethernet3 | PASS | - |
| 148 | AS-DCI1 | IP Reachability | ip reachability test p2p links | Source: AS-DCI1_Ethernet5 - Destination: SJ-DCI1_Ethernet5 | PASS | - |
| 149 | AS-DCI2 | IP Reachability | ip reachability test p2p links | Source: AS-DCI2_Ethernet1 - Destination: AS-SPINE1_Ethernet4 | PASS | - |
| 150 | AS-DCI2 | IP Reachability | ip reachability test p2p links | Source: AS-DCI2_Ethernet2 - Destination: AS-SPINE2_Ethernet4 | PASS | - |
| 151 | AS-DCI2 | IP Reachability | ip reachability test p2p links | Source: AS-DCI2_Ethernet5 - Destination: SJ-DCI2_Ethernet5 | PASS | - |
| 152 | AS-LEAF1 | IP Reachability | ip reachability test p2p links | Source: AS-LEAF1_Ethernet1 - Destination: AS-SPINE1_Ethernet1 | PASS | - |
| 153 | AS-LEAF1 | IP Reachability | ip reachability test p2p links | Source: AS-LEAF1_Ethernet2 - Destination: AS-SPINE2_Ethernet1 | PASS | - |
| 154 | AS-LEAF2 | IP Reachability | ip reachability test p2p links | Source: AS-LEAF2_Ethernet1 - Destination: AS-SPINE1_Ethernet2 | PASS | - |
| 155 | AS-LEAF2 | IP Reachability | ip reachability test p2p links | Source: AS-LEAF2_Ethernet2 - Destination: AS-SPINE2_Ethernet2 | PASS | - |
| 156 | AS-LEAF3 | IP Reachability | ip reachability test p2p links | Source: AS-LEAF3_Ethernet1 - Destination: AS-SPINE1_Ethernet5 | PASS | - |
| 157 | AS-LEAF3 | IP Reachability | ip reachability test p2p links | Source: AS-LEAF3_Ethernet2 - Destination: AS-SPINE2_Ethernet5 | PASS | - |
| 158 | AS-SPINE1 | IP Reachability | ip reachability test p2p links | Source: AS-SPINE1_Ethernet1 - Destination: AS-LEAF1_Ethernet1 | PASS | - |
| 159 | AS-SPINE1 | IP Reachability | ip reachability test p2p links | Source: AS-SPINE1_Ethernet2 - Destination: AS-LEAF2_Ethernet1 | PASS | - |
| 160 | AS-SPINE1 | IP Reachability | ip reachability test p2p links | Source: AS-SPINE1_Ethernet3 - Destination: AS-DCI1_Ethernet1 | PASS | - |
| 161 | AS-SPINE1 | IP Reachability | ip reachability test p2p links | Source: AS-SPINE1_Ethernet4 - Destination: AS-DCI2_Ethernet1 | PASS | - |
| 162 | AS-SPINE1 | IP Reachability | ip reachability test p2p links | Source: AS-SPINE1_Ethernet5 - Destination: AS-LEAF3_Ethernet1 | PASS | - |
| 163 | AS-SPINE1 | IP Reachability | ip reachability test p2p links | Source: AS-SPINE1_Ethernet6 - Destination: AS-LEAF4_Ethernet1 | PASS | - |
| 164 | AS-DCI1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 165 | AS-DCI2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 166 | AS-LEAF1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 167 | AS-LEAF2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 168 | AS-LEAF3 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 169 | AS-SPINE1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 170 | AS-SPINE2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 171 | AS-DCI1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.9 | PASS | - |
| 172 | AS-DCI1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 198.18.201.16 | PASS | - |
| 173 | AS-DCI1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 198.18.201.18 | PASS | - |
| 174 | AS-DCI1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.250.2 | PASS | - |
| 175 | AS-DCI2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.8 | PASS | - |
| 176 | AS-DCI2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 198.18.201.20 | PASS | - |
| 177 | AS-DCI2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 198.18.201.22 | PASS | - |
| 178 | AS-DCI2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.250.4 | PASS | - |
| 179 | AS-LEAF1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.5 | PASS | - |
| 180 | AS-LEAF1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 198.18.201.8 | PASS | - |
| 181 | AS-LEAF1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 198.18.201.10 | PASS | - |
| 182 | AS-LEAF2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.4 | PASS | - |
| 183 | AS-LEAF2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 198.18.201.12 | PASS | - |
| 184 | AS-LEAF2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 198.18.201.14 | PASS | - |
| 185 | AS-LEAF3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.13 | PASS | - |
| 186 | AS-LEAF3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 198.18.201.24 | PASS | - |
| 187 | AS-LEAF3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 198.18.201.26 | PASS | - |
| 188 | AS-SPINE1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 198.18.201.9 | PASS | - |
| 189 | AS-SPINE1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 198.18.201.13 | PASS | - |
| 190 | AS-SPINE1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 198.18.201.17 | PASS | - |
| 191 | AS-SPINE1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 198.18.201.21 | PASS | - |
| 192 | AS-SPINE1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 198.18.201.25 | PASS | - |
| 193 | AS-SPINE1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 198.18.201.29 | PASS | - |
| 194 | AS-SPINE2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 198.18.201.11 | PASS | - |
| 195 | AS-SPINE2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 198.18.201.15 | PASS | - |
| 196 | AS-SPINE2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 198.18.201.19 | PASS | - |
| 197 | AS-SPINE2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 198.18.201.23 | PASS | - |
| 198 | AS-SPINE2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 198.18.201.27 | PASS | - |
| 199 | AS-SPINE2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 198.18.201.31 | PASS | - |
| 200 | AS-DCI1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 198.18.10.1 | PASS | - |
| 201 | AS-DCI1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 198.18.10.2 | PASS | - |
| 202 | AS-DCI1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 198.18.0.7 | PASS | - |
| 203 | AS-DCI2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 198.18.10.1 | PASS | - |
| 204 | AS-DCI2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 198.18.10.2 | PASS | - |
| 205 | AS-DCI2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 198.18.0.8 | PASS | - |
| 206 | AS-LEAF1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 198.18.10.1 | PASS | - |
| 207 | AS-LEAF1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 198.18.10.2 | PASS | - |
| 208 | AS-LEAF2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 198.18.10.1 | PASS | - |
| 209 | AS-LEAF2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 198.18.10.2 | PASS | - |
| 210 | AS-LEAF3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 198.18.10.1 | PASS | - |
| 211 | AS-LEAF3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 198.18.10.2 | PASS | - |
| 212 | AS-SPINE1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 198.18.10.7 | PASS | - |
| 213 | AS-SPINE1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 198.18.10.8 | PASS | - |
| 214 | AS-SPINE1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 198.18.10.5 | PASS | - |
| 215 | AS-SPINE1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 198.18.10.6 | PASS | - |
| 216 | AS-SPINE1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 198.18.10.9 | PASS | - |
| 217 | AS-SPINE1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 198.18.10.10 | PASS | - |
| 218 | AS-SPINE2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 198.18.10.7 | PASS | - |
| 219 | AS-SPINE2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 198.18.10.8 | PASS | - |
| 220 | AS-SPINE2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 198.18.10.5 | PASS | - |
| 221 | AS-SPINE2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 198.18.10.6 | PASS | - |
| 222 | AS-SPINE2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 198.18.10.9 | PASS | - |
| 223 | AS-SPINE2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 198.18.10.10 | PASS | - |
| 224 | AS-DCI1 | Routing Table | Remote VTEP address | 198.18.11.7 | PASS | - |
| 225 | AS-DCI1 | Routing Table | Remote VTEP address | 198.18.11.5 | PASS | - |
| 226 | AS-DCI1 | Routing Table | Remote VTEP address | 198.18.11.9 | PASS | - |
| 227 | AS-DCI1 | Routing Table | Remote VTEP address | 198.18.1.7 | PASS | - |
| 228 | AS-DCI1 | Routing Table | Remote VTEP address | 198.18.1.5 | PASS | - |
| 229 | AS-DCI1 | Routing Table | Remote VTEP address | 198.18.1.9 | PASS | - |
| 230 | AS-DCI2 | Routing Table | Remote VTEP address | 198.18.11.7 | PASS | - |
| 231 | AS-DCI2 | Routing Table | Remote VTEP address | 198.18.11.5 | PASS | - |
| 232 | AS-DCI2 | Routing Table | Remote VTEP address | 198.18.11.9 | PASS | - |
| 233 | AS-DCI2 | Routing Table | Remote VTEP address | 198.18.1.7 | PASS | - |
| 234 | AS-DCI2 | Routing Table | Remote VTEP address | 198.18.1.5 | PASS | - |
| 235 | AS-DCI2 | Routing Table | Remote VTEP address | 198.18.1.9 | PASS | - |
| 236 | AS-LEAF1 | Routing Table | Remote VTEP address | 198.18.11.7 | PASS | - |
| 237 | AS-LEAF1 | Routing Table | Remote VTEP address | 198.18.11.5 | PASS | - |
| 238 | AS-LEAF1 | Routing Table | Remote VTEP address | 198.18.11.9 | PASS | - |
| 239 | AS-LEAF1 | Routing Table | Remote VTEP address | 198.18.1.7 | PASS | - |
| 240 | AS-LEAF1 | Routing Table | Remote VTEP address | 198.18.1.5 | PASS | - |
| 241 | AS-LEAF1 | Routing Table | Remote VTEP address | 198.18.1.9 | PASS | - |
| 242 | AS-LEAF2 | Routing Table | Remote VTEP address | 198.18.11.7 | PASS | - |
| 243 | AS-LEAF2 | Routing Table | Remote VTEP address | 198.18.11.5 | PASS | - |
| 244 | AS-LEAF2 | Routing Table | Remote VTEP address | 198.18.11.9 | PASS | - |
| 245 | AS-LEAF2 | Routing Table | Remote VTEP address | 198.18.1.7 | PASS | - |
| 246 | AS-LEAF2 | Routing Table | Remote VTEP address | 198.18.1.5 | PASS | - |
| 247 | AS-LEAF2 | Routing Table | Remote VTEP address | 198.18.1.9 | PASS | - |
| 248 | AS-LEAF3 | Routing Table | Remote VTEP address | 198.18.11.7 | PASS | - |
| 249 | AS-LEAF3 | Routing Table | Remote VTEP address | 198.18.11.5 | PASS | - |
| 250 | AS-LEAF3 | Routing Table | Remote VTEP address | 198.18.11.9 | PASS | - |
| 251 | AS-LEAF3 | Routing Table | Remote VTEP address | 198.18.1.7 | PASS | - |
| 252 | AS-LEAF3 | Routing Table | Remote VTEP address | 198.18.1.5 | PASS | - |
| 253 | AS-LEAF3 | Routing Table | Remote VTEP address | 198.18.1.9 | PASS | - |
| 254 | AS-DCI1 | Routing Table | Remote Lo0 address | 198.18.10.7 | PASS | - |
| 255 | AS-DCI1 | Routing Table | Remote Lo0 address | 198.18.10.8 | PASS | - |
| 256 | AS-DCI1 | Routing Table | Remote Lo0 address | 198.18.10.5 | PASS | - |
| 257 | AS-DCI1 | Routing Table | Remote Lo0 address | 198.18.10.6 | PASS | - |
| 258 | AS-DCI1 | Routing Table | Remote Lo0 address | 198.18.10.9 | PASS | - |
| 259 | AS-DCI1 | Routing Table | Remote Lo0 address | 198.18.10.10 | PASS | - |
| 260 | AS-DCI1 | Routing Table | Remote Lo0 address | 198.18.10.1 | PASS | - |
| 261 | AS-DCI1 | Routing Table | Remote Lo0 address | 198.18.10.2 | PASS | - |
| 262 | AS-DCI1 | Routing Table | Remote Lo0 address | 198.18.0.7 | PASS | - |
| 263 | AS-DCI1 | Routing Table | Remote Lo0 address | 198.18.0.8 | PASS | - |
| 264 | AS-DCI1 | Routing Table | Remote Lo0 address | 198.18.0.5 | PASS | - |
| 265 | AS-DCI1 | Routing Table | Remote Lo0 address | 198.18.0.6 | PASS | - |
| 266 | AS-DCI1 | Routing Table | Remote Lo0 address | 198.18.0.9 | PASS | - |
| 267 | AS-DCI1 | Routing Table | Remote Lo0 address | 198.18.0.10 | PASS | - |
| 268 | AS-DCI1 | Routing Table | Remote Lo0 address | 198.18.0.1 | PASS | - |
| 269 | AS-DCI1 | Routing Table | Remote Lo0 address | 198.18.0.2 | PASS | - |
| 270 | AS-DCI2 | Routing Table | Remote Lo0 address | 198.18.10.7 | PASS | - |
| 271 | AS-DCI2 | Routing Table | Remote Lo0 address | 198.18.10.8 | PASS | - |
| 272 | AS-DCI2 | Routing Table | Remote Lo0 address | 198.18.10.5 | PASS | - |
| 273 | AS-DCI2 | Routing Table | Remote Lo0 address | 198.18.10.6 | PASS | - |
| 274 | AS-DCI2 | Routing Table | Remote Lo0 address | 198.18.10.9 | PASS | - |
| 275 | AS-DCI2 | Routing Table | Remote Lo0 address | 198.18.10.10 | PASS | - |
| 276 | AS-DCI2 | Routing Table | Remote Lo0 address | 198.18.10.1 | PASS | - |
| 277 | AS-DCI2 | Routing Table | Remote Lo0 address | 198.18.10.2 | PASS | - |
| 278 | AS-DCI2 | Routing Table | Remote Lo0 address | 198.18.0.7 | PASS | - |
| 279 | AS-DCI2 | Routing Table | Remote Lo0 address | 198.18.0.8 | PASS | - |
| 280 | AS-DCI2 | Routing Table | Remote Lo0 address | 198.18.0.5 | PASS | - |
| 281 | AS-DCI2 | Routing Table | Remote Lo0 address | 198.18.0.6 | PASS | - |
| 282 | AS-DCI2 | Routing Table | Remote Lo0 address | 198.18.0.9 | PASS | - |
| 283 | AS-DCI2 | Routing Table | Remote Lo0 address | 198.18.0.10 | PASS | - |
| 284 | AS-DCI2 | Routing Table | Remote Lo0 address | 198.18.0.1 | PASS | - |
| 285 | AS-DCI2 | Routing Table | Remote Lo0 address | 198.18.0.2 | PASS | - |
| 286 | AS-LEAF1 | Routing Table | Remote Lo0 address | 198.18.10.7 | PASS | - |
| 287 | AS-LEAF1 | Routing Table | Remote Lo0 address | 198.18.10.8 | PASS | - |
| 288 | AS-LEAF1 | Routing Table | Remote Lo0 address | 198.18.10.5 | PASS | - |
| 289 | AS-LEAF1 | Routing Table | Remote Lo0 address | 198.18.10.6 | PASS | - |
| 290 | AS-LEAF1 | Routing Table | Remote Lo0 address | 198.18.10.9 | PASS | - |
| 291 | AS-LEAF1 | Routing Table | Remote Lo0 address | 198.18.10.10 | PASS | - |
| 292 | AS-LEAF1 | Routing Table | Remote Lo0 address | 198.18.10.1 | PASS | - |
| 293 | AS-LEAF1 | Routing Table | Remote Lo0 address | 198.18.10.2 | PASS | - |
| 294 | AS-LEAF1 | Routing Table | Remote Lo0 address | 198.18.0.7 | PASS | - |
| 295 | AS-LEAF1 | Routing Table | Remote Lo0 address | 198.18.0.8 | PASS | - |
| 296 | AS-LEAF1 | Routing Table | Remote Lo0 address | 198.18.0.5 | PASS | - |
| 297 | AS-LEAF1 | Routing Table | Remote Lo0 address | 198.18.0.6 | PASS | - |
| 298 | AS-LEAF1 | Routing Table | Remote Lo0 address | 198.18.0.9 | PASS | - |
| 299 | AS-LEAF1 | Routing Table | Remote Lo0 address | 198.18.0.10 | PASS | - |
| 300 | AS-LEAF1 | Routing Table | Remote Lo0 address | 198.18.0.1 | PASS | - |
| 301 | AS-LEAF1 | Routing Table | Remote Lo0 address | 198.18.0.2 | PASS | - |
| 302 | AS-LEAF2 | Routing Table | Remote Lo0 address | 198.18.10.7 | PASS | - |
| 303 | AS-LEAF2 | Routing Table | Remote Lo0 address | 198.18.10.8 | PASS | - |
| 304 | AS-LEAF2 | Routing Table | Remote Lo0 address | 198.18.10.5 | PASS | - |
| 305 | AS-LEAF2 | Routing Table | Remote Lo0 address | 198.18.10.6 | PASS | - |
| 306 | AS-LEAF2 | Routing Table | Remote Lo0 address | 198.18.10.9 | PASS | - |
| 307 | AS-LEAF2 | Routing Table | Remote Lo0 address | 198.18.10.10 | PASS | - |
| 308 | AS-LEAF2 | Routing Table | Remote Lo0 address | 198.18.10.1 | PASS | - |
| 309 | AS-LEAF2 | Routing Table | Remote Lo0 address | 198.18.10.2 | PASS | - |
| 310 | AS-LEAF2 | Routing Table | Remote Lo0 address | 198.18.0.7 | PASS | - |
| 311 | AS-LEAF2 | Routing Table | Remote Lo0 address | 198.18.0.8 | PASS | - |
| 312 | AS-LEAF2 | Routing Table | Remote Lo0 address | 198.18.0.5 | PASS | - |
| 313 | AS-LEAF2 | Routing Table | Remote Lo0 address | 198.18.0.6 | PASS | - |
| 314 | AS-LEAF2 | Routing Table | Remote Lo0 address | 198.18.0.9 | PASS | - |
| 315 | AS-LEAF2 | Routing Table | Remote Lo0 address | 198.18.0.10 | PASS | - |
| 316 | AS-LEAF2 | Routing Table | Remote Lo0 address | 198.18.0.1 | PASS | - |
| 317 | AS-LEAF2 | Routing Table | Remote Lo0 address | 198.18.0.2 | PASS | - |
| 318 | AS-LEAF3 | Routing Table | Remote Lo0 address | 198.18.10.7 | PASS | - |
| 319 | AS-LEAF3 | Routing Table | Remote Lo0 address | 198.18.10.8 | PASS | - |
| 320 | AS-LEAF3 | Routing Table | Remote Lo0 address | 198.18.10.5 | PASS | - |
| 321 | AS-LEAF3 | Routing Table | Remote Lo0 address | 198.18.10.6 | PASS | - |
| 322 | AS-LEAF3 | Routing Table | Remote Lo0 address | 198.18.10.9 | PASS | - |
| 323 | AS-LEAF3 | Routing Table | Remote Lo0 address | 198.18.10.10 | PASS | - |
| 324 | AS-LEAF3 | Routing Table | Remote Lo0 address | 198.18.10.1 | PASS | - |
| 325 | AS-LEAF3 | Routing Table | Remote Lo0 address | 198.18.10.2 | PASS | - |
| 326 | AS-LEAF3 | Routing Table | Remote Lo0 address | 198.18.0.7 | PASS | - |
| 327 | AS-LEAF3 | Routing Table | Remote Lo0 address | 198.18.0.8 | PASS | - |
| 328 | AS-LEAF3 | Routing Table | Remote Lo0 address | 198.18.0.5 | PASS | - |
| 329 | AS-LEAF3 | Routing Table | Remote Lo0 address | 198.18.0.6 | PASS | - |
| 330 | AS-LEAF3 | Routing Table | Remote Lo0 address | 198.18.0.9 | PASS | - |
| 331 | AS-LEAF3 | Routing Table | Remote Lo0 address | 198.18.0.10 | PASS | - |
| 332 | AS-LEAF3 | Routing Table | Remote Lo0 address | 198.18.0.1 | PASS | - |
| 333 | AS-LEAF3 | Routing Table | Remote Lo0 address | 198.18.0.2 | PASS | - |
| 334 | AS-DCI1 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-DCI1 - 198.18.10.7 Destination: 198.18.10.7 | PASS | - |
| 335 | AS-DCI1 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-DCI1 - 198.18.10.7 Destination: 198.18.10.8 | PASS | - |
| 336 | AS-DCI1 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-DCI1 - 198.18.10.7 Destination: 198.18.10.5 | PASS | - |
| 337 | AS-DCI1 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-DCI1 - 198.18.10.7 Destination: 198.18.10.6 | PASS | - |
| 338 | AS-DCI1 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-DCI1 - 198.18.10.7 Destination: 198.18.10.9 | PASS | - |
| 339 | AS-DCI1 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-DCI1 - 198.18.10.7 Destination: 198.18.10.10 | PASS | - |
| 340 | AS-DCI1 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-DCI1 - 198.18.10.7 Destination: 198.18.10.1 | PASS | - |
| 341 | AS-DCI1 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-DCI1 - 198.18.10.7 Destination: 198.18.10.2 | PASS | - |
| 342 | AS-DCI1 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-DCI1 - 198.18.10.7 Destination: 198.18.0.7 | PASS | - |
| 343 | AS-DCI1 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-DCI1 - 198.18.10.7 Destination: 198.18.0.8 | PASS | - |
| 344 | AS-DCI1 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-DCI1 - 198.18.10.7 Destination: 198.18.0.5 | PASS | - |
| 345 | AS-DCI1 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-DCI1 - 198.18.10.7 Destination: 198.18.0.6 | PASS | - |
| 346 | AS-DCI1 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-DCI1 - 198.18.10.7 Destination: 198.18.0.9 | PASS | - |
| 347 | AS-DCI1 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-DCI1 - 198.18.10.7 Destination: 198.18.0.10 | PASS | - |
| 348 | AS-DCI1 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-DCI1 - 198.18.10.7 Destination: 198.18.0.1 | PASS | - |
| 349 | AS-DCI1 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-DCI1 - 198.18.10.7 Destination: 198.18.0.2 | PASS | - |
| 350 | AS-DCI2 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-DCI2 - 198.18.10.8 Destination: 198.18.10.7 | PASS | - |
| 351 | AS-DCI2 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-DCI2 - 198.18.10.8 Destination: 198.18.10.8 | PASS | - |
| 352 | AS-DCI2 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-DCI2 - 198.18.10.8 Destination: 198.18.10.5 | PASS | - |
| 353 | AS-DCI2 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-DCI2 - 198.18.10.8 Destination: 198.18.10.6 | PASS | - |
| 354 | AS-DCI2 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-DCI2 - 198.18.10.8 Destination: 198.18.10.9 | PASS | - |
| 355 | AS-DCI2 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-DCI2 - 198.18.10.8 Destination: 198.18.10.10 | PASS | - |
| 356 | AS-DCI2 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-DCI2 - 198.18.10.8 Destination: 198.18.10.1 | PASS | - |
| 357 | AS-DCI2 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-DCI2 - 198.18.10.8 Destination: 198.18.10.2 | PASS | - |
| 358 | AS-DCI2 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-DCI2 - 198.18.10.8 Destination: 198.18.0.7 | PASS | - |
| 359 | AS-DCI2 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-DCI2 - 198.18.10.8 Destination: 198.18.0.8 | PASS | - |
| 360 | AS-DCI2 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-DCI2 - 198.18.10.8 Destination: 198.18.0.5 | PASS | - |
| 361 | AS-DCI2 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-DCI2 - 198.18.10.8 Destination: 198.18.0.6 | PASS | - |
| 362 | AS-DCI2 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-DCI2 - 198.18.10.8 Destination: 198.18.0.9 | PASS | - |
| 363 | AS-DCI2 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-DCI2 - 198.18.10.8 Destination: 198.18.0.10 | PASS | - |
| 364 | AS-DCI2 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-DCI2 - 198.18.10.8 Destination: 198.18.0.1 | PASS | - |
| 365 | AS-DCI2 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-DCI2 - 198.18.10.8 Destination: 198.18.0.2 | PASS | - |
| 366 | AS-LEAF1 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF1 - 198.18.10.5 Destination: 198.18.10.7 | PASS | - |
| 367 | AS-LEAF1 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF1 - 198.18.10.5 Destination: 198.18.10.8 | PASS | - |
| 368 | AS-LEAF1 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF1 - 198.18.10.5 Destination: 198.18.10.5 | PASS | - |
| 369 | AS-LEAF1 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF1 - 198.18.10.5 Destination: 198.18.10.6 | PASS | - |
| 370 | AS-LEAF1 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF1 - 198.18.10.5 Destination: 198.18.10.9 | PASS | - |
| 371 | AS-LEAF1 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF1 - 198.18.10.5 Destination: 198.18.10.10 | PASS | - |
| 372 | AS-LEAF1 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF1 - 198.18.10.5 Destination: 198.18.10.1 | PASS | - |
| 373 | AS-LEAF1 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF1 - 198.18.10.5 Destination: 198.18.10.2 | PASS | - |
| 374 | AS-LEAF1 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF1 - 198.18.10.5 Destination: 198.18.0.7 | PASS | - |
| 375 | AS-LEAF1 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF1 - 198.18.10.5 Destination: 198.18.0.8 | PASS | - |
| 376 | AS-LEAF1 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF1 - 198.18.10.5 Destination: 198.18.0.5 | PASS | - |
| 377 | AS-LEAF1 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF1 - 198.18.10.5 Destination: 198.18.0.6 | PASS | - |
| 378 | AS-LEAF1 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF1 - 198.18.10.5 Destination: 198.18.0.9 | PASS | - |
| 379 | AS-LEAF1 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF1 - 198.18.10.5 Destination: 198.18.0.10 | PASS | - |
| 380 | AS-LEAF1 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF1 - 198.18.10.5 Destination: 198.18.0.1 | PASS | - |
| 381 | AS-LEAF1 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF1 - 198.18.10.5 Destination: 198.18.0.2 | PASS | - |
| 382 | AS-LEAF2 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF2 - 198.18.10.6 Destination: 198.18.10.7 | PASS | - |
| 383 | AS-LEAF2 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF2 - 198.18.10.6 Destination: 198.18.10.8 | PASS | - |
| 384 | AS-LEAF2 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF2 - 198.18.10.6 Destination: 198.18.10.5 | PASS | - |
| 385 | AS-LEAF2 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF2 - 198.18.10.6 Destination: 198.18.10.6 | PASS | - |
| 386 | AS-LEAF2 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF2 - 198.18.10.6 Destination: 198.18.10.9 | PASS | - |
| 387 | AS-LEAF2 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF2 - 198.18.10.6 Destination: 198.18.10.10 | PASS | - |
| 388 | AS-LEAF2 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF2 - 198.18.10.6 Destination: 198.18.10.1 | PASS | - |
| 389 | AS-LEAF2 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF2 - 198.18.10.6 Destination: 198.18.10.2 | PASS | - |
| 390 | AS-LEAF2 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF2 - 198.18.10.6 Destination: 198.18.0.7 | PASS | - |
| 391 | AS-LEAF2 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF2 - 198.18.10.6 Destination: 198.18.0.8 | PASS | - |
| 392 | AS-LEAF2 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF2 - 198.18.10.6 Destination: 198.18.0.5 | PASS | - |
| 393 | AS-LEAF2 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF2 - 198.18.10.6 Destination: 198.18.0.6 | PASS | - |
| 394 | AS-LEAF2 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF2 - 198.18.10.6 Destination: 198.18.0.9 | PASS | - |
| 395 | AS-LEAF2 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF2 - 198.18.10.6 Destination: 198.18.0.10 | PASS | - |
| 396 | AS-LEAF2 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF2 - 198.18.10.6 Destination: 198.18.0.1 | PASS | - |
| 397 | AS-LEAF2 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF2 - 198.18.10.6 Destination: 198.18.0.2 | PASS | - |
| 398 | AS-LEAF3 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF3 - 198.18.10.9 Destination: 198.18.10.7 | PASS | - |
| 399 | AS-LEAF3 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF3 - 198.18.10.9 Destination: 198.18.10.8 | PASS | - |
| 400 | AS-LEAF3 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF3 - 198.18.10.9 Destination: 198.18.10.5 | PASS | - |
| 401 | AS-LEAF3 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF3 - 198.18.10.9 Destination: 198.18.10.6 | PASS | - |
| 402 | AS-LEAF3 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF3 - 198.18.10.9 Destination: 198.18.10.9 | PASS | - |
| 403 | AS-LEAF3 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF3 - 198.18.10.9 Destination: 198.18.10.10 | PASS | - |
| 404 | AS-LEAF3 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF3 - 198.18.10.9 Destination: 198.18.10.1 | PASS | - |
| 405 | AS-LEAF3 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF3 - 198.18.10.9 Destination: 198.18.10.2 | PASS | - |
| 406 | AS-LEAF3 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF3 - 198.18.10.9 Destination: 198.18.0.7 | PASS | - |
| 407 | AS-LEAF3 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF3 - 198.18.10.9 Destination: 198.18.0.8 | PASS | - |
| 408 | AS-LEAF3 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF3 - 198.18.10.9 Destination: 198.18.0.5 | PASS | - |
| 409 | AS-LEAF3 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF3 - 198.18.10.9 Destination: 198.18.0.6 | PASS | - |
| 410 | AS-LEAF3 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF3 - 198.18.10.9 Destination: 198.18.0.9 | PASS | - |
| 411 | AS-LEAF3 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF3 - 198.18.10.9 Destination: 198.18.0.10 | PASS | - |
| 412 | AS-LEAF3 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF3 - 198.18.10.9 Destination: 198.18.0.1 | PASS | - |
| 413 | AS-LEAF3 | Loopback0 Reachability | Loopback0 Reachability | Source: AS-LEAF3 - 198.18.10.9 Destination: 198.18.0.2 | PASS | - |