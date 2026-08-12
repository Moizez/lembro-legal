---
title: Política de Privacidad de Lembrô
lang: es
doc: privacy
home: /es/
tagline: Política de privacidad y términos de uso de Lembrô
---

# Política de Privacidad de Lembrô

**Aplicación:** Lembrô (`com.damcode.lembro`)
**Última actualización:** 11 de agosto de 2026

> **Esta es una traducción, por conveniencia.** Lembrô se desarrolla en Brasil y esta política
> se rige por la legislación brasileña. Si las dos versiones llegaran a divergir, prevalece la
> [versión en portugués](../privacidade.html).

---

## En una frase

**Lo que usted registra se queda en su celular, y solo sale de allí si usted lo autoriza.** No
hay registro, no hay cuenta, no hay ningún servidor nuestro con sus datos. Las tres situaciones
en las que algo sale del aparato — guardar una copia, enviar un resumen y el acompañamiento por
un responsable — las inicia y las autoriza **usted**, y están descritas una por una más abajo.

El resto de este documento lo detalla, porque la ley pide detalle — pero la frase de arriba es
la regla entera.

## Quién es el responsable

Esta aplicación la desarrolla y la mantiene **Carlos Moisés Batista Henrique**, bajo el nombre
**DamCode**, desarrollador persona física, en Brasil.

**Canal para cualquier cuestión de privacidad, incluidos los pedidos previstos en la LGPD** (la
ley brasileña de protección de datos): `moizezhenrique@gmail.com`

Respondemos en hasta 15 días, el plazo del artículo 19 de la LGPD.

**Sobre el encargado (DPO):** por ser un agente de tratamiento de pequeño porte, y en los
términos de la Resolución CD/ANPD n.º 2/2022, no hay designación formal de encargado — pero el
canal de arriba existe, se atiende, y es por él que debe llegar cualquier pedido, duda o
reclamo.

## Qué datos guarda la aplicación, y dónde

Todo lo de abajo queda **exclusivamente en el almacenamiento interno de su celular**, en una
base de datos a la que solo accede Lembrô:

| Qué | Para qué |
|---|---|
| Nombre y detalle de sus recordatorios | Mostrarlos en la pantalla y en el aviso |
| Horarios, días y repetición | Saber cuándo avisar |
| Registros ("lo tomé a las 08:12") | Armar el historial y el acompañamiento |
| Identificador de sus etiquetas NFC y el nombre que usted les dio | Reconocer la etiqueta cuando usted acerca el celular |
| Sus preferencias (sonido, vibración, avisos ya vistos) | Recordar lo que usted eligió |

**No pedimos y no guardamos:** su nombre, correo, teléfono, documento, dirección, fecha de
nacimiento, contactos, fotos, ubicación, ni ningún identificador de publicidad.

**No guardamos valores de salud.** Lembrô registra que la tarea **ocurrió**, nunca el resultado
de ella: no hay campo para presión, glucemia, peso ni ninguna medición. Es una decisión de
producto, no una limitación temporal.

## Datos sensibles de salud

La información de que usted usa un determinado medicamento, y en qué horarios, es **dato
personal sensible** por el artículo 5.º, II de la LGPD. Por eso la aplicación se construyó para
que ese dato **no circule**:

- No se transmite ni a nosotros ni a terceros.
- No se usa para publicidad, perfilamiento ni ninguna finalidad comercial. La LGPD prohíbe
  expresamente el uso económico de dato sensible de salud (art. 11, §4.º), y a nosotros tampoco
  nos interesa: no es así como se sostiene esta aplicación.
- No se comparte con farmacias, obras sociales, laboratorios ni anunciantes.

**Nosotros no accedemos a esos datos.** Vale ser preciso aquí, porque es fácil escribir bonito e
impreciso: el artículo 5.º, X de la LGPD define "tratamiento" de forma amplia, y la lista
incluye *almacenamiento*. Almacenamiento hay — **en su aparato**. Lo que no hay es acceso
nuestro: no recibimos copia, no tenemos cómo consultar, exportar ni borrar el contenido de sus
recordatorios. Quién decide qué registrar y qué borrar es usted, en el aparato.

No es un detalle de redacción: es lo que hace que las tres situaciones de abajo — las únicas en
que algo sale del aparato — las **dispare usted**, y no nosotros.

