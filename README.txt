Para utilizar el código se debe de entrar a la carpeta code, una vez dentro se debe de realizar 
la operación make el cual compila todo el código, una vez compilado se debe de ejecutar de la siguiente forma
./run.sh, en el caso de que la forma de ejecutar no funcione, se deben de dar permisos al run.sh con el siguiente comando
chmod 700 run.sh. Una vez listo lo anterior se puede trabajar con el código, para trabajar se debe de realizar de la siguiente manera:

./run <P> <N> 

, donde <P>: cantidad de procesos a utilizar, <N>: cantidad de de número aleatorios a sumar. El script run.sh es un cargador que tiene las llamadas correctar a MPI para ejecutar su programa.

Ejemplo de uso:

./run.sh 16 50000000
