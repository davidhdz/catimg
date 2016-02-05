catimg
======
---
Utilidad que permite pegar una serie de imágenes en formato vertical u horizontal.
`catimg` utiliza `imagemagick` para procesar las imágenes y agregar bordes automáticamente, pudiendo escoger el tamaño del mismo y color.

    Usage: catimg [options] infiles outfile

    Options:
      --version             show program's version number and exit
      -h, --help            show this help message and exit
      -v, --vertical        vertical arrangement (default)
      -z, --horizontal      horizontal arrangement
      -g number, --gap=number
                            size gap between images, default 0
      -b color, --bgcolor=color
                            background color, default white

---

Ejemplo
-------

![Before](images/407-password_web.png "Before")

<br/>
`catimg -v -g 5 -b grey 407-password-3-0* 407-password.png`

<br/>
![After](images/407-password_grey.png "After")

<br/>

Fuente de las imágenes: http://www.pidjin.net/2016/02/02/strong/
