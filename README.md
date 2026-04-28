# How To Setup OpenClaw (Complete Setup)🔥

### System Requirements

| Feature          | Minimum Requirement      | Recommended              |
| :--------------- | :----------------------- | :----------------------- |
| **OS** | Ubuntu 20.04 LTS         | Ubuntu 22.04 LTS or newer|
| **Git** | Version 2.25+            | Latest Stable            |


## Enable WSL In Ubuntu

# Setting Up

### First Open Powershell as administator Then Run this command : 
```bash
wsl --install -d ubuntu
```
then :
```bash
wsl -d ubuntu
```
# Installing
----------------------------------------------------------------

### Now For Installing paste this command : 

```bash
curl -fsSL https://openclaw.ai/install.sh | bash
```

### Then Verify : 
```bash
openclaw --version
```

# Setting OpenClaw

## So now we have to setup the openclaw - run this command in your powershell

```bash
openclaw onboard --install-daemon
```
