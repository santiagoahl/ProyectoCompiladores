<h1 align="center">
  <br>
  <a href="https://github.com/eguar11011/ProyectoCompiladores"><img src="https://cdn-icons-png.flaticon.com/512/2748/2748829.png" alt="Compilers!" width="200"></a>
  <br>
  ProyectoCompiladores
  <br>
</h1>

<h4 align="center">Un lenguaje de programación junto con su compilador propio desarrollado en C/C++ basado en el uso de expresiones regulares. 
</h4>

<p align="center">
  <a href='https://github.com/shivamkapasia0' target="_blank"><img alt='c' src='https://img.shields.io/badge/C/C++-100000?style=for-the-badge&logo=c&logoColor=FFFFFF&labelColor=3466F0&color=4A9AE0'/></a> <a href='https://github.com/shivamkapasia0' target="_blank"><img alt='flex' src='https://img.shields.io/badge/FLEX-100000?style=for-the-badge&logo=flex&logoColor=000000&labelColor=FFFFFF&color=2FBA66'/></a> <a href='https://github.com/shivamkapasia0' target="_blank"><img alt='gnu' src='https://img.shields.io/badge/GNU_BISON-100000?style=for-the-badge&logo=gnu&logoColor=000000&labelColor=FFFFFF&color=BAC0C7'/></a> <a href='https://github.com/shivamkapasia0' target="_blank"><img alt='llvm' src='https://img.shields.io/badge/LLVM-100000?style=for-the-badge&logo=llvm&logoColor=FFFFFF&labelColor=7BC6ED&color=6DAFFF'/></a>
</p>

<p align="center">
  <a href="#key-features">Características</a> •
  <a href="#how-to-use">Cómo usar</a> •
  <a href="#credits">Creditos</a> •
  <a href="#license">Licencia</a> •
</p>


## Características

En este proyecto hemos desarrollado a baja escala un lenguaje de programación cuyo compilador está construido con **C/C++**. Se han programado todas las fases de un compilador: Un analizador léxico con `Flex`, un parser con `Bison` y un ensamblador con `LLVM`.

* **Analizador léxico**. Construido con `Flex`. Como se
estudió en el curso, este tendrá como objetivo separar
las cadenas de caracteres en **tokens**. En particular,
aprovechamos la experiencia obtenida en el desarrollo
del primer proyecto del curso, en donde pudimos crear
un lexer basado en expresiones regulares.
* **Analizador sintáctico**. Construido con `Bison`.El obje-
tivo principal de este componente es generar **árboles
de sintaxis abstracta** cada vez que se tokeniza una
instrucción.
* **Assembly**. Construido con la colección de módulos
de compilador reutilizables del proyecto `LLVM`. En esta
etapa codificamos cada **árbol de sintaxis abstracta** en
código de máquina


## Cómo usar

Para clonar este proyecto, siga estos pasos:
```bash
# Clone el repositorio
$ git clone https://github.com/eguar11011/ProyectoCompiladores.git

# Ingrese al repositorio
$ cd ProyectoCompiladores

# Ingrese al código fuente
$ cd finalproject
```

## Creditos

Este software utiliza los siguientes paquetes:
- [Flex](https://westes.github.io/flex/manual/)
- [GNU Bison](https://www.gnu.org/software/bison/)
- [LLVM](https://llvm.org/)


## Licencia

MIT

---


> Santiago Ahumada [@santiagoahl](https://github.com/santiagoahl) &nbsp;&middot;&nbsp;
> David Mora [@DavidFM43](https://github.com/DavidFM43) &nbsp;&middot;&nbsp;
> Eduards Mendez [@eguar11011](https://github.com/eguar11011) &nbsp;&middot;&nbsp;
