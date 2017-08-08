# pygano

## information

(really) simple script to hide a text in an image. 

The only goal here was to play with pillow on image processing. 

## install

Be sure to have python 3.x installed.

```
pip3 instsall pillow
git clone https://github.com/jdelhaye/pygano
```

## Example

    - encode a message 
```
./pygano.py -e <image_path> "here is the text"
```
    - retrieve a message from an image
```
./pygano.py -d <file_path>
```
