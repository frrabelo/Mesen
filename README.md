# Mesen

Mesen is a multi-system emulator (NES, SNES, Game Boy, Game Boy Advance, PC Engine, SMS/Game Gear, WonderSwan) for Windows, Linux and macOS.  

## Releases

The latest stable version is available from the [releases on GitHub](https://github.com/SourMesen/Mesen2/releases).  

## Development Builds

[![Mesen](https://github.com/SourMesen/Mesen2/actions/workflows/build.yml/badge.svg)](https://github.com/SourMesen/Mesen2/actions/workflows/build.yml)

#### <ins>Native builds</ins> (recommended) ####

These builds don't require .NET to be installed.  

* [Windows 10 / 11](https://nightly.link/SourMesen/Mesen2/workflows/build/master/Mesen%20%28Windows%20-%20net8.0%20-%20AoT%29.zip)  
* [Linux x64](https://nightly.link/SourMesen/Mesen2/workflows/build/master/Mesen%20%28Linux%20-%20ubuntu-22.04%20-%20clang_aot%29.zip)  (requires **SDL2**)
* [macOS - Intel](https://nightly.link/SourMesen/Mesen2/workflows/build/master/Mesen%20%28macOS%20-%20macos-13%20-%20clang_aot%29.zip)  (requires **SDL2**)
* [macOS - Apple Silicon](https://nightly.link/SourMesen/Mesen2/workflows/build/master/Mesen%20%28macOS%20-%20macos-14%20-%20clang_aot%29.zip)  (requires **SDL2**)

#### <ins>.NET builds</ins> ####

These builds require **.NET 8** to be installed (except the Windows 7 build which requires .NET 6).  
For Linux and macOS, **SDL2** must also be installed.

* [Windows 7 / 8 (.NET 6)](https://nightly.link/SourMesen/Mesen2/workflows/build/master/Mesen%20%28Windows%20-%20net6.0%29.zip)  
* [Linux x64 - AppImage](https://nightly.link/SourMesen/Mesen2/workflows/build/master/Mesen%20(Linux%20x64%20-%20AppImage).zip)  
* [Linux ARM64](https://nightly.link/SourMesen/Mesen2/workflows/build/master/Mesen%20%28Linux%20-%20ubuntu-22.04-arm%20-%20clang%29.zip)  
* [Linux ARM64 - AppImage](https://nightly.link/SourMesen/Mesen2/workflows/build/master/Mesen%20(Linux%20ARM64%20-%20AppImage).zip)


#### <ins>Notes</ins> ####

Other builds are also available in the [Actions](https://github.com/SourMesen/Mesen2/actions) tab.

**SteamOS**: See [SteamOS.md](SteamOS.md)

## Compiling

See [COMPILING.md](COMPILING.md) 

##News: 
I created a 32-bit (x86) Linux version in AppImage format for my personal use, as I couldn't find one to download. Feel free to download and have fun.
Mesen (Linux x86 - AppImage)
Digest: 
sha256:5cac4ecdea2706708186a4783f8abe6813656a11f24e7a9433d55542ce797944 
Download: https://github.com/frrabelo/Mesen/releases/tag/Linux-x86-32bits
 
Annotations: 
appimage (clang_appimage, ubuntu-22.04, x86, Linux/appimage/appimage-x86.sh)
Node.js 20 actions are deprecated. The following actions are running on Node.js 20 and may not work as expected: actions/cache@v4, actions/checkout@v4, actions/setup-dotnet@v4, actions/upload-artifact@v4, DamianReeves/write-file-action@master. Actions will be forced to run with Node.js 24 by default starting June 2nd, 2026. Node.js 20 will be removed from the runner on September 16th, 2026. Please check if updated versions of these actions are available that support Node.js 24. To opt into Node.js 24 now, set the FORCE_JAVASCRIPT_ACTIONS_TO_NODE24=true environment variable on the runner or in your workflow file. Once Node.js 24 becomes the default, you can temporarily opt out by setting ACTIONS_ALLOW_USE_UNSECURE_NODE_VERSION=true. For more information see: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/
 
```json
{
  "resposta": "Vou te explicar de um jeito bem simples:\n\nImagine que as pequenas ferramentas usadas nos bastidores pelo GitHub para montar o seu programa (como se fossem pequenos robôs operários) funcionam usando um 'motor' chamado **Node.js**. A versão atual desse motor que eles estão usando é a 20.\n\nEsse aviso de texto amarelo é apenas o GitHub dando um 'toque' preventivo dizendo o seguinte: *\"Olha, esse motor versão 20 está ficando velhinho. Em breve (a partir do meio do ano de 2026), nós vamos mudar o padrão para um motor mais novo, a versão 24.\"*\n\n**Você precisa se preocupar ou consertar isso?**\n**Não!** É apenas um aviso informativo (um alerta padrão para os desenvolvedores se prepararem para o futuro). Seu programa foi compilado perfeitamente (veja o selinho verde de 'Success' lá em cima e o arquivo do seu AppImage gerado na parte de baixo). \n\nVocê pode ignorar esse aviso com total tranquilidade, pois não afeta em nada o funcionamento do seu programa agora.",
  "status": "sucesso"
}
```


## License

Mesen is available under the GPL V3 license.  Full text here: <http://www.gnu.org/licenses/gpl-3.0.en.html>

Copyright (C) 2014-2025 Sour

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
