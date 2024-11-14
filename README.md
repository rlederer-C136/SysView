## **Running with Profiles**

### **On Linux (Ubuntu/WSL2)**

**Use the linux profile to enable network_mode: host and GPU support, starts with console logging**
```sh
$ docker compose --profile linux up
```

**Use the linux profile to enable network_mode: host and GPU support, starts detached, no console logging**
```sh
$ docker compose --profile linux up -d
```

### **On macOS or Windows**

**The services will use the default profile and map the necessary ports**
```sh
$ docker compose up
```
or
```sh
$ docker compose up -d
```

This approach allows a single Docker Compose file that works across Linux, macOS, and Windows, adapting to the platform's specific needs via profiles and network configuration.

Access Grafana @ `127.0.0.1:3000` or `MACHINE_IP_ADDRESS:3000`
**user:** `admin`
**pass:** `admin`

Grafana will ask you to change the default admin password on first login. Please do so.

![Glances on Grafana](https://github.com/rlederer-C136/SysView/blob/main/SysView.png?raw=true)
