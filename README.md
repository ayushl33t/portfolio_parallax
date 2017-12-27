# portfolio_parallax
Portfolio -basic parallax section template on basic HTML5 and CSS3  

--html--
  make div for images 
  span for text on image overlay
  make sections 

--css--
  for adding image 

```
.pimg1{
  background-image: url('../res/pimg1.jpeg');
  min-height: 100%;
}
```
  
  for addin parallax to each image
```
.pimg1,.pimg2,.pimg3{
  position: relative;
  opacity: 0.70;
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;

  /*
  Paralex code x-x
  */
  background-attachment: fixed;
}
```



