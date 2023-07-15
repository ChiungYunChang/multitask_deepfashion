## Multitask_deepfashion
(**NOTE**: For multi-label problem the loss be be **nn.BCELoss()** or **nn.BCEWithLogitsLoss()**)


**Abstract**  
Using a pre-trained model, build a deep network that predicts the category and attributes of an item simultaneously. 

**version** <br>
`Python 3.6.9` <br> 
`torch==1.7.0+cu101` <br>
`torchsummary==1.5.1` <br>
`torchtext==0.3.1` <br>
`torchvision==0.8.1+cu101`


## Prepare Data
   
*  Category (class classification): 10  
*  Attribute (multi label classification): 15

data from : https://drive.google.com/file/d/1alC3j-4yaHfZe4bYkr6M7Snxeru4GzYN/view 
