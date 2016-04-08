# fSMTP

fSMTP - FakeSMTP - https://nilhcem.github.io/FakeSMTP

# Setup

1. Clone repo: `cd $HOME/software && git clone https://github.com/reduardo7/fsmtp.git`
2. Run `cd fsmtp && bash install.sh`

## Fix Slow Start/Send


```bash
u="127.0.0.1"
l="$(cat /etc/hostname)"
if ! grep "$l" /etc/hosts > /dev/null
  then
    sudo bash -c "echo '$u $l' >> /etc/hosts"
  fi
```

# Start

* From Start Menu, search for: `fsmtp`
* From command line: `fsmtp`