## Las tres veces en que algo sale del aparato — y usted decide las tres

### 1. Guardar una copia de seguridad

En Ajustes, "Guardar una copia" genera un archivo con sus recordatorios y su historial y abre la
hoja de compartir del propio sistema, para que **usted** elija el destino (Google Drive, correo,
WhatsApp, otra aplicación).

- Nosotros no recibimos ese archivo y no sabemos adónde fue.
- Desde el momento en que usted lo envía, pasa a regirse por la política del servicio que
  eligió.
- El archivo **no está cifrado**, para que usted mismo pueda abrirlo y para que siga siendo
  restaurable en el futuro. Guárdelo en un lugar de su confianza.

### 2. Enviar un resumen

En la pantalla Acompañamiento, "Enviar resumen" arma un **texto** con lo que pasó y abre la
misma hoja del sistema. Usted elige si lo manda, y a quién. Nosotros no vemos el contenido ni el
destinatario.

### 3. El acompañamiento por un responsable — opcional, y el único que usa la nube

Un hijo, familiar o cuidador puede, **con su autorización explícita**, acompañar de lejos si sus
horarios fueron registrados. Es la única función de la aplicación que envía algo por internet, y
**nace apagada**: solo pasa a existir después de que usted toca "Autorizar" en su pantalla,
viendo el nombre de quien lo pidió.

**Lo que viaja — y nada más que esto:**

| Dato | Ejemplo |
|---|---|
| Nombre del recordatorio | "Losartán" |
| Horario previsto | 08:00 |
| Horario registrado, o la ausencia de él | registrado a las 08:12 / no registrado |
| Cómo se registró | por la etiqueta o por el botón |
| El día al que eso se refiere | 2026-08-01 |

**Lo que nunca viaja:** el campo de detalle y anotaciones (donde se escribe la dosis), los
nombres de sus etiquetas, sus ajustes, su ubicación — que la aplicación ni siquiera recopila — y
el historial anterior a la autorización.

**Dónde queda:** en una base de datos de **Google Firebase (Firestore)**, contratada por
nosotros como operador, en un servidor ubicado en **São Paulo, Brasil** (región
`southamerica-east1`). La identidad de los aparatos es **anónima**: un código aleatorio creado
por Firebase, sin nombre, correo ni teléfono — sigue sin existir registro. El tratamiento que
hace Google como operador se rige por su propia política:
https://firebase.google.com/support/privacy

**Quién lee:** solamente los aparatos que **usted** autorizó, uno por uno, con el código de
vinculación. La autorización la verifica el servidor en cada lectura — no es promesa de la
aplicación, es regla de la base de datos. Quien acompaña **ve y no toca**: no puede registrar
por usted, no puede editar nada.

**Usted se entera:** mientras alguien acompaña, la pantalla inicial muestra un sello permanente
con el nombre de la persona. No existe modo invisible.

**También viaja una señal de que la aplicación se abrió.** Junto a cada día enviado viaja la
hora del envío, y el envío ocurre cuando usted abre Lembrô — no solo cuando registra algo. Esto
existe por un motivo específico: sin ello, un día sin ningún registro quedaba idéntico a un día
en que el celular pasó en un cajón, y quien acompaña no tenía cómo saber si fue olvido o si el
aparato quedó apagado. Con la señal, su panel puede decir "Lembrô no se abrió este día" en lugar
de sugerir que no se tomó nada.

Lo que eso significa en términos de dato: quien acompaña pasa a poder estimar **cuándo usó usted
la aplicación por última vez**. No es ubicación, no es uso del celular en general, no es
ninguna pantalla más allá de Lembrô — es la hora del último envío, y nada más. Si prefiere no
enviar eso, el camino es el mismo de todo lo de aquí: quitar el acompañamiento.

**Quien acompaña puede reenviar lo que ve.** Su aplicación tiene un botón para mandar el día en
texto — a un hermano, a un médico. El texto sale identificado como enviado por quien acompaña, y
lleva el mismo contenido del panel: nombres, horarios y si fue registrado. **No lleva la dosis
ni sus anotaciones**, que nunca salen de su aparato. Aun así vale que usted lo sepa: autorizar a
alguien a ver es autorizar a alguien que puede contárselo a terceros, como pasaría si esa
persona sacara una foto de la pantalla.

