El proyecto DATA GROUP utiliza un mecanimo conocido como Certificado de origen del Desarrollador - DCO (por sus siglas en inglés) para administrar este proceso. El DCO es una declaración jurídicamente vinculante que afirma que usted es el creador de su contribución y que desea permitir que DATA GROUP utilice su trabajo.

El acuso de recibo de este permiso se realiza mediante un proceso de inicio de sesión en Git. El sign-off es una línea simple al final de la explicación para el parche. El texto del DCO es bastante simple (de developercertificate.org):

---

Certificado de origen del desarrollador
Versión 1.1

Copyright (C) 2004, 2006 La Fundación Linux y sus colaboradores.
660 York Street, Suite 102,
San Francisco, CA 94110 USA

Todo el mundo está autorizado a copiar y distribuir copias
documento de licencia, pero no se permite cambiarlo.

Certificado de origen del desarrollador 1.1

Al hacer una contribución a este proyecto, certifico que:

(a) La contribución fue creada total o parcialmente por mí y yo
tienen derecho a presentarlo bajo la licencia de código abierto
indicada en el expediente; o

(b) La contribución se basa en trabajos anteriores que, a la mejor
de mi conocimiento, está cubierto bajo una fuente abierta apropiada
licencia y tengo el derecho bajo esa licencia de presentar
trabajo con modificaciones, ya sean creadas en su totalidad o en parte
por mí, bajo la misma licencia de código abierto (a menos que sea
autorizada a presentar una licencia diferente), según se indica
en el archivo; o

(c) La contribución me fue proporcionada directamente por algún otro
persona que certificó (a), (b) o (c) y no he modificado
eso.

(d) Entiendo y estoy de acuerdo en que este proyecto y la contribución
pública y que el registro de la contribución (incluida toda la
información personal que envío con ella, e incluyendo mi firma) se
mantiene indefinidamente y puede ser redistribuida
con este proyecto o las licencias de código abierto involucradas.

Si está dispuesto a aceptar estos términos, simplemente añada una línea a cada mensaje de envío de git:

Firmado por: tu nombre y apellido <tumail@email.com>

Si configura su user.name y user.email como parte de su configuración de git, puede firmar su commit automáticamente con git commit -s.

Por desgracia, usted tiene que usar su nombre real (es decir, pseudónimos o contribuciones anónimas no se pueden hacer). Esto se debe a que el DCO es un documento jurídicamente vinculante, otorgando al proyecto DATA GROUP el uso de su trabajo.
