# ansible
An Ansible demo

Ansible is an open-source automation tool that is best used for tasks like DSC (desired state configuration) and IaC (infrastructure as code)

This repo is inteded to serve as an example of how to use Ansible when leveraging GitHub Actions. This repo does its best to implement and document the best practices that are in place.

## Decisions
1. we lint our playbooks on every branch and every push
   - this helps catch issues early in the development process and limits surprises come PR time
1. we structure our directory according to ansible docs
   - https://docs.ansible.com/ansible/latest/tips_tricks/sample_setup.html#alternative-directory-layout

## To-Do
- OIDC?
- 

### For Me
create a ansible.cfg file with
```
[defaults]
interpreter_python = /opt/homebrew/bin/python3
```
if you are getting linting issues