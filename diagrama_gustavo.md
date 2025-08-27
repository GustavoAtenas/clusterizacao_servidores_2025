# Mininet Aula 0
## Diagrama da Rede

### 1.

```mermaid
graph LR
    PC1 --- PC2
    PC2 --- PC3
    PC3 --- PC4
    PC4 --- PC5
    PC5 --- PC6
    PC6 --- PC1
```

### 2.
"s1 = net.addSwitch('s1', cls=OVSSwitch)"

### 3.
"h1 = net.addHost('h1')"

### 4.
"c0 = net.addController('c0', controller=RemoteController, ip='127.0.0.1', port=6633)"

