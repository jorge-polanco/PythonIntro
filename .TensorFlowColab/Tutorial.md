# Tensorflow on Google Collab

Co-authored-by: Fernando Cuervo Ledesma 165972

Co-authored-by: Ximena Vazquez Mellado Flores 171319

Co-authored-by: Jorge Roberto Polanco Dominguez 167325

Co-authored-by: 

Co-authored-by: 

### Introduction
En este tutorial aprenderas a usar la libreria Tensorflow en el ambiente de Google Colab
Aprenderas:
- Que es Google Colab
- Que es TensorFlow
- Como usar TensorFlow en Google Colab
- Pasos para crear una red neuronal

### Que es Google Colab?
Google Colab es un servicio gratuito en la nube que ofrece potentes capacidades informáticas. Permite a los usuarios crear y compartir documentos, hojas de cálculo, presentaciones y más. Es una plataforma fácil de usar con una amplia gama de características, incluida la capacidad de colaborar con otros en tiempo real.

### Limitaciones de Google Colab
Google Colab es una plataforma poderosa, pero tiene algunas limitaciones. La limitación más significativa es la falta de soporte para ciertos lenguajes de programación, como Java y C++. Además, la plataforma está limitada a 12 horas de uso continuo, luego de lo cual se desconectará. Finalmente, la plataforma está limitada a 1 GB de RAM y 5 GB de almacenamiento.

### Que es TensorFlow?
TensorFlow es una plataforma de código abierto integral para el aprendizaje automático, tiene funcionalidades como:
- PREPARAR DATOS (Preprocesamiento de datos)
- CONSTRUIR MODELOS (Pre-entrenados o personalizados)
- IMPLEMENTAR MODELOS

### Instalar la extensión de Google Colab en Google Drive

