---
sidebar_position: 4
title: Systemd
---

```sh
systemctl status
systemctl list-dependencies 
systemd-analyzer critical-chain --fuzz 1h
systemd-analyze plot > something.svg
systemd-analyze dot | dot -Tpng -o stuff.png
```

