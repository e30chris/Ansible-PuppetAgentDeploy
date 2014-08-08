Ansible-PuppetAgentDeploy
=========================

## The Goal: Deploy Puppet Agent using Ansible.

_Ensure Puppet Agent is installed and running on a server._

Variables

Go here:

```
group_vars/all
```

With this format:

```
variable: value
```

### Common Tasks:

  * Create Puppet Answers file
  
  * Create install log
  
  * Install system package pre-requirements (yum)
  
  * Deploy Puppet yum repo file
  
  * Install gpg keys
  
  * Install Puppet Agent
  
  * Install Puppet Agent Service
  
  * Run Puppet Agent in noop mode




