## TroubleShooting for RDS(relational database service)

# Troubleshooting for PostgreSQL

1. pgAdmin cannot connect. 

- Most common problem: Did not set security group. 
- Solution: Set "Security group rules" to include inbound rule "Inbound rules" of type "PostgreSQL". 

2. 
