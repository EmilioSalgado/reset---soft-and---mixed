#Diferencia entre reset --soft y reset --mixed

###**La diferencia entre --mixed y --soft es si si o no se modifica el indice. Por tanto si estamos en la rama master con esta serie de commits:**

###**- A -B -C (master)**

###**HEAD apunta a C y el indice esta emparejado con C**
###**Cuando corremos git reset --soft B, master ahora apunta a B, pero el indice todavía tiene los cambios de C. Si corremos git reset --mixed B, de nuevo master apunta a B, pero en esta ocación el indice tambien cambia para coincidir con B**

![alt text](https://github.com/EmilioSalgado/reset---soft-and---mixed/blob/master/image.jpg "Imagen de la tarea")
