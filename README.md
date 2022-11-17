# SpringBoot-LDAP
Spring boot security using LDAP


### LDAP endpoint
    
    'ldap://localhost:8389/dc=springframework,dc=org', root DN is 'dc=springframework,dc=org'

### Application end point 
	
    http://localhost:9090/users/info
	username : ben
	password : benspassword


    Username and password is present in test-server.ldif. Password is encoded using LdapShaPasswordEncoder. 
    See the below uid for userName and userPassword

    dn: uid=ben,ou=people,dc=springframework,dc=org
    objectclass: top
    objectclass: person
    objectclass: organizationalPerson
    objectclass: inetOrgPerson
    cn: Ben Alex
    sn: Alex
    uid: ben
    userPassword: {SHA}nFCebWjxfaLbHHG1Qk5UU4trbvQ=



