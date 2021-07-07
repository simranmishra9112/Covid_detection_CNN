* In this project i have worked on Covid detection using CNN. I have used the chest x-ray images that are available from the open source from covid chest x-ray dataset.

* The pre trained model that is implemented is VGG-16 which is a convolution network architecture. The accuracy that i am receiving is around 85 %

* The another agenda of this project is to visualize the Class Activation maps. The class activation map is basically what ml algorithem has learned in the last convolution layer. 
    i.e If the model says the image of chest is COVID, why is the image covid ??? This is where we use GRAD-CAM (Gradient - Class Activation Map) 
    
    * This grad-cam function returns the heat map, which later is mapped on the input xray, with this we can determine which area in chest has COVID-19

* Dataset : "https://www.dropbox.com/s/e1r2laj50nh4tez/COVID-19_Radiography_Dataset.zip?dl=0" 
