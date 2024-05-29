
## Proyecto del Autor Original
 
<!-- PROJECT SHIELDS -->
[https://github.com/r3nt0n/bopscrk](https://github.com/r3nt0n/bopscrk)

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/r3nt0n/bopscrk">
    <img src="https://github.com/r3nt0n/bopscrk/blob/master/img/logo_raster.svg" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">bopscrk</h3>

  <p align="center">
    Generate smart and powerful wordlists for targeted attacks
    <br />
    <p align="center"><img src="https://github.com/r3nt0n/bopscrk/blob/master/img/bopscrk-2.4.5.gif" /></p>  
    <br />
    <br />
  </p>
</div>
<br />
<br />


# Azanet MOD
<!-- GETTING STARTED -->
El proyecto original se ha modificado para solicitar también la ruta de un archivo que contenga un listado de palabras separadas por comas.
<br />

## Instalación

*Clonar repositorio e instalar:*

```
git clone --recurse-submodules https://github.com/azanet/FORK-bopscrk_MOD
cd bopscrk
pip install -r requirements.txt
```


### Iniciar el 'Modo Interactivo'
```
bopscrk -i
```
<br />

<!-- USAGE EXAMPLES -->
## Uso
```

  -h, --help         show this help message and exit
  -i, --interactive  interactive mode, the script will ask you about target
  -w                 words to combine comma-separated (non-interactive mode)
  --min              min length for the words to generate (default: 4)
  --max              max length for the words to generate (default: 32)
  -c, --case         enable case transformations
  -l, --leet         enable leet transformations
  -n                 max amount of words to combine each time (default: 2)
  -a , --artists     artists to search song lyrics (comma-separated)
  -o , --output      output file to save the wordlist (default: tmp.txt)
  -C , --config      specify config file to use (default: ./bopscrk.cfg)
  --version          print version and exit

```

<br />
<br />









