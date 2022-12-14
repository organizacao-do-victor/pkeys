# Chaves Públicas

Bota as chave pública ai com formato .pub 

Chaves públicas devem ser o arquivo ```~/.ssh/id_rsa.pub``` . **Não é o arquivo ```~/.ssh/id_rsa```**(essa é a chave privada)

Se não existir um par deve ser gerado com o comando ```ssh-keygen```. (Só dar enter e deixar tudo padrão)

## uso 
- baixa tudo 
- ```cat *.pub > authorized_keys ```
- coloca esse authorized_keys na pasta ~/.ssh da máquina (de preferência com ansible) 

Agora todo mundo pode acessar por ssh sem precisar de senha ou chave privada compartilhada 
