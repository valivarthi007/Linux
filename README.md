# Linux
Linux System Administration 

# ✅ Comprehensive Linux Administrator  (L1–L4)

Covers: Fundamentals → Expert-Level Skills, Tooling, Monitoring, Troubleshooting & Automation

---

## 🔹 L1 – Beginner (Junior Admin / Support Technician)

### 📘 Basics & Environment
- [ ] Linux distributions & architecture (kernel, shell, init/systemd)
- [ ] File system layout: `/etc`, `/var`, `/usr`, `/tmp`, `/home`
- [ ] Basic shell usage (`bash`, `sh`)
- [ ] Essential commands: `ls`, `cd`, `cp`, `mv`, `rm`, `touch`, `mkdir`
- [ ] Redirection and piping: `>`, `>>`, `<`, `|`
- [ ] File viewing/editing: `cat`, `less`, `more`, `nano`, `vim`

### 👥 User & Group Management
- [ ] `useradd`, `usermod`, `userdel`, `passwd`
- [ ] `groupadd`, `gpasswd`, `id`, `groups`
- [ ] Sudo privileges and `/etc/sudoers`

### 📦 Package Management
- [ ] Debian-based: `apt`, `dpkg`
- [ ] RHEL-based: `yum`, `dnf`, `rpm`
- [ ] Adding/removing repositories

### 🖥️ System Monitoring Basics
- [ ] Uptime and load: `uptime`, `top`, `htop`
- [ ] Memory: `free`, `vmstat`
- [ ] Disk: `df`, `du`, `lsblk`, `mount`
- [ ] Process control: `ps`, `kill`, `nice`, `renice`

### 🛠️ Essential Tools
- [ ] `curl`, `wget`, `scp`, `rsync`, `file`, `stat`
- [ ] `screen`, `tmux`, `watch`, `alias`

### 🧩 Basic Troubleshooting
- [ ] Checking logs: `/var/log/`, `journalctl`, `dmesg`
- [ ] Service checks: `systemctl status`, `service --status-all`
- [ ] Network tests: `ping`, `traceroute`, `host`, `nslookup`

---

## 🔹 L2 – Intermediate (System Administrator)

### 🛠️ System Services & Scheduling
- [ ] Managing services: `systemctl start/stop/enable/disable`
- [ ] Logs: `journalctl`, persistent logs
- [ ] Scheduled tasks: `cron`, `crontab`, `at`, `anacron`

### 💾 Disk & Storage Management
- [ ] Partitioning: `fdisk`, `parted`, `lsblk`, `blkid`
- [ ] Filesystems: `ext4`, `xfs`, `btrfs`, `mkfs`, `fsck`
- [ ] Mounting: `mount`, `umount`, `fstab`
- [ ] Swap management: `mkswap`, `swapon`, `swapoff`
- [ ] LVM basics: `pvcreate`, `vgcreate`, `lvcreate`, resizing

### 🌐 Networking Essentials
- [ ] Network interfaces: `ip`, `ifconfig`, `nmcli`
- [ ] DNS and hostname configuration
- [ ] Tools: `ping`, `ss`, `netstat`, `telnet`, `nc`, `curl`, `traceroute`
- [ ] Firewall basics: `ufw`, `firewalld`

### 🔍 Intermediate Troubleshooting
- [ ] Analyzing service failures: `systemctl --failed`, `journalctl -xe`
- [ ] Network troubleshooting: `ethtool`, `ip a`, `tcpdump`
- [ ] Filesystem issues: `fsck`, `tune2fs`, `mount -o remount`

### 📊 Monitoring Tools (GUI + CLI)
- [ ] `htop`, `glances`, `atop`, `nmon`
- [ ] `netdata`, `collectl`, `iotop`, `iostat`

---

## 🔹 L3 – Advanced (Senior Admin / DevOps Engineer)

### 🧠 Advanced Scripting & Automation
- [ ] Bash scripting (functions, loops, conditionals, logging)
- [ ] Advanced scheduling with output logging
- [ ] Automating common admin tasks

