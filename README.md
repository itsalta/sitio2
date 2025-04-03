<!-- Para abrir el preview en Atom: ^ (control) + shift + M -->

# README
[![platform][License]][License]
[![platform][Platform]][Platform]

<!-- Para crear un índice -->
## Table of Contents
- [Requirements](#requirements)
- [Installation](#installation)
- [Download](#download)
- [Author](#author)
- [License](#license)
- [Otros Ejemplos](#otros-ejemplos)
  - [Bloques de códigos](#bloques-de-códigos)
  - [Resaltar texto](#resaltar-texto)
  - [Badges](#badges)
  - [Imagen](#imagen)

## Requirements
|Platform|Language|IDE|
|:----------:|:--------:|:---:|
|[![platform][iOS_9.0]][iOS_9.0]|[![language][swift_3.0]][swift_3.0]|[![ide][xcode_3.2]][xcode_3.2]|

## Installation
Clonar el repositorio, luego en una terminal ejecutar `pod install` para instalar las dependencias del proyecto. Por último abrir `NAME.xcworkspace` y compilar la App.

## Download
App disponible en [iTunes][AppStore] para su descarga.

## Author
Matías Correnti, [@matCorrenti][myTwitter].

## License
README is available under the MIT license. See the [LICENSE](LICENSE) file for more info.




## Otros Ejemplos

### Bloques de códigos
```swift
func texto(texto: String = "default") {
  //Comentario
  let tex: String = "Python syntax highlighting"
  let tex2: String = texto
}
```
```swift
let selector = #selector(viewDidLoad)
view.backgroundColor = .red
let toView = context.view(forKey: .to)
let view = UIView(frame: .zero)
```
~~~ swift
let text: String = "Texto"
~~~


### Resaltar texto
> *Cursiva*
>> **Negrita**
>>> ***Negrita-Cursiva***

(Se puede usar el signo `_` en lugar de `*`).


### Badges
[![AppStore][appStoreBagge]][appStore]
[![Twitter Follow][twitter]][myTwitter]
[![TestXc][testXc]][testXc]
[![CocoapodsDocs][cocoDocs]][cocoDocs]
[![Tag][tag]][tag]
[![Release][release]][release]
[![IssuesOpen][issuesOpen]][issuesOpen]
[![LicenseGitHub][licenseGitHub]][licenseGitHub]
[![DowEXTClass][dowEXTClass]][dowEXTClass]
[![CommitEXT][commitEXT]][commitEXT]


### Imagen
![Imagen de logo][logo]




<!-- Links -->
[myTwitter]:http://twitter.com/matCorrenti
[iOS_9.0]:https://img.shields.io/badge/iOS-≥_9.0-5658FE.svg?colorA=5658FE
[swift_3.0]:https://img.shields.io/badge/Swift-≥_3.0-EF5138.svg?colorA=EF5138
[xcode_3.2]:https://img.shields.io/badge/Xcode-≥_3.2-2A92F4.svg?colorA=2A92F4
[Platform]:https://img.shields.io/badge/platform-ios-lightgrey.svg
[License]:https://img.shields.io/badge/license-MIT-383838.svg


<!-- Otros -->
[appStore]:https://itunes.apple.com/ar/app/luteranos/id1137428395
[appStoreBagge]:https://img.shields.io/badge/Download_App-Luteranos-1C5FAD.svg
[twitter]:https://img.shields.io/twitter/follow/matCorrenti.svg?style=social&label=Follow&maxAge=3600
[testXc]:https://img.shields.io/badge/Xcode-≥_3.2-2A92F4.svg?colorA=0873A4
[cocoDocs]:https://img.shields.io/cocoapods/metrics/doc-percent/EXTClass.svg
[tag]:https://img.shields.io/github/tag/Saitco/EXTClass.svg
[release]:https://img.shields.io/github/release/Saitco/EXTClass.svg
[issuesOpen]:https://img.shields.io/github/issues/Saitco/README.svg
[licenseGitHub]:https://img.shields.io/github/license/Saitco/README.svg
[dowEXTClass]:https://img.shields.io/github/downloads/Saitco/README/total.svg
[commitEXT]:https://img.shields.io/github/commits-since/Saitco/EXTClass/0.3.2.svg


<!-- Links Imagenes -->
[logo]:https://github.com/Saitco/README/blob/master/img/rosaL.png "Icono de la App"
