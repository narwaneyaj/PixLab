1. Open Picture.java and look for the method getPixels2D. Is it there?
~No, it is not.

2. Open SimplePicture.java and look getPixels2D. Is it there?
~Yes, it is.

3. Does the following code compile?
         DigitalPicture p = new DigitalPicture();
~It will not be able to compile because DigitalPicture is an interface, not a class and therefore it doesn't have any methods that have specific commands. Although it does have methods, there is nothing inside those methods. 
         
4. Assuming that a no-argument constructor exists for SimplePicture, would the following
code compile?
         DigitalPicture p = new SimplePicture();
~No, it would not be able to compile. It shows that p is a DigitalPicture object and DigitalPicture is just an interface with no defined methods and therefore no objects can be made from it. 
         
5. Assuming that a no-argument constructor exists for Picture, does the following code
compile?
         DigitalPicture p = new Picture();
~No, it would not be able to compile. It shows that p is a DigitalPicture object and DigitalPicture is just an interface with no defined methods and therefore no objects can be made from it. 
         
6. Assuming that a no-argument constructor exists for Picture, does the following code
compile?
         SimplePicture p = new Picture();
~Yes, this code would compile because SimplePicture is a type of Picture and does not have any undefined methods. 
      
7. Assuming that a no-argument constructor exists for SimplePicture, does the following
code compile?
         Picture p = new SimplePicture();
~No, this code will not compile because it is backwards on the Picture hierarchy and the object p cannot be a Picture object and creating a new SimplePicture object because Picture is broader and contains SimplePicture. 