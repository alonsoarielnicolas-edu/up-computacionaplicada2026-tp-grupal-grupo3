# up-computacionaplicada2026-tp-grupal-grupo3



Integrantes:



Notas Varias:
#Para testear el script backup_full.sh utilizar ./ , bash , o /usr/bin/bash , si por error se utiliza sh , a pesar de que el shebang apunte a Bash , utilizara sh por estar forzado desde el comando.

#authorized_keys tiene dos claves autorizadas ya que se utilizo una segunda maquina virtual Linux para acceder de forma segura mediante claves privadas autogeneradas durante la mayor parte del proceso

#El password de root fue cambiado varias veces a lo largo del proceso ya que por exposicion a la red (debido al bridge de virtualbox) , representaba un riesgo de seguridad. La version subida a este github contiene el password solicitado 

#Los directorios fueron descargados utilizando filezilla por sftp . Puede existir alguna diferencia minima en los directorios debido a symlinks de debian y particularidades de la herramienta.


#En el directorio backup_dir pueden existir backups antiguos producto de sucesivas pruebas de los scripts cron en horarios que no son los mismos que pide la consigna . Estos deben ser unicamente considerados como parte del proceso de testing de cron.
