# Weon4JS
## Translate **weon** and **weas** for all the world!
## Traductor de weón, weones y weás para todo el mundo!

Weon4JS es un módulo que traduce frases chilenas con weón y derivados, según la interpretación gramatical de sus palabras.

La clase **Wn** de *Weon4JS* se emplea para traducir las frases con partículas de weón. Por ahora, el módulo no distingue más modismos chilenos.

Hay una versión online de este traductor, lo encuentras [acá](https://interpretaweon.web.app/)

Si deseas aprender a entender weón, puedes consultar el [siguiente enlace](https://github.com/fkatv/pyweon/tree/master/learn)

Si deseas ver la versión de este traductor de español chileno en Python, puedes visitarlo [acá!](https://github.com/fkatv/pyweon)

## Modo de uso:

```
import Wn from './weon4.js'
wn = new Wn()

// in some javascript app...

const traduceWeon = (frase) => { // frase = "una frase con alguna weá aweoná"
  let T = wn.translate(L, lang="es") // spanish translate
  console.log(T) //arreglo: [frase_corregida, traducción_frase]
  let frase_corregida = T[0]
  let traduccion = T[1]
  return traduccion
}

// ...
```

De Chile pal mundo.

Fkatv.
