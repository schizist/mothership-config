# mothership restore notes

Important mounts:
- /mnt/fast
- /mnt/bulk

Frigate:
- config lives in /home/gort/frigate/config
- media lives in /mnt/bulk/frigate/media

Pi-hole:
- main config: /etc/pihole/pihole.toml
- custom dnsmasq snippets: /etc/dnsmasq.d

Klipper:
- printer config lives in /home/gort/printer_data/config

After a rebuild:
1. restore mounts in /etc/fstab
2. restore docker/frigate compose
3. restore Pi-hole config
4. restore printer_data/config
5. restore systemd overrides if needed
