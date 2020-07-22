###### #hyperblog
# Un blog increíble para el curso Git y GitHub de Platzi

------------

> Master de **freddier**. **Anita** hizo un *pull request* que fusionó unos cambios con algo de **freddier**. Anita también hizo un *fork* como colaboradora. **Anita** hizo unos cambios y los envió con un *pull request*. Ese* pull request* fue aprobado y se fusionó en el *commit*. 

Pero mientras pasaba el tiempo, **freddier** hizo cambios completamente distinto en *master*. ¿CÓMO TRAER ESTOS CAMBIOS AL REPOSITORIO DE **ANITA**? Para traerlo hay que entender que anita en realidad  son dos repositorios: un repositorio en github (online en internet) y un repositorio distinto en local.

### # Tenemos dos opciones: 

1. Crear un *upstream* (fuente de origen) en el repositorio local. Normalmente un repositorio local envía cambios locales al github de **anita**. Pero un *upstream* es un repositorio adicional que apunta al repositorio *master*. Cuando desde local pedidos al *upstream* la última versión, lo que hace es traer el último *commit* y fusionarlo con la versión local. Y luego para subirlo a github hacemos un *push origin* *master* (que sería el *push* tradicional hacia **anita**). 

3. La otra forma es hacerlo desde github (online, sin usar la consola).

2020-07-22 15:36:30 Wednesday