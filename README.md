# WD2 - 5 Page Website

5 Page Website designed by Michael Gogarty - 472900572

This assessment was a lot of fun, front-end development is what I really enjoy doing and can utilize my skills in image manipulation and creating unique designs. I learnt a lot from this assessment, mainly psuedoclasses and the effects you can apply - such as the hamburger drop down menu animation with pure CSS and using a checkbox to enable functionality.

Also to mention, taking feedback from the last web design assessment, I have applied inline-block to the three SVGs within the index.html.

## Criteria

## Part B - CSS

### Mediaquery incorporating two layouts. Mobile and Desktop

Mobile responsive layout is defined at `width: 568px`

### Demonstrated use of two type of CSS combinator and three pseudoclasses

**Two types of CSS combinators include**

Child combinator: `index.css - line 20`
```
.sponsor-container > img {  
 display: inline-block;  
 max-width: 200px;  
 max-height: 200px;  
 padding: 1em;  
}
```

General sibling combinator: `index.css - line 1` 
```
p ~ span {  
 font-weight: bold;  
 font-size: 0.9em;  
}
```

**Three types of CSS pseudoclasses include**

Hover pseudoclass: `index.css - line 75`
```
.img-container > img:hover {  
 transform: scale(1.05,1.05);  
 transition:all 0.25s ease-in-out;  
}
```

Checked psuedoclass: `h-nav.css - line 143`
```
#mobile-menu:checked + .mobile-nav {  
 display: block;  
 }
 ```

Focus psuedoclass: `webform.css - line 22`
```
input:focus {  
 background: rgb(109, 109, 109);  
}
```

### Animate in and out of :hover on menu or hamburger menu

Animation on nav links with :hover  
```
nav > ul > li:hover {  
 color: #b1b1b1;  
 transition: 300ms;  
}
```

Keyframe animation on hamburger menu

```
@keyframes drop {  
 from {  
 	transform: translateY(-100%);  
 	opacity: 0.1;  
 	}  
 to {  
 	transform: translateY(0%);  
 	opacity: 1;  
 	}  
 }
 ```
 
 # Part C - Images
 
 ### Three Images in content list cropped square
 
 ![Cropped Images](https://i.imgur.com/RvuE7Bc.png)
 
 ### One example of a composited image created from at least two images
 
 The header is two images into one, the male was cut out with pen tool and placed on top of the stock image. Also one of the cropped images is manipulated.
 
![Manipulated Images](https://i.imgur.com/3Ym743F.jpeg)

### Header image incorporates the use filter selector in CSS

For the header, I used the Screen blending option: h-nav.css - line 1.  

```
.bg-screen {  
 background: url(../src/desktop-img.jpg), var(--con-header);  
 background-repeat: no-repeat, no-repeat;  
 background-size: cover;  
 background-blend-mode: screen;  
 display: flex;  
 flex-direction: column;  
}
```  

## Part D - Validation
### Screenshot of W3C Validation of HTML/CSS
![Validation](https://i.imgur.com/B4FuxEH.png)

### Cross-Browser test three examples including mobile phone
![Cross-site Validate](https://i.imgur.com/qRs0OEE.png)

![Mobile Test](https://i.imgur.com/BqmUmdn.png)

## Part E - Metacognition

### Sources of all images, including copyright or license requirements

Manrope - Font: 
Copyright 2020 The Manrope Project Authors (https://github.com/sharanda/manrope)

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is copied below, and is also available with a FAQ at:
http://scripts.sil.org/OFL

Image 1:   
https://creativecommons.org/publicdomain/zero/1.0/  
https://www.hippopx.com/en/asphalt-blur-buildings-city-dark-downtown-evening-355793  
License to use [Creative Commons Zero - CC0](https://creativecommons.org/publicdomain/zero/1.0/deed.en)  

Image 2:  
https://www.hippopx.com/en/asphalt-barefoot-blur-jacket-landscape-model-mountain-359759  
License to use [Creative Commons Zero - CC0](https://creativecommons.org/publicdomain/zero/1.0/deed.en)  

Image 3:  
https://www.hippopx.com/en/download/80681-7360x3319-5fe3d51137dd1c6464233f72c22384bf  
License to use [Creative Commons Zero - CC0](https://creativecommons.org/publicdomain/zero/1.0/deed.en)  

Image 4:  
https://www.hippopx.com/en/cat-mieze-kitten-tiger-cat-domestic-cat-red-cat-cat-face-75113  
License to use [Creative Commons Zero - CC0](https://creativecommons.org/publicdomain/zero/1.0/deed.en)  

Image 5:   
https://www.hippopx.com/en/skateboard-child-boy-sunset-afterglow-landscape-skateboarding-71961    
License to use [Creative Commons Zero - CC0](https://creativecommons.org/publicdomain/zero/1.0/deed.en)   

Image 6:  
https://www.hippopx.com/en/couple-photoshoot-wedding-wedding-portraits-wedding-photoshoot-greece-bride-14632  
License to use [Creative Commons Zero - CC0](https://creativecommons.org/publicdomain/zero/1.0/deed.en)  

Image 7:  
https://www.hippopx.com/en/man-portrait-face-person-ale-portrait-picture-theatre-187601  
License to use [Creative Commons Zero - CC0](https://creativecommons.org/publicdomain/zero/1.0/deed.en)  

### Secure original images, and describe what modifications have been made to ensure they are web-ready

The modifications I made to ensure these images were web-ready was to create a document size 500x500, then resized accordingly to fit the aspect ratio and finally saved them as low-quality JPEGs. 

As for the logo, I created that with shapes and a font-type, then exported this as an SVG. 

### Describe the tools that were used to make alterations to these images

Photoshop was used to make alterations to these images, as mentioned previously when I manipulated these images I used the pen tool, a quick selection tool additionally with select & mask to soften and feather the cut. 

### What alternative file formats could these images have been saved, why did you choose the one(s) you did

An alternative file format these images could have been saved in in would be .PNG, furthermore you could save it as a .GIF but it's really not recommended because file size is just far too high.

I decided to go for .JPEG and .SVG, simply because .JPEG isn't very heavy in file size like .PNG is and I wasn't using an alpha layer anyway. As for the shapes I used .SVGs because it's very low in file-size and .SVGs are ideal for responsive design. 

### Describe how these images best suit the message you are trying to convey for the client

These images best suit the message I'm trying to convey for the client because when reading the case-study, I saw they cater for any kind of occasion but saw that they focus on weddings, so I added an image of a newly wed couple to outline that service.

The other images I used were high quality photography shots as well, furthering the outline of the purpose of this business being photography.

The logo I created is simple and I kind of ripped off Instagram's old logo, being the camera with the flash. You can see the initials of the business with the creative design surrounding it.

### What WHS principles were followed while working on this project

Common Work Health and Safety practicies I followed while working on this project were as follows:

- Maintaining a good distance from the monitor to eliminate eye strain, also using night time display. 
- Correcting my posture while working.
- Trying my best to practice touch typing properly to ensure no injury.
- Ensuring the safety of my surrounding workspace, eliminating any hazards that posed a potentional risk.
- Taking regular breaks and stretching.