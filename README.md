# Requirements
opencv  
opencv-contrib-python >= 4.5.2  
pillow  
python-docx  

# usage  
put your image folder under ./img  
run this command:  
```
python repeat.py  
```  
You could modify line 97 in repeat.py to decide the folder depth, for example:
```  
    for e in p.glob("./5月1日/*.*g"): #p.glob("./*.*g"):
```  
After this command ended, you could get a doc file and get repeated images in ./repeatedDir