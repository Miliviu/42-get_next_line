# 42-get_next_line Spanish
1. Llamar a tu función get_next_line en un bucle te permitirá leer el contenido de
un file descriptor línea a línea hasta el final.
2. Tu función deberá devolver la línea que se acaba de leer. Si no hay nada más que
leer o si ha ocurrido un error, deberá devolver NULL.
3. Asegúrate de que tu función se comporta adecuadamente cuando lea de un archivo
y cuando lea de stdin.
4. Tu programa debe compilar con la flag -D BUFFER_SIZE=xx. Esta flag se utilizará
para determinar el tamaño del buffer de las lecturas de tu get_next_line.
5. En el header get_next_line.h deberás tener como mínimo el prototipo de la función get_next_line.
# 42-get_next_line English
1. Repeated calls (e.g., using a loop) to your get_next_line() function should let
you read the text file pointed to by the file descriptor, one line at a time.
2. Your function should return the line that was read.
If there is nothing else to read or if an error occurred, it should return NULL.
3. Make sure that your function works as expected both when reading a file and when
reading from the standard input.
4. Because you will have to read files in get_next_line(), add this option to your
compiler call: -D BUFFER_SIZE=n
5. Add all the helper functions you need in the get_next_line_utils.c file
