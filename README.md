# Ansible AWS VPC Setup

Infrastructure-as-code project using Ansible to provision an AWS VPC with a bastion host for secure access management.

## What it does

- Provisions a custom AWS VPC using Ansible playbooks
- Deploys and configures a bastion host instance for secure SSH access into the private network
- Configures security groups to control and restrict access to the bastion host

## Tech Stack

- **Ansible** – infrastructure automation
- **AWS** – VPC, EC2 (bastion host), Security Groups

## Structure

- `vpc_setup.yml` – provisions the VPC and networking components
- `bastion_instance.yml` – deploys and configures the bastion host
- `vars/` – variable definitions for reusable, environment-specific configuration

## Why I built this

To practice infrastructure automation with Ansible in a real AWS environment, focused on secure network access patterns (VPC isolation + bastion host as a controlled entry point) commonly used in production cloud architectures.
