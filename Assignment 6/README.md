### 22F DH110, Alex Yoo 
# Assignment 6: Interface Design System

## 🔹 Description 
**Project Summary**
This project centers around an unsolicited redesign of MyLA311, LA City's 311 app for fielding city services for local residents. This app also aims to enhance and make more efficient the LA transit experience. Both design efforts will serve to help LA residents better utilize the public services available to them, in an effort to create a more sustainable community that follows the UN's sustainability goal for sustainable cities and communmities. 

**Process and purpose of interface design** 
The process of the interface design for my app began with the low-fidelity wireframes created during Assignment 5. There, I designed the cornerstone wireframes for the major interactions of the app, and outlined a general wireflow that reflects the intended userflow. This assignment moves further to develop the interface design of the app, focusing more on the graphic/visual elements of my app design (e.g. colour palette). Here, I test several different variations of important design elements: layout, typography, shape, colour, and colour-contrast accessibility. The process of iterating through these design properties occurs in the order listed prior (beginning with layout, ending with accessibility). 

The UI/UX design process is always iterative, and as such I may further improve the design system that I have created throughout this assignment. However, the purpose of creating this interface design is to not only ensure a more visually-appealing experience for my users, but also maximize consistency across screens and to construct a definitive style-guide for my designs moving forward. This allows me to orient myself in the visual design process, and deeply consider what colours, visual assets, etc. will be in line with my goals of designing an easy, intuitive interface that is maximally accessible. 

> Link to Figma file [here](https://www.figma.com/file/hCWuj8WsEqumdAJYi72R7P/22F-DH-110-(Copy)?node-id=138%3A1166)
> 
> View the resulting high-fidelity wireframe below (in light and dark mode). Note that my design section will begin iterating from the low-fi version of this wireframe.
![UI Wireframe](https://user-images.githubusercontent.com/101301281/200758434-c0403c4c-8e3a-4783-8322-0dd1faeef672.png)





## 🔹  Design 
### Layout variations 
<p align="center">
<img width="90%" alt="DH 110 - Layout Variation" src="https://user-images.githubusercontent.com/101301281/200746050-129369f5-92e3-455a-ade9-6052d4b83456.png">
</p>


### Typographic variations
![01 0 Text Variation](https://user-images.githubusercontent.com/101301281/200752496-8f5a88e2-a15b-4e20-bb59-fecf58debeb9.png)
![Type Variation Frames](https://user-images.githubusercontent.com/101301281/200753050-204d51a3-7b29-473b-9cfc-e79ddd10263e.png)



### Shape variations
![Shape variation](https://user-images.githubusercontent.com/101301281/200749903-f7cc846b-3481-4ee4-8fcd-699c97d1ec33.png)



### Colour variation
![Colour Variation](https://user-images.githubusercontent.com/101301281/200747210-85c0cc88-b2be-4407-9e76-d11b4a1d48f8.png)


### Accessibility check
> NOTE: I've noticed that the image quality is appearing lower for some devices. View the Figma file [here](https://www.figma.com/file/hCWuj8WsEqumdAJYi72R7P/22F-DH-110-(Copy)?node-id=138%3A1166) for better quality.

![03 1 1 Colour Contrast - Dark](https://user-images.githubusercontent.com/101301281/200748806-5d1e772b-c9be-4c95-876c-2344adfd7a73.png)
![03 1 1 Colour Contrast - Light](https://user-images.githubusercontent.com/101301281/200748811-6a91e12f-61bf-44a5-ae28-abd23a9a7b0f.png)


## 🔹  Impression test 
> Could not find a new user willing to be recorded. All quotations are paraphrased in detail based on the notes I took during testing. 

## 🔹  Design System + Summary
### Typography
- **Title:** Manrope Extra Bold, 34 pt, 1% Letter Spacing, 1.1x line height
- **Subtitle:** Manrope Medium , 21 pt, 1% Letter Spacing, 1.1x line height
- **Body text:** Manrope Regular, 16 pt, 1% Letter Spacing, 1.1x line height
- **Caption text:** Manrope Extra Light, 14 pt, 2 % Letter Spacing. 1.1x line height

> Typography decisions

> In my first low-fidelity draft of my wireframes, I used different variations of Montserrat for the placeholder text. However, I found the width of individual characters on Montserrat to be too large, making it difficult to fit larger amounts of text on smaller screens/visual assets. I then tested three variations of typography: Poppins, Assitant, and Manrope. I immediately gravitated towards Poppins and Manrope, mainly because I found Assistant to appear too condensed and narrow. This limits visibility on smaller screens, so I moved away from Assistant early on in my selection process. 
> 
> Visually, Poppins and Manrope are quite similar to each other (and both of them similar to Monsterrat). They do however vary more distinctly in punctuation and numerical symbols. I found Poppins to be too round in these aspects (e.g. the period in Poppins is a circle, whereas Manrope uses a rectangle) in that it seemed to exude a softness that does not feel in line with a government-operated platform. Thus, I ended up choosing Manrope. As for sizing, I chose what I felt to be most visible to users given the amount of text and/or visual elements on the screen. I hope to verify this with additional user testing when we iterate on our high-fidelity prototypes. 


### Colour scheme
![03 1 1 Colour Var 1Palette](https://user-images.githubusercontent.com/101301281/200762745-0a6a9336-4296-4a27-95f8-b6c0dc37a5cf.png)

> Colour decisions

> The colour palette I chose takes influence from the current MyLA311 app, which is comprised almost entirely of blue. I decided to add additional shades of blue to add more contrast and visual stimulation in the design. In particular, I found it hard to choose a button colour for the popular resources/services buttons. There are quite a few of these buttons and they make much of the interface without scrolling, so any colour I chose seemed to be too overwhelming. I ended up choosing a near-white shade of grey (#FEFEFE) to use as the base button colour. I also added a drop-shadow to the light mode, and an inner-shadow to the dark mode to indicate the affordance of "press-ability". That is, I wanted to signify that the buttons could be pressed down on, so I used elements that added dimension to the buttons (borrowing on design factors from skeuomorphism).

### Layout
- 10 rows, 4 columns 
- Margin: 30 
- Gutter: 20 
- Colour & Opacity: Red (#FF0000) at 10% opacity

> Layout decisions
> 
> I am generally utilizing the layout for column, margin, and gutter guidance. The rows are also in place for guidance, but I am also utilizing Figma's tools for snapping to matching dimensions (e.g. indicating when multiple elements are X pixels apart), as some of my design utilizes more asymmetrical design in the vertical direction, so exact divisions set by rows may not align perfectly with my design assets. I chose this particular layout (10 rows, 4 columns) because I felt the amount of information (i.e. buttons and interactable elements) will vary per page, so I wanted a number of rows that would be easily divisible regardless of the exact quantities of information per screen. As seen above, I also considered utilizing a grid layout/guide, but I felt it to be too distracting because of all the boxes, and also because it's difficult to visualize the gutters (rather, I would have to recall the number of grid spaces that objects should be apart).

