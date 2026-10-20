# Repositorio de paquetes de Quantum Linux

Aquí viven los paquetes propios de [Quantum Linux](https://quantumlinux-arch.github.io)
(Quantum Shell, Fotón, Quantum Store, Centro Quantum…). Los sistemas instalados
los reciben solos con cada actualización: **no hace falta descargar nada a mano**.

Los paquetes están en la Release [`x86_64`](https://github.com/QuantumLinux-arch/quantum-repo/releases/tag/x86_64)
y van firmados con la clave de Quantum Linux:

```
A8C6 45AA 66BB 4405 80DE  596B D416 458B 54B2 90FA
```

La clave pública está en [`quantum.asc`](quantum.asc) y la instala el paquete `quantum-keyring`.

Configuración de pacman (Quantum ya la trae):

```ini
[quantum]
SigLevel = Required
Server = https://github.com/QuantumLinux-arch/quantum-repo/releases/download/$arch
```
