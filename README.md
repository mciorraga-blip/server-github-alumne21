#Servidor a la nuve con GutHub Codespaces - alumno21

##📌 Descripció del projecte
Aquest projecte consisteix en la creació i configuració d’un servidor web utilitzant GitHub Codespaces. He instal·lat Apache, he creat una pàgina pública i una zona privada protegida amb autenticació bàsica. Tot el treball queda documentat i accessible des del repositori.

##🖥️ Màquina virtual integrada (Codespace)
El servidor s’executa dins d’un Codespace, que funciona com una màquina virtual Linux.
Des d’aquí he pogut instal·lar Apache, crear l’estructura de la web, configurar la carpeta privada i provar el funcionament mitjançant la URL pública del port 80.

##🚀 Passos bàsics per posar en marxa el servidor
  1. Obrir el Codespace associat al repositori.
  2. Iniciar Apache si no està actiu:
     sudo service apache2 start
  3. Comprovar que el port 80 està obert a la pestanya Ports.
  4. Accedir a la web pública amb la URL del Codespace.
  5. Accedir a la zona privada afegint /privada al final de la URL.
  6. Si es modifica la configuració, reiniciar Apache:
     sudo service apache2 restart

##📁 Fitxers inclosos al repositori

###El repositori conté:
  - index.html (pàgina pública)
  - privada/index.html (pàgina privada)
  - privat.conf (configuració mínima del lloc)
  - README.md (documentació del projecte)

⚠️ Seguretat
No s’ha pujat cap contrasenya, cap fitxer .htpasswd ni cap clau privada.
Les credencials només existeixen dins del servidor del Codespace.
