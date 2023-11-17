# Backdoor Project

This Python-based project involves the creation of a backdoor for accessing the file system of a victim's machine connected over the same network.

## Instructions for Testing

Before testing this backdoor on your machine(s), ensure that both devices are connected to the same network.

### Steps:

1. Modify the values in `address.py`:
   - Set the `IP_ADDR` (IP address) of your host machine.
   - Give a preferred `PORT` number.

2. Run `listener.py` on the host machine:
   ```bash
   python listener.py

3. Run `reverse_backdoor.py` on the victim's machine

4. Once the connection is established, You can execute system commands on the victim's machine from your host machine through the backdoor.
