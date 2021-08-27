# kubernetes-alias

This repository contains a script to generate some of convenient shell aliases for kubectl, so you no longer need to spell out every single command and --flag over and over again.

---

## Examples
```bash
# GET
alias k="kubectl"
alias kg="kubectl get"
alias kgp="kubectl get pod"
alias kgd="kubectl get deployment"
alias kgsv="kubectl get services"
alias kgi="kubectl get ingress"

# EDIT
alias ked="kubectl edit deployment"
```

---

## Installation

Clone this repo and save it in your $HOME directory, then edit your .zshrc file with:

`[ -f ~/kubernetes-alias/script ] && source ~/kubernetes-alias/script`

---

## Syntax explanation

- **`k`** = `kubectl`

- commands:
  - **`g`** = `get`
  - **`e`** = `edit`

---

This is not an official Google project.
