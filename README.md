https://www.youtube.com/watch?v=VB29kjSOp7E&ab_channel=PhilipDiLeo

Roles documentation


Run `ansible-playbook -i hosts global.yml`
- calls subsystems/*.yml
    - points to `host-vars`
        - execution is done by roles:


### Eos_purge
- when executing tasks, if running `eos-purge`, it can reconcile configs (return them to a **baseline**)

### eos_config
- use this to go through config and change config states using regex
- cannot run run `non-idempotent` commands (????)

### eos_facts
gather info from a switch

### eos_ping
run pings
```yaml

```

### debug
-

### eos_command
