# ![Greenter](https://cdn.giansalex.dev/images/github/greenter-ico.png) Greenter
![CI](https://github.com/thegreenter/greenter/workflows/CI/badge.svg)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/ab05a05260fe452c9bfae8bf20e94d5d)](https://www.codacy.com/gh/thegreenter/greenter?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=thegreenter/greenter&amp;utm_campaign=Badge_Grade)
[![Project Stats](https://www.openhub.net/p/greenter/widgets/project_thin_badge.gif)](https://www.openhub.net/p/greenter)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fthegreenter%2Fgreenter.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fthegreenter%2Fgreenter?ref=badge_shield)
    
Esta librería le permite implementar la **Facturación Electrónica** en Perú, desde los sistemas desarrollados por el 
contribuyente, el cual esta normado por SUNAT.   
Greenter realiza la mayoría de tareas del proceso, genera el XML según el estándar UBL, firma con el certificado digital,
comprime el archivo XML en formato zip, realiza el envío al webservice de SUNAT y procesa el CDR (Comprobante de Recepción), además incluye otras 
herramientas de utilidad.

Puede ver una demostración en [@greenter/demo](https://github.com/thegreenter/demo).

[![Quality gate](https://sonarcloud.io/api/project_badges/quality_gate?project=thegreenter_greenter)](https://sonarcloud.io/dashboard?id=thegreenter_greenter)

## Requerimientos
- PHP `7.2` o superior
- Extensiones PHP Activadas: `soap`, `dom`, `zip`, `zlib`, `openssl`.

## Documentación
- Lee esta [guia](https://fe-primer.greenter.dev/) para conocer mas sobre facturación electrónica.
- Empieza con este [ejemplo basico con greenter](https://greenter.dev/starter/).
- Tienes dudas o necesitas ayuda puedes hacerlo desde [aqui](https://community.greenter.dev/).
- Puedes seguirnos en [Facebook](https://fb.me/thegreenter) para actualizaciones.

## API REST
API REST con [Lycet](https://github.com/giansalex/lycet) empleando Symfony Framework.

## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fthegreenter%2Fgreenter.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fthegreenter%2Fgreenter?ref=badge_large)