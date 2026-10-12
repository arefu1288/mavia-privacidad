# Política de privacidad de Mavia

**Vigente desde: 12 de octubre de 2026.**

## Responsable y contacto

El responsable de tus datos es **Andrés Refusta**, persona natural en Chile. Puedes escribir a **mavia.app@gmail.com** para consultas o solicitudes sobre tu privacidad.

Mavia es una app gratuita para iPhone que arma tu mapa de viajes usando la ubicación y la fecha de las fotos de tu galería. No tiene publicidad, no vende tus datos ni realiza rastreo entre apps. No utiliza App Tracking Transparency.

## Datos que quedan en tu teléfono

La ubicación exacta y la fecha de cada foto, tu zona de casa —ciudad, centro y radio de 5 km— y los viajes ocultos se procesan y guardan solo en tu teléfono. Permiten reconocer tus viajes y distinguirlos de los lugares cercanos a tu casa.

**Mavia no sube tus fotos.** El detalle de cada viaje las muestra desde tu galería. La ubicación exacta de cada foto y la ciudad y el centro de tu casa tampoco salen del teléfono a través de Mavia.

Este procesamiento se inicia cuando eliges **Importar mi galería** y autorizas el acceso a Fotos. Puedes retirar ese permiso en los ajustes de iOS. Retirarlo impide nuevos accesos a tu galería, pero no equivale a eliminar los datos ya guardados.

## Cuenta y viajes guardados

Al usar **Iniciar sesión con Apple**, guardamos en Supabase tu identificador de Apple, tu correo —que puede ser el correo privado de retransmisión de Apple— y tu nombre, si lo compartes.

Para guardar y recuperar tu mapa, conservamos en tu cuenta:

- Tu región de casa, por ejemplo, Región Metropolitana; nunca su ciudad ni su centro.
- De cada viaje marcado: nombre, fechas, origen —detectado o agregado a mano— y la nota que escribas.
- De cada parada: nombre del lugar, país, región, centro aproximado redondeado a dos decimales, cantidad de fotos y horas de inicio y fin.

El redondeo tiene una escala aproximada de 1,1 km; estos datos siguen asociados a tu cuenta. Los viajes que ocultas se borran de la nube y permanecen en tu teléfono.

El tratamiento de la cuenta, los viajes y las paradas tiene como fundamento la ejecución del servicio que solicitas: guardar y recuperar tu mapa.

## Métricas de uso

Usamos PostHog para mejorar Mavia y entender cómo se utiliza. El fundamento de este tratamiento es nuestro interés legítimo en mejorar la app.

PostHog recibe eventos de un catálogo cerrado, como abrir una pantalla o terminar la importación, con cantidades expresadas en rangos. También recibe el modelo genérico del dispositivo, la versión de iOS y de la app, el tamaño de pantalla y un identificador de sesión. Al iniciar sesión, los eventos se asocian al identificador de tu cuenta; no son datos anónimos.

Las métricas no incluyen coordenadas ni nombres de lugares. Se descarta la IP; no usamos geolocalización por IP, zona horaria ni idioma. No hay grabación de sesiones ni encuestas.

Las métricas vienen encendidas por defecto. Puedes apagarlas en **Ajustes → Compartir datos de uso** para detener su recopilación futura. Para solicitar la eliminación de datos anteriores, puedes escribirnos o eliminar tu cuenta.

## Proveedores y transferencias

Para prestar el servicio utilizamos:

- **Supabase, en São Paulo, Brasil:** recibe y guarda los datos de cuenta, región de casa, viajes marcados y paradas descritos en esta política.
- **PostHog, en su nube de la Unión Europea:** recibe y procesa los eventos y datos técnicos descritos en la sección de métricas.
- **Apple:** interviene en la solicitud de inicio de sesión para autenticarte con tu Apple ID y entrega a Mavia el identificador, el correo y, si lo compartes, tu nombre. También procesa la revocación del acceso de Mavia a tu Apple ID al eliminar tu cuenta.

El uso de Supabase y PostHog implica transferir esos datos fuera de Chile. Mavia no envía tus fotos a estos proveedores.

## Permisos e imágenes compartidas

Mavia solicita acceso a Fotos para leer la ubicación y fecha de las fotos y mostrarlas en tus viajes. También solicita permiso para guardar las imágenes que generas. Puedes administrar estos permisos en los ajustes de iOS.

La imagen para compartir se arma en tu teléfono, sin metadatos ni ubicación exacta. Tú eliges su destino mediante la hoja de compartir de iOS. **Mavia no recibe esa imagen.** Su contenido visible llega a las personas o servicios que elijas.

## Conservación y eliminación

Conservamos los datos mientras exista tu cuenta. Puedes eliminarla desde **Ajustes → Eliminar mi cuenta y mis datos**.

Al eliminarla:

- La cuenta, los viajes y las paradas se borran de Supabase de inmediato.
- Se elimina tu registro de persona en PostHog y sus eventos se borran en segundo plano durante los días siguientes.
- Se revoca el acceso de Mavia a tu Apple ID.
- Se borran los datos de Mavia en tu teléfono.

Los respaldos de los proveedores pueden conservar copias por un tiempo limitado, según sus propias políticas.

**Las fotos originales de tu galería no se tocan.** El borrado tampoco retira imágenes que ya hayas compartido con terceros.

## Seguridad

Las conexiones están cifradas. El acceso a los datos guardados está protegido por usuario: cada cuenta solo puede acceder a sus propios datos. La sesión se guarda en el llavero del iPhone.

## Tus derechos

Puedes solicitar acceso a tus datos, su rectificación, supresión, oposición al tratamiento, portabilidad y bloqueo, en los casos y condiciones que establece la legislación aplicable.

- **Acceso:** conocer tus datos y cómo se tratan.
- **Rectificación:** corregir datos inexactos o incompletos.
- **Supresión:** solicitar su eliminación.
- **Oposición:** objetar un tratamiento determinado.
- **Portabilidad:** recibir los datos comprendidos por este derecho en un formato reutilizable.
- **Bloqueo:** suspender temporalmente el tratamiento en los casos legales, sin eliminar su almacenamiento.

En **Ajustes → Exportar todo** puedes obtener un archivo JSON con tus viajes y paradas, sin datos de casa ni fotos. Esta exportación no sustituye una solicitud sobre otros datos personales. También puedes usar **Eliminar mi cuenta y mis datos** para borrar tu cuenta.

Para ejercer tus derechos por correo, escribe a **mavia.app@gmail.com**, indica tu solicitud y los datos que permitan localizar tu cuenta. Si pides una rectificación, señala qué debe corregirse. Responderemos dentro de los plazos que fija la ley.

## Mayores de 18 años

La edad mínima para usar Mavia es **18 años**. La app no está dirigida a menores de esa edad. Si sabemos que una cuenta pertenece a una persona menor de 18 años, la eliminamos.

## Cambios a esta política

Publicaremos los cambios en https://arefu1288.github.io/mavia-privacidad/ con su nueva fecha de vigencia. Los cambios importantes se avisarán dentro de la app.
