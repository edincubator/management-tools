# EDI management-tools

## Usage

´´´console
    ansible-playbook --private-key <private-key> -i hosts playbook.yml -e username=<username-to-create> -e ldap_bind_password=<ldap-bind-password> -e kerberos_admin_password=<kerberos-admin-password>
´´´