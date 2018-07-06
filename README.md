1. Clone the repo with " git clone"
2. Build image : "docker build -t "imagename" "/path/to/Dockerfile"
3. Run Docker : "docker run "imagename"

Runtime configuration can be provided using environment variables:

LDAP_SERVER_NAME, the LDAP server name, i.e. "ADOP LDAP"
LDAP_SERVER_BASE_DN, the LDAP BASE_DN
LDAP_SERVER_BIND_ID, the LDAP admin bind ID
LDAP_SERVER_HOST, the LDAP server host, i.e. "ldap"
LDAP_SERVER_PORT, the LDAP server port, i.e. "389"
