# Mis dotfiles

## ¿Qué es esto?
Es un repo mediante el cual puedo automatizar la instalación de las Apps que suelo tener en mis Mac, además de la configuración del propio macOS.

## ¿Cúal es el proceso?
1. Actualizar o instalar la última versión de macOS desde la App Store
2. Instalar Xcode desde la App Store, abrirlo y aceptar el acuerdo de licencia
3. Instalar el macOS Command Line Tools mediante el comando xcode-select --install
4. Clonar este repo a tu Mac
5. Ejecutar el install.sh
6. Reiniciar el Mac para finalizar el proceso

## ¿Qué utiliza?
* [Homebrew](https://brew.sh/index_es.html)
* [Homebrew Bundle](https://github.com/Homebrew/homebrew-bundle)
* [Homebrew-Cask](https://caskroom.github.io)
* [mas-cli](https://github.com/mas-cli/mas)

Aunque en realidad toda la magia se basa en dos utilidades, **Homebrew-Cask** con la que podemos instalar varios cientos de Apps como Google Chrome, Alfred, etc., ([buscar más aquí](https://caskroom.github.io/search)) desde el terminal, y **mas-cli** con la que podemos instalar Apps de la App Store también desde el terminal.

## Agradecimientos
Conocí esto de los dotfiles gracias a [este post](https://driesvints.com/blog/getting-started-with-dotfiles/) de Dries Vints y su repo https://github.com/driesvints/dotfiles. Repo del que además me he inspirado bastante mientras he ido creando el mío.
