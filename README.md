# keystroke-dynamics 
## Identificación de usuarios en base a sus patrones de tecleo
Los métodos existentes en la actualidad para la identificación y verificación de usuarios pueden dividirse en tres grupos: métodos basados en la posesión de un dispositivo fisico como los tokens, aquellos basados en el conocimiento (como las contraseñas) y métodos basados
en datos biométricos. Éstos últimos utilizan rasgos biológicos que son más difíciles de copiar
u obtener para usuarios ilegítimos que los tokens o contraseñas ya que se tratan o de rasgos físicos
como las huellas dactilares o el iris o de rasgos relacionados con patrones de comportamiento,
entre los que se puede destacar la identificación mediante patrones de tecleo o "keystroke dynamics" en inglés. Este método se basa en la existencia de ciertos patrones
en la forma en que tecleamos que se suponen lo suficientemente únicos y distintivos como para
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


Para realizar este análisis he utilizado el data set GREYC (1https://www.labri.fr/perso/rgiot/pub/keystroke.db).
Este dataset consta de consta de datos de 133 usuarios que teclearon la contraseña 'greyc laboratory'
en dos teclados distintos. Para la predicción de los patrones e identificación de los usuarios he analizado el rendimiento de varios métodos: k-nearest-neighbours, random forest y red neuronal.