**Para apagarlo:** Ajustes → Quién me acompaña → Quitar. **Un toque**, sin confirmación en
cascada. El acceso se corta en el momento, el envío para. Y la aplicación **borra de la nube
todo lo que ya había enviado** — retirar el consentimiento no deja rastro hacia atrás.

**Retención:** cada día enviado se **borra después de 90 días**. Quien borra es la propia
aplicación, la primera vez que abre con internet después del vencimiento — no hay ningún
servidor nuestro corriendo solo. Consecuencia honesta: si la aplicación se desinstala sin que
usted use Quitar, lo que ya subió puede permanecer allí; en ese caso, escriba al contacto de
arriba y lo borramos. Su historial completo sigue viviendo solo en su aparato.

**Base legal:** su **consentimiento** (LGPD, art. 11, I — dato sensible), recogido de forma
específica y destacada en la pantalla de autorización. Revocarlo es el botón Quitar.

## Avisos (notificaciones)

Los avisos se generan **dentro de su celular**, por la propia aplicación, y se programan en el
sistema operativo. No hay servidor de notificación, no hay *push* y ninguna información sobre
sus recordatorios viaja por internet para que el aviso llegue.

La aplicación pide permiso de notificación la primera vez que abre. Si usted lo rechaza, Lembrô
sigue funcionando — solo que no avisa.

## Etiquetas NFC

La etiqueta NFC guarda **apenas una dirección con un identificador aleatorio** creado por la
aplicación (por ejemplo, `lembro://t/tag_a1b2c3`). **No contiene** el nombre del medicamento, ni
ningún dato suyo.

Es deliberado: una etiqueta NFC puede ser leída por cualquier celular. Como el identificador
solo tiene sentido dentro de su aplicación, quien acerque otro aparato a su etiqueta no descubre
nada sobre usted.

El permiso de NFC en Android se concede en la instalación y sirve solo para leer y grabar sus
etiquetas. No usamos NFC para pagos ni para identificarlo a usted.

## Permisos y para qué sirven

| Permiso | Para qué |
|---|---|
| NFC | Leer y grabar sus etiquetas |
| Notificaciones | Avisar a la hora del recordatorio |
| Alarma durante el ahorro de energía | Hacer que el aviso llegue aun con el celular quieto |
| Cobro en la aplicación (*billing*) | Comprar Lembrô completo por la tienda |

No pedimos ubicación, cámara, micrófono, contactos, almacenamiento externo ni teléfono.

## Compras

Lembrô es gratis y funcional. Hay una versión completa paga, opcional, y una suscripción
separada para quien acompaña a otra persona.

**Quien procesa el pago es la tienda de aplicaciones** (Google Play o App Store), que es la
vendedora legal. Lembrô **no ve, no recibe y no almacena** datos de pago: ni tarjeta, ni
documento, ni dirección de facturación. La aplicación solo le pregunta a la tienda si existe una
compra válida asociada a su cuenta, y recibe "sí" o "no".

El tratamiento de sus datos de pago se rige por la política de privacidad de la tienda:

- Google Play: https://policies.google.com/privacy
- App Store: https://www.apple.com/legal/privacy/

## Análisis de uso, rastreo y publicidad

**No existen en Lembrô.** No usamos herramientas de analítica, informes de fallas, rastreadores,
identificadores de publicidad, *píxeles* ni SDK de terceros con esa finalidad. No sabemos
cuántas veces usted abrió la aplicación, ni qué recordatorios tiene.

**Una salvedad honesta sobre el cobro.** Para vender la versión completa, la aplicación incluye
la biblioteca de cobro de la propia Google Play. Es de Google, y hace diagnóstico propio con sus
servidores sobre el funcionamiento de la compra — algo que ocurre en toda aplicación que vende
por la tienda, y que no pasa por nosotros: no lo recibimos, no lo vemos y no podemos acceder a
esa información. Nada de sus recordatorios o registros se envía por ese camino. Lo que Google
hace con esos datos se rige por su política de privacidad, enlazada arriba.

