##1.random color in the function:
   The parameter `c` in the funtion is about the color of the lines or the shapes, usually the color need to use three value to represent one color so we use `numpy.random.rand(3,1)` to create 3 random variable in 1 line. Then I pass the parameter to `c`
   alpha is the prameter for transparency. Here `0.5` means 50% transparency

   ```python
   #use default maker--circle with area "area"
   import numpy as np
   import import matplotlib.pyplot as plt
   plt.scatter(x,y,s=area,c=np.random.rand(3,1),alpha=0.5) 
   ```
   
##2. how does plot()/scatter() work

   simple view: x and y can be single variable or list, if pass single variable to the parameter, will add one point to the diagram. While pass list to the parameter, the function will pair all the x and y, and iteratively pass them to the function
