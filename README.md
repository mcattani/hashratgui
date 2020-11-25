# hashratgui
HashRat es una app utilizada para generar “hashes” utilizando diferentes algoritmos: md5, sha1, sha256, sha512, etc..

    Hashrat is a hash-generation utility that supports the md5, sha1, sha256, sha512, whirlpool, jh-224, jh256, jh-384 and jh-512 hash functions. Hashes can be output in octal, decimal, hexadecimal, uppercase hexadecimal or base64. 

Destaco algunas características que le encuentro de gran utilidad:

    Posee una gran cantidad de algoritmos para elegir como así también distintas codificaciones de los mismos.
    Puede aplicarse un algoritmo sobre un arhivo o carpeta para utilizar luego la salida para comprobar la integridad de los mismos.
    Puede utilizarse para generar passwords muy seguros. Ingresando nuestra palabra o frase clave y utilizando la salida como clave de ingreso.

Por ejemplo: utilizamos la salida de la siguiente cadena como password para Facebook:

    Cadena: password facebook
    Salida (MD5): pUE_0LOWXbh4UVnLf_stUV

Para utilizar esta interfaz gráfica es necesario tener instalado hashrat en nuestro SO. En Ubuntu y derivados se instala desde apt:

    sudo apt install hashrat

La interfaz gráfica solo provee de una fracción de lo que este programa es capaz, les recomiendo leer el manual de la aplicación para ver todo lo que puede hacer.

    man hashrat

Dentro de la carpeta DEB_file se encuentrán los archivos .deb para su instalación en distros basadas en Debian.

Si te parece útil / interesante esta app por favor visitá mi blog: https://thenerdyapprentice.blogspot.com/
