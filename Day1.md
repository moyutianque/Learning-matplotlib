##1.random color in the function:
   The parameter `c` in the funtion is about the color of the lines or the shapes, usually the color need to use three value to represent one color so we use `numpy.random.rand(3,1)` to create 3 random variable in 1 line. Then I pass the parameter to `c`
   
   ```python
   #use default maker--circle with area "area"
   import numpy as np
   import import matplotlib.pyplot as plt
   plt.scatter(x,y,s=area,c=np.random.rand(3,1),alpha=0.5) 
   ```
   
##2.
