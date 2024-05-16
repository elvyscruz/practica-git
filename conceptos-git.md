#conceptos:

Ques es git ?
Es un sistema de control de versiones distribuido

ideas claves;
- linea de tiempo compuesta por registros de los cambios (commit) 
  ---commit---commit---commit---commit  

- repositorio -> un directorio con git inicializado

- ramas (branches)
  main->---commit---commit---commit \
  desa->---commit---commit---commit   -> --commit--commit
  test->---commit---commit---commit /
  Para cambiar de rama usamos el comando switch

  * checkout 
(podemos volver a cualquier commit realizado a ver los cambios) 

Para inicializar un directorio de archivos, usamos el comando:
- git init

- staging: significa agregar uno o mas archivos modificados para registrar los cambios