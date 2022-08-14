# Mi maquina virtual
### Aca les dejo la guia completa de como hice mi maquina virtual para hack the box y para practicar mis cursos de programacion y pentesting en general 


*Nota:* **Esta maquina la hice yo para mi es mi configuracion personal para utilizar en el dia a dia, puede que a algunos les guste y a otros no**

# Primera parte

## Instalando virtual box


Vamos a entrar en la web oficial de Virtualbox y vamos a descargar el binario para la plataforma que sea que tengamos, en mi caso windows 

<https://www.virtualbox.org/wiki/Downloads>

![alt text](https://github.com/isat-lab/isat-lab.github.io/blob/048b712daf1f89c36da4bb86a7272af3e99160a3/_posts/imagenes%20apra%20el%20markdown%20de%20mi%20primera%20maquina%20virtual/Virtualbox_download.jpeg "Virtualbox_download")

## Vamos a crear la maquina

**Nota: Para que la maquina virtual funcione tienen que tener activada la virtualizacion desde el bios en su maquina, como en todos los sistemas se hace de una forma distinta, no lo voy a poner y cada uno va a tener que hacerlo por su cuenta, es facil igual**

* Abrimos virtualbox y le damos al boton de nueva 

![alt text](https://github.com/isat-lab/isat-lab.github.io/blob/f450652abf9e610b8c78440dc260ea70ceabd0de/_posts/imagenes%20apra%20el%20markdown%20de%20mi%20primera%20maquina%20virtual/maquina%20nueva,%20boton%20nueva.jpeg "boton maquina nueva")

* Se abre una nueva ventana, vamos a completar con los siguientes datos: 
- Nombre: El que mas te guste
- Carpeta maquina: Lo que pone por defecto
- Tipo: linux
- Version: Debian de 64 bits
Y le damos a siguiente

![alt text](https://github.com/isat-lab/isat-lab.github.io/blob/f450652abf9e610b8c78440dc260ea70ceabd0de/_posts/imagenes%20apra%20el%20markdown%20de%20mi%20primera%20maquina%20virtual/interfaz%20de%20nueva%20maquina.jpeg "interfaz de maquina nueva")

* Asignamos 6 gb de ram y le damos a siguente

![alt text](https://github.com/isat-lab/isat-lab.github.io/blob/f450652abf9e610b8c78440dc260ea70ceabd0de/_posts/imagenes%20apra%20el%20markdown%20de%20mi%20primera%20maquina%20virtual/asignamos%20la%20ram,%206%20gigas.jpeg "asignamos la ram y le damos 6 gb")

* Dejamos seleccionado crear un disco virtual ahora y le damos a crear

![alt text](https://github.com/isat-lab/isat-lab.github.io/blob/f450652abf9e610b8c78440dc260ea70ceabd0de/_posts/imagenes%20apra%20el%20markdown%20de%20mi%20primera%20maquina%20virtual/creamos%20disco%20duro%20virtual.jpeg "crear disco virtual")

* En tipo de disco VDI (Virtualbox Disk Image) y le damos a next

![alt text](https://github.com/isat-lab/isat-lab.github.io/blob/f450652abf9e610b8c78440dc260ea70ceabd0de/_posts/imagenes%20apra%20el%20markdown%20de%20mi%20primera%20maquina%20virtual/tipo%20de%20disco%20virtual%20disk%20image%20vdi.jpeg "tipo de disco vdi")

* En Almacenamiento un unidad de disco duro fisica dejamos tildado Reservado dinamicamente

![alt text](https://github.com/isat-lab/isat-lab.github.io/blob/f450652abf9e610b8c78440dc260ea70ceabd0de/_posts/imagenes%20apra%20el%20markdown%20de%20mi%20primera%20maquina%20virtual/reservado%20dinamicamente.jpeg "Reservado dinamicamente")

* Le asignamos 80 gigas de espacio 

![alt text](https://github.com/isat-lab/isat-lab.github.io/blob/f450652abf9e610b8c78440dc260ea70ceabd0de/_posts/imagenes%20apra%20el%20markdown%20de%20mi%20primera%20maquina%20virtual/con%2080%20gigas%20de%20espacio.jpeg "80 gigas")

* Ya esta lista la maquina virtual, le damos al boton de crear

En este punto ya nos va a aparecer nuestra maquina virtual, pero todavia no esta lista, vamos a seleccionar nuestra maquina y le vamos a dar click al boton de configuracion para poder terminar los ultimos detalles 

![alt text](https://github.com/isat-lab/isat-lab.github.io/blob/f450652abf9e610b8c78440dc260ea70ceabd0de/_posts/imagenes%20apra%20el%20markdown%20de%20mi%20primera%20maquina%20virtual/seleccionamos%20la%20maquina%20que%20se%20creo%20y%20le%20damos%20a%20configuraciones.jpeg "boton de configuracion")
