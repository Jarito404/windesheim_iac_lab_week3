## Opdracht 3 — Meerdere groepen in één draaiboek

### Playbook bestand
`playbooks/03_multi_group.yml`

### Beschrijving
- **app** groep: installeert en start `chrony` (NTP service)
- **db** groep: installeert `curl`
- variabelen zijn gedefinieerd in `group_vars/app.yml` en `group_vars/db.yml`

### Uitvoeren
ansible-playbook playbooks/03_multi_group.yml -K

BECOME wachtwoord is hetzelfde als het sudo wachtwoord