### 🚀 Performance Tuning
- [ ] `vmstat`, `iostat`, `iotop`, `mpstat`
- [ ] CPU/memory tuning: `ulimit`, `nice`, `renice`, `top`
- [ ] Kernel tuning: `sysctl`, `/proc`, `/sys`

### 🔐 Security Hardening
- [ ] SELinux/AppArmor: `getenforce`, `setenforce`, `auditd`
- [ ] SSH hardening: port, keys, root login, `sshd_config`
- [ ] Firewalls: `iptables`, `nftables`, `fail2ban`
- [ ] File integrity: `AIDE`, `tripwire`, `md5sum`, `sha256sum`

### 🔧 Backup & Recovery
- [ ] Tools: `rsync`, `tar`, `dd`, `borg`, `restic`
- [ ] Snapshotting: LVM snapshots, Btrfs/ZFS snapshots
- [ ] Backup rotation with `logrotate`

### 🐳 Containers & Virtualization
- [ ] Docker: install, run, volume, network, images
- [ ] KVM, QEMU, libvirt, virt-manager basics
- [ ] `systemd-nspawn`, LXC

### 🔍 Advanced Troubleshooting
- [ ] Boot failures: `grub`, `initrd`, `rescue mode`
- [ ] Kernel issues: `dmesg`, `syslog`, `journalctl -k`
- [ ] Process tracing: `strace`, `lsof`, `fuser`
- [ ] Core dump analysis and `coredumpctl`
- [ ] Log deep-dives: `ausearch`, `auditctl`, `grep`, `awk`, `sed`

---

## 🔹 L4 – Expert (Linux Architect / SRE / Infrastructure Engineer)

### 🌐 Infrastructure Design & High Availability
- [ ] Clustering: `Pacemaker`, `Corosync`, `Keepalived`
- [ ] Load balancing: `HAProxy`, `NGINX`, `IPVS`
- [ ] PXE booting, TFTP/DHCP, provisioning via Kickstart/Preseed

### ⚙️ Configuration Management & CI/CD
- [ ] Ansible: playbooks, inventory, roles, Vault
- [ ] Puppet, Chef, Salt basics
- [ ] CI/CD pipelines: Jenkins, GitHub Actions, GitLab CI

### ☁️ Cloud & Hybrid Linux
- [ ] Linux in AWS/GCP/Azure (EC2, IAM, VPC)
- [ ] SSH key management across clouds
- [ ] Linux image creation, auto-scaling

### 🛡️ Advanced Security & Compliance
- [ ] SELinux custom policy modules
- [ ] Vulnerability scanners: `Lynis`, `OpenVAS`, `ClamAV`
- [ ] Live kernel patching: `kpatch`, `livepatch`
- [ ] Compliance: CIS, NIST, HIPAA hardening

### 🧠 Expert Troubleshooting & Recovery
- [ ] Debugging kernel panics (`kdump`, `crash`, `vmcore`)
- [ ] Live recovery: chroot, live CD, rescue mode
- [ ] Advanced journaling and boot trace: `systemd-analyze`, `bootchart`

---

## 🧰 Tools Summary by Category

| Category          | Tools                                                                 |
|-------------------|------------------------------------------------------------------------|
| Monitoring        | `htop`, `glances`, `nmon`, `netdata`, `collectd`, `atop`              |
| Performance       | `vmstat`, `iostat`, `iotop`, `mpstat`, `sysctl`, `tuned`              |
| Networking        | `ip`, `ss`, `netstat`, `tcpdump`, `ethtool`, `nmcli`, `nmap`          |
| Storage           | `lsblk`, `fdisk`, `parted`, `mount`, `lvm`, `mdadm`, `df`, `du`       |
| Security          | `firewalld`, `iptables`, `fail2ban`, `auditd`, `SELinux`, `AppArmor` |
| Backup/Recovery   | `rsync`, `tar`, `dd`, `borg`, `restic`, `timeshift`                   |
| Troubleshooting   | `journalctl`, `dmesg`, `strace`, `lsof`, `fuser`, `systemctl`         |
| Automation        | `bash`, `cron`, `at`, `Ansible`, `Puppet`, `Jenkins`                  |
| Containers/Virt.  | `docker`, `lxc`, `kvm`, `virt-manager`, `libvirt`                     |
