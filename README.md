# Manticore-tiny-changes

Setup:
1. Instalar manticore
```pip install manticore```
2. Instalar yices2 (el solver particular que manticore usa por defecto):

   Descargar https://yices.csl.sri.com/releases/2.6.4/yices-2.6.4-x86_64-pc-linux-gnu.tar.gz

   Una vez dentro del directorio descomprimido ```sudo ./install-yices``` (darle permisos de ejecucion)
3. Sobreeescribir el código fuente de manticore con el contenido de este repo:

  ```python3 -c "import manticore as _; print(_.__file__)"``` para obtener el path a la instalación de manticore: ```<path>/manticore/__init__.py```
  
  output de ejemplo: ```/usr/local/lib/python3.8/dist-packages/manticore/__init__.py ```
  
  (sobreescribir el contenido de ```<path>/manticore```)
