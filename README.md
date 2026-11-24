# Local Guardian

Control parental **local** para Android. La app se convierte en *Device Owner* del teléfono y oculta o recupera
aplicaciones y activa restricciones con las funciones oficiales de Android para empresas
(`DevicePolicyManager`). No necesita root, cuentas, servidores ni Internet: cada teléfono guarda su propia
configuración y se cambia con una contraseña maestra.

Este repositorio **solo contiene el APK firmado** para poder descargarlo al configurar un teléfono.

## Descarga

APK actual: [`LocalGuardian.apk`](https://raw.githubusercontent.com/TICALIJJ/Alimer-Local-Guardian/main/LocalGuardian.apk)

| Dato | Valor |
|---|---|
| Versión | 0.6.0-fase6 |
| Paquete | `es.alimer.localguardian` |
| Android | 8 (API 26) o superior |
| Probado en | Android 13 (un solo modelo) |
| SHA-256 del APK | `a4820e0c56d26682aea6214eb4e7fa2a29bfdb2ad9b01fab88d46f2642135511` |
| SHA-256 del certificado de firma | `12fa619cbedb975ed8d465f713e67b53806e0599cb823b510fdd882f9c81bd3b` |

El certificado de firma no cambia entre versiones: un APK firmado con otra clave **no** es un Local Guardian
legítimo.

## Uso

Para ser Device Owner, el teléfono tiene que estar **recién restablecido** de fábrica (sin cuentas añadidas) y se
configura con un código QR de aprovisionamiento que apunta a este APK. Una vez configurado, todos los cambios
piden la contraseña maestra del propio teléfono.

## Aviso

Software en desarrollo, sin garantía de ningún tipo. Úsalo bajo tu responsabilidad y prueba antes en un teléfono
que no sea el de uso diario: un teléfono con Device Owner solo se puede liberar desde la propia app o
restableciéndolo de fábrica.
