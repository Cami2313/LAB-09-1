# LAB 9
# CAMBIO SEGUN TSX
***
Uno de los cambios que podemos observar es al inicializar el proyecto :  
**yarn create vite lab-9**  
**[1/4] Resolving packages...**  
**[2/4] Fetching packages...**  
**[3/4] Linking dependencies...**  
**[4/4] Building fresh packages...**  
**success Installed "create-vite@5.2.3" with binaries:**  
      **- create-vite**  
      **- cva**  
**√ Select a framework: » React**  
**√ Select a variant: » TypeScript**  
En este caso debemos eligir React como framework y TypeScript como lenguaje.
***
Sin embargo, el cambio principal para adaptar el proyecto a TypeScript es la introducción de tipado. En nuestro caso, basándonos en la API, la estructura de los productos se vería de la siguiente manera:  
**export interface Product {**  
    **id: number;**  
    **title: string;**  
    **description: string;**  
    **price: number;**  
    **discountPercentage: number;**  
    **rating: number;**  
    **stock: number;**  
    **brand: string;**  
    **category: string;**  
    **thumbnail: string;**  
    **images: string[];**  
**}**  
Esto define la estructura de datos que esperamos recibir de nuestra API, asegurando consistencia y facilitando el trabajo con los datos en nuestro proyecto.
