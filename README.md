# Cisco Router Configuration Backup (Packet Tracer)

This is a step-by-step project that shows how to:
- Configure a Cisco router (Router0)
- Save its configuration
- Back it up to a TFTP server
- Restore it to another router (Router1)

---

## 🧱 IP Address Plan

| Device     | Interface | IP Address  |
|------------|-----------|-------------|
| Router0    | G0/0      | 10.0.0.1    |
| Server     | FA0       | 10.0.0.2    |
| Router1    | G0/0      | 10.0.0.3    |

---

## 📁 Files Included

| File                         | Description                            |
|------------------------------|----------------------------------------|
| `router0_initial_config.txt` | Config commands for Router0            |
| `backup_to_tftp.txt`         | Steps to back up config to TFTP server |
| `restore_to_router1.txt`     | Steps to restore config on Router1     |
| `config-backup.png`          | Network diagram image                  |
| `.pkt` file                  | Packet Tracer file                     |

---

## 🔁 Basic Steps

1. Configure Router0
2. Save and back up its configuration to TFTP server at `10.0.0.2`
3. Copy that config from TFTP to Router1
4. Reload Router1 and verify

---

## 🛠 Tools Used

- Cisco Packet Tracer
