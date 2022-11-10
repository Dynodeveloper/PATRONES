<h1>Patron Decorator</h1>

<p>Su definicion basica es la generacion de elementos de forma dinamica sin necesidad de definir todas las posibles combinaciones, este nos permite extender comportamientos de forma dinamica</p>

<h2>Ejemplo</h2>

<p>cada decorador viene siendo los comportamientos que agregar a un elemento base o clase, un decorador viene siendo un componente por ende debe de tener herencia de otro componente, lo que nos lleva a algo asi como capas de componentes</p>

<img src="image.png">

<p>en este ejemplo encontramos la clase padre que en este caso es el elemento enemigo de un videojuego, que a su vez hereda a cada enemigo en particular que a su vez lleva un contructor en el cual añadiremos los decoradores como lo pueden ser un casco o una armadura</p>