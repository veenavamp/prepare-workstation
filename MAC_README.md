# prepare-workstation

## Install GIT BASH (windows)

### INSTALLING CHOCOLATEY

#### Install with powershell.exe in admin mode

```

Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))

```

if you don't see any errors, you are ready to use Chocolatey! Type choco or choco -?

Ref: https://chocolatey.org/install

#### Install GIT using chocolatey

```
choco install git.install
```

ref: https://community.chocolatey.org/packages/git.install

#### install Terraform:

Open git bash or powershell in admin mode and run the below command.

```
choco install terraform
```

#### install AWS cli:

Open git bash or powershell in admin mode and run the below command.

```
Choco install awscli
```

#### install eksctl:

```

choco install eksctl

```

### Install helm

```

choco install kubernetes-helm

``





