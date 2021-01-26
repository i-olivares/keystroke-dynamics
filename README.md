# keystroke-dynamics - Identificación de usuarios en base a sus patrones de tecleo
Desde la llegada de los ordenadores personales a inicios de los 80 y, mas tarde, con la llegada
de los dispositivos móviles, se ha producido una explosión en el número de tareas que llevamos a
cabo digitalmente, desde algo tan sencillo como mirar un correo electrónico hasta operaciones que
implican información tan sensible como las transacciones bancarias. En este contexto, se vuelven
cada vez más importantes los mecanismos de identificación y verificación de usuarios. Los métodos
existentes actualmente pueden dividirse en tres grupos, que además pueden utilizarse de forma
individual o complementaria: métodos basados en la posesión de un dispositivo fisico como los
tokens, aquellos basados en el conocimiento (como las contraseñas) y, por último, métodos basados
en datos biométricos. Étos utilizan rasgos biológicos que, en principio, son más difíciles de copiar
u obtener para usuarios ilegítimos que los tokens o contrase~nas ya que se tratan o de rasgos físicos
como las huellas dactilares o el iris o de rasgos relacionados con patrones de comportamiento,
entre los que podemos destacar la identificación mediante patrones de tecleo o "keystroke dyna-
mics" en inglés. Como su nombre indica, este método se basa en la existencia de ciertos patrones
en la forma en que tecleamos, que se suponen lo suficientemente únicos y distintivos como para
identificarnos de forma unívoca. Para comprobar la identidad de una persona que intente acceder
al sistema, se comparan los datos almacenados en el momento del registro con aquellos que proporciona
el usuario que está intentando acceder. En este sentido, la verificación o identificación del usuario 
puede ser estática, si se realiza sólo en el momento de el acceso al sistema, o dinámica,
si se verifica de forma continuada la identidad del usuario que ha accedido al sistema durante
toda la sesión. Por tanto, este método no sólo provee de una forma segura de identificación sino
que, además, los únicos productos necesarios son un teclado y un software para llevar a cabo la
autenticación, convirtiéndose así en un método mínimamente invasivo y de fácil adhesión para el
usuario, asi como de bajo coste en comparación con los métodos biométricos físicos que necesitan
de hardware adicional.

![image](https://user-images.githubusercontent.com/57218498/105896415-0d626a80-6017-11eb-96b0-44a10bd1d6bb.png)


En este caso se va a utilizar el data set GREYC (1https://www.labri.fr/perso/rgiot/pub/keystroke.db)
Este dataset consta de consta de datos de 133 usuarios que teclearon la contraseña 'greyc laboratory'
en dos teclados distintos durante, al menos, cinco sesiones espaciadas alrededor de una
semana entre ellas. Se evalúan varios métodos (k-nearest-neighbours, random forest y red neuronal)
para la predicción e identificación de los patrones de tecleo de los usuarios.
