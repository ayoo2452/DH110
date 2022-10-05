## DH110 Fall 2022 | Alex Yoo | Topic: Sustainable Cities and Communities
# Assignment 1: Heuristic Evaluation

**Tentative Project Title: ConnectLA**
**Project Description**
Just as sustainable communities depend on proper environmental regulation, the daily circumstances of citizens are equally relevant and should be thoroughly accounted for and supported by their respective local governments. In line with this effort are My311LA (mobile app) and 211LA.org, both of which serve the greater Los Angeles population by providing information and/or support on local economic, domestic, and navigational resources. My project this quarter is to redesign the My311LA app with easy usability and high accessibility, while also drawing inspiration from 211LA.org site. As a whole, this project reflects the UN's Sustainable Community and Cities goal (SDG #11) as it will serve as a uniting resource to help LA citizens better make use of available resources while highlighting a need for new resources


## **Overview of Nielsen Heuristics ([Nielsen Norman Group](https://www.nngroup.com/articles/ten-usability-heuristics/))**

| Number | Heuristic | Description |
|---|---|---|
| 1 | Visibility of System Status | Users should always be informed about what is going on and should be given appropriate feedback to their actions |
| 2 | Match Between System and the Real World | Use concepts and language that are familiar and logical to the user |
| 3 | User Control and Freedom | Allow users to make mistakes; give them options to undo and redo tasks |
| 4 | Consistency and Standards | Follow conventions and make sure design is consistent across the platform |
| 5 | Error Prevention | Get rid of error-prone conditions and provide users with safety nets for high-cost errors |
| 6 | Recognition Rather Than Recall | Minimize user's memory load by giving them suggestions and help in context |
| 7 | Flexibility and Efficiency of Use | Provide multiple ways to perform a task to make the platform accessible to all users |
| 8 | Aesthetic and Minimalist Design | Provide only relevant content and features |
| 9 | Help Users Recognize, Diagnose, and Recover From Errors | Tell users what the problem is and provide suggestions to fix it |
| 10 | Help and Documentation | Supply users with extra help to complete their tasks |

---

## **Critique 1: MyLA311 (App)**

### About MyLA311

MyLA311, a mobile app produced by the Los Angeles City Hall, is a _____.

### 311LA Heuristic Evaluation- Overview

