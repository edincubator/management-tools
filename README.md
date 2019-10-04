# EDI management-tools

## Usage

´´´console
    ansible-playbook --private-key <private-key> -i hosts playbook.yml -e username=<username-to-create> -e ldap_bind_password=<ldap-bind-password> -e kerberos_admin_password=<kerberos-admin-password> -e ranger_url=<ranger-url> -e ranger_username=<ranger-user> -e ranger_password=<ranger-password> -e zookeeper_servers=<zookeeper-servers> -e nifi_url=<nifi-url> -e nifi_username=<nifi-username> -e nifi_password=<nifi-password>
´´´