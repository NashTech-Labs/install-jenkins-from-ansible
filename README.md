# Ansible Playbook: Install Jenkins

## Overview

This Ansible playbook is designed to install Jenkins on a target server. It performs the following tasks:

1. Updates the system packages.
2. Installs OpenJDK 11.
3. Installs necessary packages (wget).
4. Adds the Jenkins apt key.
5. Adds the Jenkins apt repository.
6. Installs Jenkins.
7. Starts the Jenkins service.

## Requirements

- Ansible installed on the machine running the playbook.
- A target server .

## Usage

1. Clone the repository:

   ```bash
   git clone <repository-url>
2. Change directory:
   ```bash
   cd <playbook-directory>
3. Run playbook:
   ```bash
   ansible-playbook -i <path-to-inventory-file> <path-to-playbook-file>
