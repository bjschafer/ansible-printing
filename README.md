# Ansible Collection - cmdcentral.printing

Ansible role collection for managing a 3D printing Raspberry Pi

## Setup

Create a new virtualenv and install packages:

```bash
python3 -m venv ./venv
source venv/bin/activate

pip install -r requirements.txt
```

## Basic usage

Create a playbook that includes your selection of the `klipper`, `moonraker`, and `fluidd` roles.

Explore the variable in `roles/*/defaults/main.yml`. Sensible defaults are set for many things, but you may
wish to change things to fit your environment.

## Help, issues, stability

This is provided as best effort. I'm developing it for my own usage and this informs many design decisions.

If something is broken or missing, please feel free to file an issue, or even to submit a PR! I can't promise I'll
include it, but I'm always happy to take a look.
