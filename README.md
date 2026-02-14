# Tester_uirlib
El código se encarga de realizar una solicitud get a dos direcciones URLs:
https://httpbin.org/get y https://self-signed.badssl.com/.

En la primera tratará de realizar la solicitud en un sitio con autofirmado y fallará porque el servidor no la reconoce
como un certificado de confianza.

En la segunda URL no mandó error porque le estamos indicando que el cliente acepte aunque no tenga un certificado válido.
