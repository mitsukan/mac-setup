# Mac Ansible playbook
This is written to set up a fresh install of MacOS.

## Pre-requisites
1. Install X-Code: `xcode-select --install`
2. `export PATH="$HOME/Library/Python/3.8/bin:/opt/homebrew/bin:$PATH"`
3. `sudo pip3 install --upgrade pip`
4. `sudo pip3 install ansible`
5. `ansible-playbook main.yml`