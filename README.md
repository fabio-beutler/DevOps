# DevOps

Este trabalho ter por objetivo criar uma infraestrutura com 2 clusters Kubernetes.

Para isso seguiremos as seguintes configurações no roteador Mikrotik

| interface | ip                    | descrição                     |
| --------- | --------------------- | ----------------------------- |
| eth1      | 200.0.35.146          | claro                         |
| eth2      | 192.168.5.1, 10.0.2.1 | viveiros, cloud               |
| eth3      | none                  | rede backup futuro            |
| vpn1      | 192.168.6.1           | vpn para acessar a rede local |

porta mikrotik 48291
