# pochelper - Run an ansible playbook on POC devices.
# When setting up a Poc, you often have a large number of devices to configure. This helper script allows
# you to run the same command or enter the same config on all or a set of devices in the PoC.

usage: pochelper [-h] [--config CONFIG] [--cmd CMD] [-o filename] [-i filename] hosts [hosts ...]

Run an ansible playbook on POC devices.

positional arguments:
  hosts                 which devices to configure or command

optional arguments:
  -h, --help            show this help message and exit
  --config CONFIG       send a configuration to the device in set format
  --cmd CMD, --command CMD
                        send a configuration to the device in set format
  -o filename, --out filename
                        write output to a file
  -i filename, --inventory filename
                        Name of inventory file

# pwp
A briefer 'ip a' command.

(c) Erik Sherk, Natalie Landsberg