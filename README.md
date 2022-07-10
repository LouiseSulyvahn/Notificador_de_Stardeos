
# Notificador de Stardeos

Un Bot de Discord que notifica le a tu comunidad cuando subes un video a [Stardeos](https://stardeos.com/).

# Solicitar invitación

El bot solo puede unirse a 100 servidores hasta que sea verificado por Discord, por lo que **solo se agregara en los servidores de los creadores de contenido.**

Agrega a **Lenore#8596** (UID:357738028304957440) para solicitar la invitación del bot.

# Guía de configuración

Una vez que el bot este en tu servidor solo queda configurarlo.

Escribe **/setup** y completa los datos solicitados.

* **stardeos_username** - (Tu nombre de usuario de Stardeos (case-sensitive).
* **discord_channel** - Selecciona el canal donde quieres que las notificaciones sean enviadas.
* **use_everyone** - ¿Quieres que las notificaciones incluyan @everyone?.

![](https://i.imgur.com/So9hFmr.png)

# Limitaciones

Debido al uso de Cloudflare y la falta de una API oficial, algunas funciones del Bot están limitadas.

* Se buscan videos cada 5 minutos y se puede extender si el bot es constantemente bloqueado por Cloudflare.
* No se puede agregar la miniatura de los videos a las notificaciones, ya que Cloudflare impide que se muestren correctamente.

# ToDo

* Optimizar código.
* Resubir la miniatura de los videos para que se muestren correctamente.
* Agregar Cloudflare Bypass.

# Notas 

Este bot es una solución temporal a la falta nativa de webhooks que notifiquen de nuevos videos y solo es desarrollado en mi tiempo libre para aprender.
