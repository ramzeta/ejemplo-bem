# ejemplo-bem

En este caso, creamos un objeto STARTUPINFO vacío y configuramos su propiedad dwFlags para incluir el valor STARTF_USESHOWWINDOW. Esto indica que se debe usar la propiedad wShowWindow para determinar cómo se muestra la ventana de la consola. Luego, al llamar a check_output, pasamos este objeto STARTUPINFO al parámetro startupinfo.