# AppImage para Cisco Packet Tracer 7.3

Fork de: https://github.com/konradmb/PacketTracer-AppImage

*🎶I'm already Tracer🎶*

### A configuration for [pkg2appimage](https://github.com/AppImage/pkg2appimage) to build Packet Tracer in AppImage form.

## Como usar?

*Tenha certeca de ter o pacote `git` instalado.

1. Clone este repositório e mude para dentro dele usando `cd`

    ```shell
    git clone https://github.com/konradmb/PacketTracer-AppImage.git
    cd PacketTracer-AppImage/
    ```
2. Download pkg2appimage tool e crie o executável
   ```shell
   wget https://github.com/AppImage/pkg2appimage/raw/master/pkg2appimage
   chmod +x pkg2appimage
   ```
3. Faça a build:

   ```shell
   ./pkg2appimage PacketTracer.yml
   ```

4. Depois do processo, o AppImage do Packet Tracer estará no diretório `out/`.

5. Para rodar a aplicação, basta dar dos cliques no AppImage, como qualquer outro AppImage. Confira também se
o AppImage está com permissões de execução das propriedades do arquivo. (Botão direito sobre>>Propriedades)

## Download do AppImage Pronto

Para aqueles que não querem buildar o seu prop AppImage, tomei a liberdade de fazer upload do app já no formato,
confira a página de releases: https://github.com/Diolinux/PacketTracer-AppImage/releases/

Vale lembrar que é preciso de uma conta na Network Academy da Cisco para poder usar o sofware: https://www.netacad.com/pt-br





