# fedora-personal-postinstall

fedora-personal-postinstall is ansible post install playbook I wrote to standardize local builds for fedora 28.

## Requirements
ansible 2.7.5+

## Usage

Update blockheight_start in monerowin-csvout.py with desired starting block height. Then start monerowin-csvout.py. This will generate a blocks.csv file.

```bash
ansible-playbook fedora_postinstall.yml
```
