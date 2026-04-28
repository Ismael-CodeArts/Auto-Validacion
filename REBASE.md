##FASES DEL PROCESO

* **Fase de Generación:** Se ha creado un archivo llamado pruebas.txt donde se realiza 3 commit descriptivos ("Cambios", "Arreglos", "Actualizazión de las cosas")
* **Fase de Integración:** Ejecutamos git rebase -i HEAD~3 en el que se nos abre un editor donde modificamos solo los dos últimos commits(quitamos pick y ponemos squash) para hacer cambios en el historial .
* **Fase de Renombrado:** Aquí escribimos un mensaje para un único commit (Tarea 5:Limpieza de commit)
* **Fase de Sincronización Forzada:** Para subir los cambios a GitHub con la nueva estructura del historial de  commits ejecutamos git push origin main --force.

