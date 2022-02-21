# proxmox-lxc-ne
Installation script for installing [Node Exporter Prometheus](https://github.com/prometheus/node_exporter) on all LXC's within Proxmox


On your Proxmox Node run:
1. ```cd ~```

2. ```wget https://raw.githubusercontent.com/hotsoupp/proxmox-lxc-ne/main/proxmox-lxc-node-exporter.sh```

3. ```chmod +x proxmox-lxc-node-exporter.sh```

4. ```./proxmox-lxc-node-exporter.sh```

After this all of your current LXC's running debian/ubuntu should be installed with [Node Exporter Prometheus](https://github.com/prometheus/node_exporter)
