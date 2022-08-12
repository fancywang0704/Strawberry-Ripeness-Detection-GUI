# Making strawberry ripeness detection GUI
## Steps
   - install designer (Ubuntu Linux) with:
   
   ![image](https://user-images.githubusercontent.com/101705236/184282441-83ceb9f7-8268-4f14-974c-3faae4f2592e.png)
   
   - start designer （Ubuntu Linux) with:
   
   ![image](https://user-images.githubusercontent.com/101705236/184282714-1ff2784e-7937-4c63-92b9-4b0b197e7cf4.png)
 
   - export my design to a UI file. Click File > Save As > berry_detection.ui
   
   - convert the ui code to a python file with:
   
     pyuic5 /home/linux/berry_detection.ui -o berry_detection.py
     
   - convert the qrc code to a python file with:
     
     pyrcc5 res.qrc -o res_rc.py
     
   - run main.py and GUI appears


## Initial interface display

<div align="center">

  ![1](https://user-images.githubusercontent.com/101705236/184280870-f53b2aab-08b3-4b8e-b7c3-c264b8171148.png)
  
</div>