**Y sobre Firebase.** La biblioteca de Firebase, usada por el acompañamiento, está presente en
la aplicación — pero solo habla con internet cuando existe una vinculación suya. No incluimos
Firebase Analytics ni Crashlytics: de Firebase usamos exactamente dos servicios, la base del
espejo (Firestore) y la identidad anónima (Authentication), descritos en la sección del
acompañamiento.

Como consecuencia, tampoco **podemos** recuperar sus datos si usted pierde el celular sin haber
guardado una copia — y por eso existe la copia de seguridad.

## Niños y adolescentes

Lembrô no está dirigido a menores de 13 años y no recopila datos de nadie, de ninguna edad. Si
un responsable usa la aplicación para organizar la rutina de un niño, los datos siguen en el
aparato del responsable, bajo su control.

## Sus derechos (LGPD, artículo 18)

Como todos los datos están en su aparato y bajo su control, usted ejerce sus derechos
directamente, sin depender de nosotros y sin plazo de espera:

| Derecho | Cómo ejercerlo |
|---|---|
| **Acceder** a los datos | Están visibles en la aplicación; "Guardar una copia" exporta todo en un archivo legible |
| **Corregir** | Editar el recordatorio, o corregir/borrar un registro en el historial |
| **Portabilidad** | El archivo de la copia de seguridad es JSON abierto, no un formato cerrado |
| **Eliminar** | Borrar el recordatorio, o desinstalar la aplicación — desinstalar quita la base de datos entera |
| **Eliminar el espejo del acompañamiento** | Ajustes → Quién me acompaña → **Quitar**: corta el acceso y borra de la nube todo lo que ya se envió, en el mismo toque |
| **Revocar el consentimiento** | Del acompañamiento: el botón Quitar. Del resto: desinstalar — no hay nada más nuestro que revocar |

Si aun así quiere hablar con nosotros sobre privacidad, use el contacto de arriba.

## Retención y eliminación

Los datos quedan en su aparato el tiempo que usted quiera. **Desinstalar la aplicación borra la
base de datos.** No hay copia nuestra, por lo tanto no hay nada que sobreviva a la
desinstalación — excepto los archivos de copia de seguridad que usted mismo haya guardado en
otro lugar y, si usa el acompañamiento, los días ya enviados al espejo. **Si usa el
acompañamiento y va a desinstalar, use antes Quitar**: es lo que borra el espejo en la nube.
Desinstalar sin eso deja allí lo que ya subió, y la eliminación pasa a depender de un pedido por
el contacto de arriba.

## Seguridad

Los datos residen en el área privada de la aplicación, protegida por el sistema operativo: otras
aplicaciones no logran leerla. Fuera del espejo del acompañamiento — que solo existe con su
autorización, viaja cifrado (TLS) y lleva el mínimo descrito arriba —, no hay transmisión por la
red, lo que elimina la clase entera de riesgos de interceptación y de filtración en servidor
para todo el resto.

Recomendamos mantener activa la pantalla de bloqueo del celular, con contraseña o biometría — es
ella la que protege cualquier aplicación, incluida esta, si el aparato se pierde.

## Incidentes

La única base de datos fuera del aparato es el espejo del acompañamiento, descrito arriba — con
el mínimo de dato posible, identidad anónima y lectura restringida por regla de servidor. Si se
identificara alguna vulnerabilidad en la aplicación o en esas reglas, la corregiremos y
publicaremos una actualización; si hubiera riesgo relevante a los titulares, lo comunicaremos
por los canales de la tienda y por esta página, conforme el artículo 48 de la LGPD.

## Cambios en esta política

La versión anterior de esta política prometía: si alguna función pasara a enviar datos fuera del
aparato, esta página sería actualizada **antes** del lanzamiento y la aplicación pediría
**consentimiento específico y destacado** en la pantalla. El acompañamiento por un responsable
es exactamente ese caso, y así fue como llegó: descrito aquí antes de existir en la tienda,
apagado por defecto, y encendido solamente por su toque en "Autorizar".

La promesa sigue valiendo para lo que venga: un cambio que amplíe lo que sale del aparato se
publicará aquí antes, con la fecha de arriba cambiada, y nunca se encenderá en silencio ni por
defecto.

## Ley aplicable

Esta política se rige por la legislación brasileña, en especial la Ley n.º 13.709/2018 (LGPD) y
la Ley n.º 8.078/1990 (Código de Defensa del Consumidor).
