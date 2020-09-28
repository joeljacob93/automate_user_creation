# create_users
Automating user accounts creation along with SSH keys and hashed passwords



Create SHA512 hashed password using python as below. The hashed password can be added to a sub-directory under ansible as well and called within the yaml script using file lookup as shown in the script for SSH keys

python -c 'import crypt; print(crypt.crypt("Ga.2t8z#n4f?", crypt.mksalt(crypt.METHOD_SHA512)))'