1- Abre Google Drive y selecciona la opción de "Nuevo" que se encuentra en la parte superior izquierda de la pantalla
![Instalación de Goggle Colaboratory](https://user-images.githubusercontent.com/122324007/223330602-bbfa4ce2-3938-44f4-80a8-36ff6467bd0b.png)

2- Selecciona la opción "más" y selecciona "Conectar más aplicaciones"
![Mas aplicaciones](https://user-images.githubusercontent.com/122324007/223330965-1a87c585-d332-4696-bfc1-5de4bff24368.png)

3- En el buscador, escribe "Colaboratory" y selecciona la primera opción
![image](https://user-images.githubusercontent.com/122324007/223331165-5f185f95-c13b-4ab5-babc-5784ff5682dd.png)

4- Selecciona la opción "Instalar"
![image](https://user-images.githubusercontent.com/122324007/223331738-fd56dad2-adde-4083-a7ba-b5cd6502afb6.png)

5- Das click en "Continuar", seguido de "Hecho"

![image](https://user-images.githubusercontent.com/122324007/223331909-bb3736e2-aa5a-4eb0-959f-ff2d93a0eaf2.png)

Ya estás listo para crear un bloc de notas de Google Colab


###Primer vistazo a Google Colab
1.	Como bienvenida tendremos una completa introduccion a este ambiente, donde se nos presentan ejemplos de códigos que podemos desarrollar.
![image](https://user-images.githubusercontent.com/73982270/224893231-fadefc24-e922-412d-9cd6-e13b6280c9c3.png)

2.	Posteriormente podremos ver nuestro ambiente de desarrollo para trabajar con códigos, podemos seleccionar entre varias opciones como GPU, CPU o incluso algunas clases de GPU si están disponibles, es de resaltar que muchas características avanzadas en este ambiente se encuentran disponibles si pagas por ello. Estas opciones las podemos encontrar en el GCP Marketplace.
![image](https://user-images.githubusercontent.com/73982270/224893269-6f6c0217-be4e-4d57-bb8e-fd45c0c6a1cd.png)

3. Una vez dentro de nuestro ambiente de trabajo, podemos proceder a confirgurar o instalar elementos a ocupar, por ejemplo algunas librerias, extensiones o bien hacer uso de un nuevo marco de trabajo.
![image](https://user-images.githubusercontent.com/73982270/224893631-c577ecc8-2399-4b32-9473-4ea02e208af5.png)
Al mismo tiempo, Google Colab nos brinda ciertas funciones como editor de texto, por ejemplo el caso de los errores, donde nos indicara la linea en la cual hemos tenido un error o el programa no puede continuar por cierto motivo.

4. En la siguiente imagen se observa un codigo en el ambiente de trabajo Google Colab, donde en este ejemplo se esta ejecutando el algoritmo YOLO v7 para deteccion de objetos. En este caso se importo este codigo desde el repositorio oficial de GitHub, generando una copia personal para trabajar de manera adecuada.
![image](https://user-images.githubusercontent.com/73982270/224893796-c2eb956c-00be-4915-a115-3cb42715fd7d.png)

5. Google Colab restringe muchas cosas como parte de su politica, dentro de las cuales se encuentran
File Hosting
Download Torrent
Remote Desktop or SSH
Remote proxy connection
Crypto Minin
Execution DoS
Corrupted passwords
Multiple accounts
Deepfakes
Finalmente, he aqui una imagen obtenida desde Google Colab sobre las tarias de paga para este servicio.
![image](https://user-images.githubusercontent.com/73982270/224894223-549884d8-11fa-4e4b-b64a-fb01e687523d.png)


### Instalar TensorFlow

1- Abre Google Drive y selecciona "Nuevo"

![Nuevo documento de Drive](https://user-images.githubusercontent.com/122324007/223322867-43f7d643-a62a-4b47-a38c-2e906c3bf264.png)


2- Selecciona las pestañas "más" y después "Google Colaboratory"

![Pestaña Google Colaboratory](https://user-images.githubusercontent.com/122324007/223323146-fb9f3bda-fea0-4dd3-b8e5-053e36b95502.png)


3- Introduce la siguiente línea de código en una nueva celda de código y da click al boton de ejecutar celda:

![!pip install tensorflow](https://user-images.githubusercontent.com/122324007/223323637-25aa5824-b79d-4a53-9afe-420ec2d4e754.png)


4- Deberán aparecer varias líneas de código que indican que todo está correcto con el mensaje "Requirement already satisfied"

![Requirement already installed](https://user-images.githubusercontent.com/122324007/223323987-58bdae8e-d99c-4819-9d66-3f1f767a269c.png)


5- Para comprobar que Tensorflow se instaló de forma correcta, podemos introducir las siguientes líneas en una nueva celda:

![revisar version de TF](https://user-images.githubusercontent.com/122324007/223325190-a1c78ae9-1834-49b7-8163-1f899da30c39.png)


Has instalado TensorFlow en tu bloc de notas de Colab


### Usar GPU para trabajar con TensorFlow
1- Seleccionar pestaña de "Entorno de ejecución" y seleccionar opcion "Cambiar tipo de Entorno de ejecución".

<img width="384" alt="Acelerador" src="https://user-images.githubusercontent.com/63762598/223907977-63f32783-4f0c-4889-9cc1-a75c1bd17633.png">


2- Seleccionar "Acelerador de Hardware" y seleccionar GPU.

<img width="453" alt="GPU" src="https://user-images.githubusercontent.com/63762598/223908053-f33cbd62-7e56-46ad-80bf-2b4229876b21.png">


### Tensorflow 2.0
La nueva versión de Tensorflow nos trajo nuevas opciones como:
- Cambio en API
- Reordenamientos de argumentos
- Cambio de nombre de símbolo

<img width="633" alt="Tensorflow2" src="https://user-images.githubusercontent.com/63762598/223909091-9ce43b6b-f509-449c-bfc7-ae79d0bdfbac.png">


### Como empezar un proyecto de machine learning usando Tensorflow
- Coleccion de datos: Los datos que va a utilizar para el entrenamiento y las pruebas de su modelo. Deben ser datos de alta calidad.
- Preprocesamiento de datos: Limpiar, dar forma y formatear nuestros datos.
- Creacion de modelo: Hyperparametros.
- Entrenamiento de modelo: Entrenamiento y prueba.
- Evaluación de modelo: Presición, Perdida.
