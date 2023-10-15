# encriptar fichero
ansible-vault encrypt --ask-vault-pass --output fichero.encrypt fichero.conf

# conf en awx

En credenciales , crear una credencial de tipo vault , con el password para desencriptar.

En la plantilla , asignar el main.yaml (playbook) y adjuntar la credencial de tipo vault creada en la plantilla. (el playbook , el modulo copy usara el password gracias al parametro 'decrypt' indicado en el modulo copy.)