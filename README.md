# AppImage for Cisco Packet Tracer
*🎶I'm already Tracer🎶*

### A configuration for [pkg2appimage](https://github.com/AppImage/pkg2appimage) to build Packet Tracer in AppImage form.

## How to use it?

1. Clone this repository and go to its directory.
    ```shell
    git clone https://github.com/konradmb/PacketTracer-AppImage.git
    cd PacketTracer-AppImage/
    ```
2. Download pkg2appimage tool and make it executable.
   ```shell
   wget https://github.com/AppImage/pkg2appimage/raw/master/pkg2appimage
   chmod +x pkg2appimage
   ```
3. Build it:
   * If you want to build Packet Tracer 7.2.1:
   ```shell
   ./pkg2appimage PacketTracer.yml
   ```
   * Or if you want to build Packet Tracer 7.1.1:
   ```shell
   ./pkg2appimage PacketTracer-7.1.yml
   ```
4. After a short break you should get an executable inside `out/` directory.


## Differences from official version 

* PacketTracer7 binary is patched to change `~/.packettracer` file name to `~/.ptappimage00` as to prevent conflicts with Packet Tracer executed from normal folder.
