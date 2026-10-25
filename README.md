# Homelab Access & Recovery Automation

Infrastructure engineering portfolio project designing secure access and recovery for a Proxmox and Ubuntu homelab.

The design uses an Ansible-first approach with role-based configuration and small bootstrap scripts for prerequisites. It treats LAN SSH, OpenSSH over Tailscale, and Tailscale SSH as distinct access paths, with independent verification and rollback planning to preserve existing configurations.

**Current phase:** Architecture and design review. Documentation and an Ansible directory skeleton are in place; production automation has not been implemented or deployed.

Project files and internal infrastructure details remain private while the design develops.
