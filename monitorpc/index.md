---
title: Monitor PC + PC Gauge — Descarga / Download
---

# Monitor PC

[Español](#español) · [English](#english)

## Español

**Monitor PC** es un programa portable para Windows que muestra el uso de CPU, GPU, RAM, discos, red y temperaturas en una ventana flotante, y lo sirve a tu móvil a través de tu red local. Con la app de Android **PC Gauge** ves todo en vivo desde el móvil, además de la información del sistema.

### Descarga

[**Descargar MonitorPC_portable.exe**](MonitorPC_portable.exe)

No necesita instalación: descárgalo y ábrelo.

### Requisitos

- Windows 10 u 11.
- **Ejecutar como administrador** para leer todos los sensores (sin admin funciona igualmente, mostrando "N/D" donde falte un dato). Como administrador también crea solo las reglas del firewall (TCP 8765 y UDP 8766), que solo aceptan conexiones de tu red local y de Tailscale.
- Opcional: driver **PawnIO** (<https://pawnio.eu>) para temperaturas de CPU y ventiladores.
- PC y móvil en la misma red (o en la misma red Tailscale, ver abajo).

### Emparejar con la app de Android

1. Abre Monitor PC en el PC.
2. En la bandeja del sistema elige **"Emparejar móvil (QR)…"** (o Ajustes → Panel móvil). Aparece un código QR.
3. En la app de Android pulsa **Escanear código QR** y apunta a la pantalla.
4. Listo: el PC aparece en "Mis PCs". Tócalo para ver sus datos en vivo.

**Recomendado:** en Ajustes → Panel móvil marca **"Pedir código de acceso"**. El QR ya lleva el código, así que emparejar sigue siendo igual de rápido y nadie más en tu red podrá ver tus datos.

También puedes usar **Buscar en la red** (misma Wi-Fi) o **Introducir a mano** la IP, el puerto (8765) y el código de acceso que muestra el programa.

### Uso fuera de casa con Tailscale

Si el PC y el móvil están en tu red [Tailscale](https://tailscale.com), la app conecta por la IP de Tailscale (100.x) o el nombre MagicDNS aunque estés con datos móviles. El adaptador de Tailscale debe estar como red "Privada" en Windows para que el firewall lo permita.

### Privacidad

Tus datos solo viajan entre tu móvil y tu PC. Lee la [política de privacidad](privacy.html).

---

## English

**Monitor PC** is a portable Windows program that shows CPU, GPU, RAM, disk, network usage and temperatures in a floating window, and serves them to your phone over your local network. With the Android app **PC Gauge** you see everything live on your phone, plus the system information.

### Download

[**Download MonitorPC_portable.exe**](MonitorPC_portable.exe)

No installation needed: download it and run it.

### Requirements

- Windows 10 or 11.
- **Run as administrator** to read every sensor (without admin it still works, showing "N/A" where a value is missing). As administrator it also creates the firewall rules itself (TCP 8765 and UDP 8766), which only accept connections from your local network and Tailscale.
- Optional: **PawnIO** driver (<https://pawnio.eu>) for CPU temperatures and fans.
- PC and phone on the same network (or the same Tailscale network, see below).

### Pair with the Android app

1. Open Monitor PC on the PC.
2. From the system tray icon choose **"Emparejar móvil (QR)…"** ("Pair phone"; the PC program is in Spanish), or Ajustes → Panel móvil. A QR code appears.
3. In the Android app tap **Scan QR code** and point at the screen.
4. Done: the PC shows up in "My PCs". Tap it to see live data.

**Recommended:** in Ajustes → Panel móvil tick **"Pedir código de acceso"** ("require access code"). The QR already carries the code, so pairing stays just as fast and nobody else on your network can see your data.

You can also use **Search the network** (same Wi-Fi) or **Enter manually** with the IP, port (8765) and the access code shown by the program.

### Remote use with Tailscale

If the PC and the phone are on your [Tailscale](https://tailscale.com) network, the app connects through the Tailscale IP (100.x) or MagicDNS name even on mobile data. The Tailscale adapter must be set as a "Private" network in Windows so the firewall allows it.

### Privacy

Your data only travels between your phone and your PC. Read the [privacy policy](privacy.html).
