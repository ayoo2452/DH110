![00 - Cover](https://user-images.githubusercontent.com/101301281/204706492-ff08d262-b2f7-414e-bb2f-c69febc3f03f.png)

### by Alex Yoo | Fall 2022, DH 110
# myLA311: Unsolicited Mobile Redesign


## <a name="intro">🔹Introduction</a>
Just as sustainable communities depend on proper environmental regulation, the daily circumstances of citizens are equally relevant and should be thoroughly accounted for and supported by their respective local governments. In a sprawling, densely populated city like Los Angeles, a need for organized support and communication with the local government is extremely **prevalent**.  As such, my project this quarter is an unsolicited mobile redesign of MyLA311, a mobile app created by the City of Los Angeles as a means to facilitate city service request submissions. This app targets users based in Los Angeles, as the city services that users may request only range over the Los Angeles area. My redesign also draws information from the website 211LA.org, which provides information on economic, domestic, and/or personal resources available to Los Angeles citizens. As a whole, this project reflects the UN's Sustainable Community and Cities goal (SDG #11) as it will serve as a uniting resource to help LA citizens better make use of available resources, including but not limited to city services, public transit, and volunteer organizations.  

## <a name="designStatement">🔹Design Statement</a>

Los Angeles is infamous for its high cost of living and is notoriously difficult to navigate without a car, but this city also has underutilized facilities and resources. This project aims to create a centralized hub of information for Los Angeles residents, allowing easy access to city-provided resources like public transit and city services. Furthermore, this redesign intends to raise awareness **for support systems and/or organizations for various concerns.

Having streamlined communication and easy access to resources is incredibly important to foster a sustainable community. Thus, it is important to resolve this issue through my project— a mobile redesign— because such a product utilizes modern advances in technology and communication to improve the quality of life for Los Angeles citizens. 

> *Note that this project limits itself to Los Angeles-specific issues due to our highly dense population and the specialized issues and/or solutions that can arise from our unique location and culture.*
> 

## 🔹Competitor Analysis [A1, A2]

### ************************************************Severity score rating scheme************************************************

1 = Little to no issues, no pressing pain points that prevent user from using the app

2 = Minor issues of low priority to fix but occasionally noticeable throughout user journey

3 = Major issues, high priority to fix, majorly affects user flow/journey

### ****************************************************************Heuristic evaluation #1: MyLA311****************************************************************

| # | Heuristic | Severity Score |
| --- | --- | --- |
| 1 | Visibility of system status | 3 |
| 2 | Match Between System and the Real World | 1 |
| 3 | User Control and Freedom | 2 |
| 4 | Consistency and Standards | 2 |
| 5 | Error Prevention | 3 |
| 6 | Recognition Rather Than Recall | 1 |
| 7 | Flexibility and Efficiency of Use | 3 |
| 8 | Aesthetic and Minimalist Design | 2 |
| 9 | Help Users Recognize, Diagnose, and Recover From Errors | 3 |
| 10 | Help and Documentation | 3 |

**********************Major pain points in design:**********************

- Error prevention:
    - The “Create Service Request” userflow does not prompt users to verify input locations and/or addresses. Users are able to enter arbitrary entries to the address input section. 
    - Users are not given a confirmation/review page prior to submitting their request. As such, users may not see their problem resolved due to a mistaken input, developers may have to account for more ways to filter erroneous/mistyped inputs, and local authorities may waste resources on looking into incorrectly cited reports.
- Flexibility and efficiency of use:
    - The “City Service Directory” feature has extremely poor organization. This feature is composed of an extensive list of services that are in no apparent order— they aren’t sorted alphabetically, nor by sector, and there are no relevant dates attached to the service titles that might hint at how services are being organized. 
    - No way to filter the services. Users looking to browse through a specific category of services (say, housing assistance) would have to scroll through the entirety of the list.

### **********************************************************Heuristic evaluation #2: 211LA.org**********************************************************

| # | Heuristic | Severity Score |
| --- | --- | --- |
| 1 | Visibility of system status | 1 |
| 2 | Match Between System and the Real World | 1 |
| 3 | User Control and Freedom | 1.5 |
| 4 | Consistency and Standards | 1 |
| 5 | Error Prevention | 1 |
| 6 | Recognition Rather Than Recall | 1 |
| 7 | Flexibility and Efficiency of Use | 2 |
| 8 | Aesthetic and Minimalist Design | 1.5 |
| 9 | Help Users Recognize, Diagnose, and Recover From Errors | 1.5 |
| 10 | Help and Documentation | 1.5 |

**********************Major pain points in design:**********************

- Flexibility and efficiency of use
    - The site could benefit from providing time/availability as an additional filter when browsing resources and/or events. For instance, allowing users to filter results to only include services available at certain hours of the day (ex. working parents who need to narrow down the resources based on when they are available).
    
> :mega: View the full documentation on heuristic evaluations [here]()

### Usability Testing - Pilot

The usability testing was guided largely by the resources supplied by Professor Cho. Most questions use the template questions provided in class, with specifications made to tailor the form to my specific app (MyLA311). The participant responded to all survey questions via Google Forms, and entered their information using the provided laptop computer. In addition to the online survey, the participant was asked to complete a few tasks in the existing MyLA311 app. Throughout the three tasks, I asked the participant to articulate aloud some of their thoughts to better understand their process and justifications for their navigation. Both these tasks and the rest of the questions in the survey served to measure the user's ease of use.

> :mega: View the full documentation on pilot usability testing [here]()


> *********************Note: Only UCLA email addresses will be able to access the file.*********************
> 

## 🔹 User Research [A3]

### Interesting insights

- Participants A and B were both extremely reliant upon and trusting of their GPS software, and use it regularly even for short/roughly familiar drives. However, neither wants to have to look up directions to bus. Follow up questions I'd like to look further into:
    - What is too much information to handle for navigation? Both driving with GPS and looking up routes involve following directions from the GPS, but what discriminates one from the other?
- Participant A had limited knowledge and interest in learning about City of LA services
    
    > "I mean, I know that I can look online, and like a lot of the information is there. But I just don't have stuff like off the top of my head. And I'm usually just too lazy to look online, in general, because it doesn't really impact me unless I really need it." - Participant A
    > 
- Participant B doesn't take the bus to new places or unfamiliar areas, and usually only takes the bus on routes they've been before. Indicates a circular issue.
    
    > Question: "So are you more comfortable with busing to places that you've been prior to? Like just bussing to places that you're more familiar with?"
    > 
    
    > Participant B: "I would say so, yeah. If I had to look up how to take a bus—to like somewhere new— I would probably just end up driving."
    > 
    
    
    
> :mega: View the full documentation on user research [here]()

## 🔹 UX Storytelling [A4]

## Persona 1: Taylor Whitestead (Images: [Google Drive Ver.](https://drive.google.com/drive/folders/1SAU-YB3vyxjTszdIJb_A6HcP_nkYHt7f?usp=sharing))

### Persona + Empathy Map

![https://user-images.githubusercontent.com/101301281/197952730-7600188b-e826-4be5-8cea-25bbd9aabeda.png](https://user-images.githubusercontent.com/101301281/197952730-7600188b-e826-4be5-8cea-25bbd9aabeda.png)

### Journey Map

![https://user-images.githubusercontent.com/101301281/197952783-30f8514f-6159-4a53-a6fd-4e2477860bc2.png](https://user-images.githubusercontent.com/101301281/197952783-30f8514f-6159-4a53-a6fd-4e2477860bc2.png)

## Persona 2: Kimia Lee (Images: [Google Drive Ver.](https://drive.google.com/drive/folders/1SAU-YB3vyxjTszdIJb_A6HcP_nkYHt7f?usp=sharing))

### Persona + Empathy Map

![https://user-images.githubusercontent.com/101301281/197952825-96e02d20-d945-4c08-9ba6-ee9e15168255.png](https://user-images.githubusercontent.com/101301281/197952825-96e02d20-d945-4c08-9ba6-ee9e15168255.png)

### Journey Map

![https://user-images.githubusercontent.com/101301281/197952892-4cd54a3d-f443-4b87-8875-1b7e53f0a2f8.png](https://user-images.githubusercontent.com/101301281/197952892-4cd54a3d-f443-4b87-8875-1b7e53f0a2f8.png)

> :mega: View the full documentation on UX Storytelling [here]()

## 🔹 Low-fidelity Prototype

Upon imagining realistic usage scenarios for both users (information on which can be found in [Assignment 4: Personas and Scenarios](https://github.com/ayoo2452/DH110/tree/main/Assignment%204)), I identified three features of interest for the redesign of MyLA311:

1. A route-finder with information specific and tailored to LA Public Transit (not just the Metro, but including other public transport services that serve the greater Los Angeles County area). This navigation should ease cognitive load, and provide enough information on the different lines/systems so that first time users understand their options sufficiently.
2. A cohesive, easily browse-able directory of resources available to the community. This should support efficient and relevant filtering, as well as ways to easily compile and/or save resources of high interest to the user.
3. Re-organize and address error verification issues with the Submit a Request function on MyLA311 app. (This particular features stems from my heuristic evaluation of MyLA311's app, and— more recently-- a deeper evaluation at MyLA311's website).

### Lo-Fi Wireframes
![22F DH 110- Wireframes only](https://user-images.githubusercontent.com/101301281/204714684-a4e8382b-52b0-4b2d-ac1e-4462dadec020.png)
### Lo-Fi Wireflow
![A05 Wireflow](https://user-images.githubusercontent.com/101301281/204715082-f10fccc0-e8e4-4b02-baf7-27021c210b1d.jpeg)


### Main areas to improve the prototype

1. **Changing the "Continue as guest" to say "Continue without logging in" instead.** 
2. **Adding more signifiers and significantly more detail to the navigation portion of the app.** 
3. **Enhancing the filter and sort-by functions for all three portions (Navigation, Services, Resources)**

> :mega: View the full documentation on the low-fidelity prototype [here]()

## 🔹 Wireframes & Design System [A6]

###  Hi-Fidelity Wireframe: Design System sample

![https://user-images.githubusercontent.com/101301281/200758434-c0403c4c-8e3a-4783-8322-0dd1faeef672.png](https://user-images.githubusercontent.com/101301281/200758434-c0403c4c-8e3a-4783-8322-0dd1faeef672.png)

## 🔹 Design System + Summary

### Typography

![01 0 Text Variation- Chosen](https://user-images.githubusercontent.com/101301281/204715908-287c6852-369a-4068-9b30-a3971e7ad669.png)

- **Title:** Manrope Extra Bold, 34 pt, 1% Letter Spacing, 1.1x line height
- **Subtitle:** Manrope Medium , 21 pt, 1% Letter Spacing, 1.1x line height
- **Body text:** Manrope Regular, 16 pt, 1% Letter Spacing, 1.1x line height
- **Caption text:** Manrope Extra Light, 14 pt, 2 % Letter Spacing. 1.1x line height

### Colour scheme

![https://user-images.githubusercontent.com/101301281/200777473-43c04558-aab8-42a5-95cb-cb126203b319.png](https://user-images.githubusercontent.com/101301281/200777473-43c04558-aab8-42a5-95cb-cb126203b319.png)

> Colour decisions

> The colour palette I chose takes influence from the current MyLA311 app, which is comprised almost entirely of blue. I decided to add additional shades of blue to add more contrast and visual stimulation in the design. In particular, I found it hard to choose a button colour for the popular resources/services buttons. There are quite a few of these buttons and they make much of the interface without scrolling, so any colour I chose seemed to be too overwhelming. I ended up choosing a near-white shade of grey (#FEFEFE) to use as the base button colour. I also added a drop-shadow to the light mode, and an inner-shadow to the dark mode to indicate the affordance of "press-ability". That is, I wanted to signify that the buttons could be pressed down on, so I used elements that added dimension to the buttons (borrowing on design factors from skeuomorphism).
> 

### Colour Accessibility check

> NOTE: The image quality is appearing lower for some devices. View the Figma file [here](https://www.figma.com/file/hCWuj8WsEqumdAJYi72R7P/22F-DH-110-(Copy)?node-id=138%3A1166&t=F9FfE6Q01Dr0Lsnx-0) for better quality.
> 

![https://user-images.githubusercontent.com/101301281/200748806-5d1e772b-c9be-4c95-876c-2344adfd7a73.png](https://user-images.githubusercontent.com/101301281/200748806-5d1e772b-c9be-4c95-876c-2344adfd7a73.png)

![https://user-images.githubusercontent.com/101301281/200748811-6a91e12f-61bf-44a5-ae28-abd23a9a7b0f.png](https://user-images.githubusercontent.com/101301281/200748811-6a91e12f-61bf-44a5-ae28-abd23a9a7b0f.png)

### Layout

- 10 rows, 4 columns
- Margin: 30
- Gutter: 20
- Colour & Opacity: Red (#FF0000) at 10% opacity

> :mega: View the full documentation on the wireframes and design system [here]()

## 🔹 High-fidelity Prototype

> :mega: View the full documentation on the high-fidelity prototype [here]()

## 🔹 Cognitive Walkthrough + Revisions

******************************************Cognitive Walkthrough: Main takeaways******************************************

1. The current design seems to rely on subtitles and/or written information. This may be a weak point for users who rely more on visual cues to quickly navigate the page. Try to emphasize key features using more contrasting colours and/or sizing.
2. Similarly to point #1: Users utilize layout as a clue on what certain features are capable of and/or what certain visual assets afford.
3. The tracking bar on the “submit a service request” section is really useful. Consider implementing more “tracking” features throughout each sector of the app, and in the earliest stages of a process.
4. Users would benefit from seeing more information on what to expect after submitting a request (E.g. How long till they get a response? Will they get a confirmation email?)
5. The app has a professional, clean feel to it. Reviewer B noted that the app is consistent in aesthetic, colouring, and layout.

## 🔹 Pitch video

> :video_camera: View the pitch video [here]()

## 🔹 Conclusion
