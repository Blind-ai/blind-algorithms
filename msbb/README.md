open music sheet box bounding v1.0
======================
The goal of this is to find bounding boxes into a music sheet.<br />

## Easy dependencies installer

this installation script has been made on ubuntu 18.04.
Its use is to easily install python opencv, numpy....

```
pip3 install -r requirement.txt
```

## Usage

The script can be found in src/

#### Examples:
Apply optic flow in realtime from webcam flux, previsualize and save the flux.<br /> 
```
python3 src/sheet_to_bounding_box.py data/images/page0.jpg [nb threads]
```

## Features

- [x] .images
- [x] .pdfs
- [x] .threading
- [x] .return bounding boxes
- [ ] .write bouding boxes into file


## Examples 
### 1 thread

![](https://github.com/Cjdcoy/openmsbb/blob/master/data/demo.gif)

### 4 threads

![](https://github.com/Cjdcoy/openmsbb/blob/master/data/demo2.gif)

