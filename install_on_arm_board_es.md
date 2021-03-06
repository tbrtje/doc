# Instalar YunoHost en una tarjeta ARM

*Encontrar otros medios de instalar YunoHost **[aquí](/install)**.*

<center>
<img src="/images/olinuxino.jpg" width=250 style="padding-bottom:20px">
<img src="/images/micro-sd-card.jpg">
</center>

<div class="alert alert-info" markdown="1">
Antes de alojar tu propio servidor en tu casa, te recomendamos que consultes las [posibles restricciones impuestas por tu Proveedor de Internet](/isp). Si tu proveedor es demasiado restrictivo, puedes utilizar un VPN para eludir estas restricciones.
</div>

- Una tarjeta ARM con un procesador de 500 MHz et 512 Mo de memoria RAM ; 
- Un adaptador de corriente para alimentar la tarjeta ;
- Una tarjeta microSD : al menos **8 Go** y **Clase 10** (por ejemplo una [Transcend 300x](http://www.amazon.fr/Transcend-microSDHC-adaptateur-TS32GUSDU1E-Emballage/dp/B00CES44EO)) ;
- Un cable ethernet/RJ-45 para conectar la carte con el router / caja internet. (Con el Raspberry Pi 0, puedes conectar tu tarjeta con un cable OTG y un adaptador Wifi USB.)
- Un [proveedor de Internet ético](/isp), de preferencia con una buena velocidad de upload.

---

## Instalación con la imagen pre-instalada (recomendada)

<a class="btn btn-lg btn-default" href="/images">0. Descargar la imagen pre-instalada para tu tarjeta ARM</a>
<br>
<small class="text-info">Si no existe una imagen dedicada a tu tarjeta, puedes seguir la sección "Instalación encima de ARMbian".</small>

<a class="btn btn-lg btn-default" href="/burn_or_copy_iso">1. Poner la imagen en tu tarjeta SD</a>

<a class="btn btn-lg btn-default" href="/plug_and_boot">2. Conectar y encender</a>

<a class="btn btn-lg btn-default" href="/ssh">3. Conectarse en SSH</a>

<a class="btn btn-lg btn-default" href="/postinstall">4. Proceder a la post-instalación</a>

---

## Instalación encima de ARMbian

<a class="btn btn-lg btn-default" href="https://www.armbian.com/download/">0. Descargar la imagen ARMbian para tu tarjeta ARM</a>

<a class="btn btn-lg btn-default" href="/burn_or_copy_iso">1. Poner la imagen en tu tarjeta SD</a>

<a class="btn btn-lg btn-default" href="/plug_and_boot">2. Conectar y encender</a>

<a class="btn btn-lg btn-default" href="/ssh">3. Conectarse en SSH</a>

<a class="btn btn-lg btn-default" href="/install_manually">4. Proceder a la post-instalación genérica</a>