| # | Heuristic | Severity Score | 
| --- | --- | --- | 
| [1](#1.1) | Visibility of system status | 3 | 
| [2](#1.2)| Match Between System and the Real World | 1 |
| [3](#1.3) | User Control and Freedom| 2 | 
| [4](#1.4) | Consistency and Standards | 2 |
| [5](#1.5) | Error Prevention | 3 | 
| [6](#1.6) | Recognition Rather Than Recall | 1 |
| [7](#1.7) | Flexibility and Efficiency of Use | 3 | 
| [8](#1.8) | Aesthetic and Minimalist Design | 2 | 
| [9](#1.9) | Help Users Recognize, Diagnose, and Recover From Errors | 3 | 
| [10](#1.9) | Help and Documentation | 3 | 

***Note that severity ratings are on a scale of 1 to 3, with the scheme as follows:***  

1 = Little to no issues, no pressing pain points that prevent user from using the app  
2 = Minor issues of low priority to fix but occassionally noticeable throughout user journey  
3 = Major issues, high priority to fix, majorly affects user flow/journey


### 1.1: Visibility of System Status<a id='1.1'></a>
**Severity rating: 3**
- MyLA311 allows users to view the city's available services through a section labeled "City Service Directory", in which the various services that users may interact with are listed, alongside brief explanations of that respective service. While this feature is likely meant as an avenue for users to browse for services, there is little organization and no means to filter the extensive list of services. Additionally, this list does not load in its entirety—instead, users have to scroll up and wait for the page to continue loading before it displays more options. Despite there being seemingly many services on this list, the app does NOT say how many service titles the user has seen, nor how many are left to view. Similarly, there are also not any page numbers to show where the user is in their browsing process. From the perspective of system status visability, this browsing format lacks transparency and is a major user pain point that should take high priority to address.

    *Other critiques on this particular feature (City Service Directory) will also be made as I evaluate Heuristic 7 (flexibility and efficiency of use) [below](#1.7).*

- The most action-driven section (requesting a service) has poor visibility throughout. As a trial, I tested the process for submitting a complaint via the "Create a service request" feature on the home page, and was met with an unpleasantly surprising user flow. The most concerning issue (relevant to this heuristic) is that once a user has entered their personal information and the details of their request, there is no confirmation page *prior* to submitting the request. This app does not give users a chance to review their service request before submitting, so users do not have an opportunity to audit their own inputs before submission. Not only does this result in an unpleasant shock factor for the user (I personally had no intention of actually submitting a request, but my supposedly trial request went through before I knew it), but also increases the likelihood of human error in input. Sorting real and/or accurate requests from accidental or erred messages is an additional tax on the backend of things for this app, and a better design here would help mitigate such unnecessary expenditure of effort.

### **1.2: Match Between System and the Real World**<a id='1.2'></a>

**Severity rating: 1**

- MyLA311 does a relatively sound job of using familiar phrases and terminology. Service request options are usually titled with descriptive, clear language such that most users would be able to understand what that request means. Additionally, the service requests are segmented in categories that are common and intuitive. For example, services like “barricade removal”, “curb repair”, “flooding”, and “land/mud slide” are all categorized under “Street Problems/Repairs”
- The most pressing critique under this heuristic is that the option “City Info” (found upon expanding the hamburger menu) is accompanied by an icon comprised of what looks like a chat box, but that icon actually leads users to a city map.
    - *Recommendation: Replace the term “City Info” with “City Map”, and exchange the chat box icon for a navigation pin*

### **1.3: User Control and Freedom**<a id='1.3'></a>

**Severity rating: 2**

- Aside from the “Create Service Request” module, all the other features on MyLA311 do not have a back arrow that allows users to return to the menu/homepage. Rather, users have to click on the “MyLA311” icon on the top left corner of the screen, or open the hamburger menu to click the home icon.
- Users who are navigating through the “Create Service Request” do have the option to cancel their service request on the initial complaint page, but— as highlighted in my above evaluation of Heuristic #1— users are not given the option to review (or cancel) their input after hitting the submit button.

### **1.4: Consistency and Standards**<a id='1.4'></a>

**Severity rating: 2**

- A minor inconsistency that appears is the “City Info” feature mentioned above in [Heuristic 2](#1.2): the “City Info” icon appears to look like a chat box— possibly indicating the presence of an FAQ or even chat bot page— but links to a map. This representation may confuse certain users, as map data is typically iconized with a location pin or icons of similar association.
- Additionally, the “Create Service Request” form requires users to fill out their residence address. The format of inputting one’s address is a bit unconventional in that users have to input the number of their home separate from their street. Furthermore, the form provides two dropdown menus for unfamiliar options: “Direction” and “Suffix”, which ask for the user’s cardinal directions and street suffix (e.g. “Blvd”, “Ave”, etc).
    - For example, if my address was “32 Peppermint Blvd”, I would have to input “32” in one box, then “Peppermint” in another, and then find “Blvd” in the Suffix box. As for the “Direction” option, this is not required, but may be confusing to users who aren’t used to specifying which cardinal direction their residence is.

### **1.5: Error Prevention**<a id='1.5'></a>

**Severity rating: 3**

- Most of MyLA311’s poor design comes from their lack of error prevention throughout the “Create Service Request” user flow. To begin, I randomly chose a service to “request” (Dog Defecation, under the Animal Complaints/Violations section). Upon navigating to the Service Request Details page, I found that I had to input my residence address in. Many online retailers or forms that require you to input an address typically verify your address— that is, they make sure that you’ve entered a real address. However, MyLA311 does not have such a feature, so users are responsible for validating their own address (typos are also not accounted for).
- *As you can see below, entering an arbitrary address is considered a valid input by the app’s system*
- Another area of concern is the Contact Info section of submitting a request. Though the initial page annotates what information belongs where (ex. “Email” is written in the first box), these annotations go away once users start typing in those boxes. If a user didn’t read these annotations and just started randomly inputting information (say, wrote the first name in the top box, last name in the second, and their email in the third), the system would error, but the user would have to erase at least one of their inputs to verify what box is for what information.
- And as mentioned previously in [Heuristic 1](#1.1), users are not given a confirmation/review page prior to submitting their request. Removing the ability to review the requests can be detrimental to users, developers, and those who have to follow up on all the requested services. Users may not see their problem resolved due to a mistaken input, developers may have to account for more ways to filter erroneous/mistyped inputs, and local authorities may waste resources on looking into incorrectly cited reports.

### **1.6: Recognition Rather Than Recall**<a id='1.6'></a>

**Severity rating: 1**

- MyLA311 typically makes use of icons and visual representations where it can, promoting recognition. However, it could improve further by offering categories that users can use to search for services. As it stands now, the search bar prompts uses to search by entering keywords, rather than selecting keywords— making this difficult for first-time users who just want to browse, or other users who can’t quite recall what kinds of services MyLA311 even offers.

### **1.7: Flexibility and Efficiency of Use**<a id='1.7'></a>

**Severity rating: 3**

- A major flaw in this app lies in its poor browse-ability. Specifically, the “City Service Directory” has extremely poor organization. When navigating to this directory, users are met with an extensive list of services that are in no apparent order— they aren’t sorted alphabetically, nor by sector, and there are no relevant dates attached to the service titles that might hint at how services are being organized. Additionally, there is no way to filter the services. Users looking to browse through a specific category of services (say, housing assistance) would have to scroll through the entirety of the list.
- Another potential issue lies in the process of changing the interface language. Users can change the language of their app, but the name of that language is written in the app’s current language. For example, in my English interface, my language options are “English, Español, Simplified Chinese, Traditional Chinese, Korean, Armenian”. Imagine a user who doesn’t speak or read any English, but wants to change their language to Simplified Chinese. In this case, it may be difficult for them to do so if they cannot read “Simplified Chinese”, as it’s written in English. A more accessible design would include English *and* the respective language (ex. writing “Korean/한국어”).
    - It does appears that the app has already done so for Spanish, by writing Español— this should be extended to the other languages
    - Additionally, a more flexible design would include many more languages than just the 6 options here, especially given Los Angeles’s diversity.

### **1.8: Aesthetic and Minimalist Design**<a id='1.8'></a>

**Severity rating: 2**

- The app makes use of a largely blue color palette, thereby contributing to a somewhat monotonous overall impression.
- Additionally, the app’s visual assets are lacking in terms of quality and layout— certain icons (such as the home icon in the hamburger menu and the search icon/magnifier in the City Service Directory) are grainy in appearance.
- In general, the app has a minimal design that makes a dull impression on the user and could make better use of information hierarchy, especially in their already overwhelming City Service Directory.

### **1.9: Help Users Recognize, Diagnose, and Recover From Errors**<a id='1.9'></a>

**Severity rating: 3**

- There is little error recovery feedback from users, and there are no pages that offer an FAQ or quick links to assistance. This is particularly disappointing in the Create Service Request user flow, as there is limited information on what exactly each service does or to what extent information should be provided, so users are more prone to making errors.

### **1.10: Help and Documentation**<a id='1.10'></a>

**Severity rating: 3**

- As in my evaluation above for [Heuristic 9](#1.9), there appears to be no help pages or FAQ sections that users can look to. There is a Customer Service button on the app homepage, but this only directs users to a phone number.

---

## Critique 2: 211la.org (Website)

*Table 2: 211LA.org Heuristic Evaluation*

| # | Heuristic | Severity Score | 
| ----------- | ----------- | --- | 
| [1](#2.1) | Visibility of system status | score | 
| [2](#2.2)| Match Between System and the Real World | score |
| [3](#2.3) | User Control and Freedom| score | 
| [4](#2.4) | Consistency and Standards | score |
| [5](#2.5) | Error Prevention | score | 
| [6](#2.6) | Recognition Rather Than Recall | score |
| [7](#2.7) | Flexibility and Efficiency of Use | score | 
| [8](#2.8) | Aesthetic and Minimalist Design | score | 
| [9](#2.9) | Help Users Recognize, Diagnose, and Recover From Errors | score | 
| [10](#2.9) | Help and Documentation | score | 

### 2.1: Visibility of System Status<a id='2.1'></a>

**Severity rating: 1**

- Site allows users to easily navigate back and forth between pages, modules, and features.
- While there are not many “fancy” features that really heighten the visibility of the system status (that is, the users’ current place/progress on the site), this is largely accounted for by the fact that this site is mainly a large database for LA residents to see and gain access to supporting resources nearby. Rather than using this site to accomplish a task (e.g. scheduling an appointment), [211LA.org](http://211LA.org) serves more as a search engine. As such there’s less to criticize on the system status and its transparency to users throughout their navigational flow.

### 2.2: Match Between System and the Real World<a id='2.2'></a>

**Severity rating: 1**

- Website uses descriptive titles in their resource lists, and does not use unnecessary jargon. They also avoid using acronyms so that users can get a clear idea of what a given organization is offering and/or what service is being provided.
- The site also makes great use of map-views that users can access when scanning through results on certain resources. This makes it easy for users to understand what resources are available to them nearby, and provides a sense of familiarity with the area that they might be able to receive assistance.

### 2.3: User Control and Freedom<a id='2.3'></a>

**Severity rating: 1.5**

- “Return to results” button available upon clicking on a resource page.
- Navigation is also relatively clear and accessible, but may cause users frustration as it is not a “sticky menu”— one has to scroll all the way to the top of the site in order to access the menu, should they want to navigate away from their current page.

### 2.4: Consistency and Standards<a id='2.4'></a>

**Severity rating: 1**

- The site does a good job of sticking to basic terminology and for providing a mundane but straightforward user flow.
- Navigation is predictable and has little to no areas of concern/room for misinterpretation.
- There does appear to be more visuals when searching by “events” rather than “resources”. While this may help distinguish the two search categories, it also may appear confusing to new users who aren’t used to seeing the many icons used in the “events” search log/results.

### 2.5: Error Prevention<a id='2.5'></a>

**Severity rating: 1**

- Unlike the other interface I critiqued in this assignment, there are minimal actions that users can take when navigating the [211LA.org](http://211LA.org) website. Again, this is largely because the users do not have information to input, as 211LA.org is mainly a database meant to be searched within, rather than manipulated or added to.
- With this in mind, there are not really many areas where this site needs to improve in terms of error prevention. Given the relatively clear layout of the navigation bar and the ability to go back and forth between objects, there is sufficient design in place to guide users in the case of accidentally shifting between pages.

### 2.6: Recognition Rather Than Recall<a id='2.6'></a>
**Severity rating:**


### 2.7: Flexibility and Efficiency of Use<a id='2.7'></a>
**Severity rating:**


### 2.8: Aesthetic and Minimalist Design<a id='2.8'></a>
**Severity rating:**


### 2.9: Help Users Recognize, Diagnose, and Recover From Errors<a id='2.9'></a>
**Severity rating:**


### 2.10: Help and Documentation<a id='2.10'></a>
**Severity rating:**





