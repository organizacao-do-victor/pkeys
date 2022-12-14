# Chaves Públicas

Bota as chave pública ai com formato .pub 

Chaves públicas devem ser o arquivo "\~/.ssh/id_rsa.pub" , **não é o arquivo "~/.ssh/id_rsa"**(essa é a chave privada)

## uso 
- baixa tudo 
- cat *.pub > authorized_keys 
- coloca esse authorized_keys na pasta ~/.ssh da máquina (de preferência com ansible) 

Agora todo mundo pode acessar por ssh sem precisar de senha ou chave privada compartilhada 
