graph BT
  B(sys-firewall):::green --> A(sys-net):::red
  C(personal):::yellow --> B
  D(sys-vpn):::green --> B
  E(work):::blue --> D

  classDef red fill:#e6194b,stroke:#333,stroke-width:1px,color:#ee
  classDef green fill:#3cb44b,stroke:#333,stroke-width:1px,color:#ee
  classDef yellow fill:#ffe119,stroke:#333,stroke-width:1px,color:#aa
  classDef blue fill:#4363d8,stroke:#333,stroke-width:1px,color:#ee
