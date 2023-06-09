# Moon texture maps


These model files can be used for the *Shake*Movie repository and moved/linked to:
``
shakemovie/maps
``

## Infos

- Map:

needs .TGA image format, store without compression, no alpha channel<br>
size: 8192 x 4096 pixels


- Logo image:

needs graymap file format .PGM, store as binary (without comment line in case GraphicConverter is used)<br>
size: variable

0. create on keynote presentation: logo-incite.key
   -> store slides as PNG images

1. convert to PGM format with imagemagick convert:
   ```
   > ./convert_logo.sh
   ```

logo size small:
* width x height: 250 x 50

logo size big: 3x bigger
* width x height: 750 x 150


## Example

**file**: topo_moon8192.ppm.tar.bz2

- compressed by `tar cvjf topo_moon8192.ppm.tar.bz2 topo_moon8192.ppm`

- decompress by `tar xvjf topo_moon8192.ppm.tar.bz2` 

You might have to uncompress the files you want using the bunzip2 command.

