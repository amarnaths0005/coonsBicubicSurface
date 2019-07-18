# coonsBicubicSurface
HTML5 Application to manipulate a Coons Bicubic Surface using its corner points, U and W tangents and UW twists.

Requirements:
   1. Should enable the user to modify the x, y, z coordinates of the four points
       corresponding to the u, w values of (0, 0), (0, 1), (1, 0) and (1, 1).
       The range for these coordinates should be [-1,1].
   2. Should enable the user to modify the x, y, z components of the tangent 
       vector with respect to u, at the four points corresponding to the 
       u, w values of (0, 0), (0, 1), (1, 0) and (1, 1). 
       Not necessarily the normalized tangents. The range for these tangent vector 
       components should be [-10, 10].
   3. Should enable the user to modify the x, y, z components of the tangent 
       vector with respect to w, at the four points corresponding to the 
       u, w values of (0, 0), (0, 1), (1, 0) and (1, 1). 
       Not necessarily the normalized tangents. The range for these tangent vector 
       components should be [-10, 10].
   4. Should enable the user to modify the x, y, z components of the twist 
       vector with respect to u and w, at the four points corresponding to the 
       u, w values of (0, 0), (0, 1), (1, 0) and (1, 1). 
       Not necessarily the normalized twist vectors. The range for these twist vector 
       components should be [-10, 10].
   5. Should display the Coons Bicubic Patch on the screen, and this surface should 
      change dynamically as the user modifies any of the values using sliders. 
      Perspective View.
   6. Should display the bounding box of dimension 2 units, centred at the origin.
   7. Should enable the user to modify the camera angle, from which viewing is done.
   8. Should enable the user to modify the u, w values, and should display a moving point
      on the surface as the user modifies these values using the sliders.
   9. All user input should be via sliders.
   10. Should use WebGL, in the form of three.js. 

    Tested on Chrome, Firefox and Edge, on Windows.
    
    ![Screenshot of CoonsBicubicSurface](https://github.com/amarnaths0005/coonsBicubicSurface/blob/master/coons.png)
