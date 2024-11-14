## DES222: Assessment 2
#### Aaron Troughton, 1167270 ####
# Journal Title: ‘Location Based Diary’ #

![Image](Images/sketch.png)

## Index: ##
**1. CONCEPTUALISATION**

1.1	Task and Journal Statements

1.2	Determining Design Purpose

1.3	Research and Evaluation of Existing Solutions

1.4	Early Concepts

1.5	Development of Selected Concept

**2. Front End Programming**

2.1 Home Page Layout

2.2 Designing the Journaling User Interface

**3. Backend support with Flask**

3.1 Using HTTP Requests

3.2 Displaying trips

3.3 Viewing Individual Entries

3.4 Last Refinements

**4 Delivery and Reflection**

4.1 Hosting

4.2 Future Improvements

4.3 Demonstration

***
# 1. Conceptualisation # 

02/10/2024
## 1.1 Task and Journal Statements ##
<ins> Predetermined Goal:</ins> Create a context aware web application to enhance user experience through responsiveness and innovation 

The task prescribed is to design and develop a responsive project. The following journal will display how ideas and concepts evolve from the predetermined goal and through evaluation of existing projects contribute to the creation of the final design.

***
## 1.2 Determining Design Purpose ##
As the project is aimed to enhance user experience through a context-aware application it is evident that the Design Council’s Double Diamond methodology will be used to ensure human centred design factors are addressed throughout the tasks design development.
![Image](Images/Double_Diamond.png)

Design Council. (n.d.). Framework for innovation. https://www.designcouncil.org.uk/our-resources/framework-for-innovation/

In 2024 there has been a growing movement of digital detox through applications like BeReal with a focus on showing the world unfiltered, switching to 'dumb phones', eliminating distractions, and connecting back to nature. Although it may seem contradictory at first, this concept will be core to the development of this project by prioritising simplicity and disconnection.

#### <em> “Travel far enough, you meet yourself" - David Mitchell, Cloud Atlas (2004) ####

<strong> Rationale </strong> - The goal and expected outcome for this project's application to achieve by the end of the design process would be to support a healthier relationship with technology in everyday life by embracing digital wellbeing, promoting mindfulness, as well as presenting moment awareness through the simplicity of an adaptive journal to store meaningful experiences. 

A concept proposal posted of Padlet was created from this rationale as well as a picture collage to brainstorm the aesthetic and functionality of the application.

![Image](Images/Padlet.png)

![Image](Images/collage.png)

***
## 1.3 Research and Evaluation of Existing Solutions ##

03/10/2024

With the rationale and core concepts defined prior in section 1.2 of this journal, it sets up criteria to evaluate existing solutions to identify strengths and weaknesses through SWAT analysis to contribute to the development of this project. The collage above visualises the brainstorming process powering the projects idea by merging certain features and functionality from various applications such as timeline tracking, and adding interactive media with the goal of creating a digital journal to authentically preserve how someone felt about a certain day or journey. The collage incorporating varying solutions offers a mixture of different means of usage, target audiences, and functionality which highlights why the SCAMPER ideology will be effective when utilising these numerous existing applications and other relevant hardware examples.

### Existing Solution 1: Google Timelines ###

![Image](Images/timelines.png)

05/10/2024

Google Timelines is a feature within the Google Maps mobile app and tracks the day of the user, provides insights into monthly travel patterns and exercise, as well as letting you view and edit travel history. Integration with Google Photos also allows users to view a detailed timeline of a day with reference to photos and notes from that day and location of origin, allowing for a detailed and time based journal entries. Some additional background information is that as a hobbyist photographer and outdoors traveler I had used Google Timelines for a couple of years for the reasons stated earlier in the design purpose and my experience from a user perspective of Google Timelines and some of the other solutions is a major part of why this project is being constructed and this experience will be used to find what features can be used as inspiration and what to avoid in the final proposal through SWOT analysis to ensure that user wants and needs are addressed effectively.

<strong> Strengths ✅ </strong>- Google Maps is a free service only requiring a Google account. Great accuracy for road trips with GPS tracking and easily integrates with other Google services such as Google Photos. Application offers wide range of functionality.

<strong> Weaknesses ❌ </strong>- Google recently rolled out an update which ended support for Google Timelines online and now only stores information locally for security concerns. This change eliminated cross functionality across devices and made recorded statistics and travel journeys inaccurate. Another weakness here in response to the tasks design purpose is that this apps features are not dedicated towards the intended audience which this task is aiming for which creates an opportunity to design an app with this focus.

<strong> Opportunities 🧭 </strong>- Google does offer the API of their mapping services for third party use. A timeline like recording where a day entry for a journal is sorted by hour or in order can create a detailed journal entry and offer interactiveness to the user when expanded on. This project can offer grouped insights as seen in the image above to display a summary of activities recorded in the journal.

<strong> Threats ⚠️ </strong>- An inherent threat which would be consistent among all these solutions is recording of sensitive data regarding the users location and daily activities which must be protected when sent and stored. An option for local storage only could be provided to users.

***
### Existing Solution 2: Strava ###

![Image](Images/strava.png)

<strong> Strengths ✅ </strong>- Strava is the premier app when it comes to recording and tracking any outdoor based activity whether it be biking, walking, kayaking, swimming, skiing, it records all data and offers the millions of users insights into their performance and hobby activities. Satellite geolocation tracking to work even in the most remote places. Is available on all platforms and syncs across devices. Generates routes and activities for you. Works with many popular accessories and health apps. Customisable map interface using Mapbox API. Free app to install and use with premium plans available. Can join clubs and compete in challenges.

<strong> Weaknesses ❌ </strong>- Only in the context of this task is it a weakness but Strava acts as more of a social media platform where you share your trips with others and can compare performances and times with one another. In this projects use case of a private journal for self reflection, the concept of this apps functionalities will be utilised but with an app centred around single user without the social aspect which leads to the opportunities.

<strong> Opportunities 🧭 </strong>- In comparison to the Google Maps API from the prior example, the Mapbox API is much more accessible while offering a wide range of map customisation on a free plan with a 50,000 request limits which will work for this task. Incorporating a feature to link images to a certain time and location period to achieve the goal of being context aware and responsive.

<strong> Threats ⚠️ </strong>- Account security. If the project is aimed to work across devices, data must be managed securely and appropriately.

***
### Existing Solution 3: Apple Journals ###

![Image](Images/appjournal.jpg)

<strong> Strengths ✅ </strong>- Apple launched their official journal app December 2023. It is simplistic, clutter free and easily understandable offering the fundamental features such as date, text, photos, point location, voice over and music. This closely aligns with the concept of a scrapbook from the collage earlier. Saved entries are protected and made to be private to create an environment best for self-reflection.

<strong> Weaknesses ❌ </strong>- Main weakness is that this is limited to users in Apple's ecosystem only which is limiting the reach of the application. The goal of this task to create a journal application to record your movement throughout the day which would require functionality from the previous two examples to be added with the concept of a journal seen here. This will be explored more in the DEFINE stage of the double diamond and later in SCAMPER.

<strong> Opportunities 🧭 </strong>- Incorporating the feature to sort and filter entries as seen in Apple Journals will add interactiveness and reduce clutter in the proposed project. Daily notifications to enter in the journal could be an option provided but by default would need to be disabled to adhere to the task's theme of disconnection.

<strong> Threats ⚠️ </strong>- Unlike the other solutions, this application is highly secure making the only real risk of backing up data to prevent data loss.

***
### Existing Solution 4: Project Life ###

![Image](Images/projectlife.png)

<strong> Strengths ✅ </strong>- Project Life is a completely free app from Becky Higgins made to create digital scrapbooks easily and is used as a teaching tool in primary school education. Offers an easy to use tool to journal in the form of visual imagery. App is intended to easily export digital scrapbooks and journals in a physical format, creating an engaging experience for the users.

<strong> Weaknesses ❌ </strong>- Cannot save work to come back to later and does not offer much flexibility when it comes to what is able to be inserted into the scrapbook or journal. Offers a tool rather than an experience which in the case of this project does not satisfy the task goal. What is normally basic functionality such as font selection are blocked by a pay barrier.

<strong> Opportunities 🧭 </strong>- The option to offer various different formats for pages is an interesting concept to explore. This allows for some individuality between entries and can have different pages formatted in a way which best reflects the user's day.

<strong> Threats ⚠️ </strong>- As listed in the weaknesses, not being able to save progress makes losing work a high risk.

***
### Existing Solution 5: Hiker's Logbook ###

![Image](Images/logbook.png)

User discussion [HERE](https://www.reddit.com/r/Ultralight/comments/118cmky/hikers_logbook_an_ultralight_journal_app/) displays the target audience and the intended use case of the task's responsive application. 

<em> "I wanted to keep a daily journal of my mileage, major events of the day, and where I slept just to create some anchors to allow me to remember the day in the future."</em>

<strong> Strengths ✅ </strong>- This app was independently made by a hobbyist Aaron Byers non for profit to allow for an extremely light weight and easy to understand application which offers all statistics regarding hiking trips while offering the ability to take notes and journal each trip to look back on. This example is the closest at achieving the concept of journaling trips through location which is sought after in this task. Works offline without functionality loss. No account needed and is completely free to use.

<strong> Weaknesses ❌ </strong>- Is only available on iPhone devices which limits accessibility. This app is intended for hiking only but this must be expanded in the app being designed to support a wide range of hobbies. Uses manual input coordinates which is good for completely offline usage but a map API like Mapbox will need to be used in the tasks revisions.

<strong> Opportunities 🧭 </strong>- The minimalistic design and list display will be the ideal direction the UI will take. This will be explored further in low fidelity diagrams and in Figma prototypes further on in the journal. Each journal entry can have two sides like seen here, one with the trip data, mapping information, and photos with the other side of the entry being the reflection.

<strong> Threats ⚠️ </strong>- Is a individually made app and is not regularly supported.

***
### Existing Solution 6: Remerkable Paper Pro ###

![Image](Images/remarkable.gif)

<strong> Strengths ✅ </strong>- Digitises the paper journaling experience without loosing the authentic feel of writing on paper. The lightweight, colourful, E Ink tablet with local encryption and cross platform capability allows for a quality built smart device to journal notes in but without the distractions of everyday smartphones. Paper like feel is achieved through a textured surface to enhance the journaling experience on the go. Is designed solely for writing which allows for an unmatched journaling experience. A pen to write along with shapes and unlimited media support allows for endless customisation in journal entries.

<strong> Weaknesses ❌ </strong>- High price barrier unlike the previous existing solutions. Ability to back up documents is another seperate subscription. Fragile device would not be ideal for the rougher, outdoor activities which this tasks intends to journal.

<strong> Opportunities 🧭 </strong>- The other solutions looks at a service/application approach to the task goal but this offers a look into how hardware can be utilised for the same goal. As determined early in this tasks' journal, context aware software such as strava and timelines would most likely be the approach taken, but dedicated hardware to expand of the softwares impact towards the task rationale can be designed in future advancements of this idea.

<strong> Threats ⚠️ </strong>- Fragile and slim form factor makes the device easy to damage and misplace.

Another relevant concept is nature journaling as seen in this video

[https://www.youtube.com/watch?v=o3pEY-qTBc8&ab_channel=Liberty%27sLibrary](https://www.youtube.com/watch?v=o3pEY-qTBc8&ab_channel=Liberty%27sLibrary)

The goal of this task is to provide the ability to journal a wide range different input such as plain text, images, and geolocation to allow for the user to create a journal in a way which allows them to best reflect what is being journaled and support any emotion and meaning behind the text. These 6 existing services and products explored displayed functions from differing apps with unique use cases and as identified, this task is aiming to utilise some of the core functionality seen across these examples to build an app which satisfies the task goal of connecting with the outdoors, traveling, and self reflection through an engaging and customisable journal application while employing geolocation API's to be accurately context-aware. Inspiration to achieve this goal can be visualised further in the Venn diagram below

![Image](Images/venn.png)

***
## 1.4	Early Concepts ##
06/10/2024

Reviewing and evaluating existing solutions allowed for the task to define what is expected to be seen in the early concepts and final development. To further advance in the define stage of the double diamond and more towards to development of the application, three revisions and application diagrams will be produced to see how effective the proposed solutions are at achieving the task goal.

### Realisation 1: Trek - A Journey Tracker Journal Application ###

This application is inspired by the geolocation and time based activity tracking seen in the Google timelines features and Strava app but would be dedicated for journaling and self-reflection. The goal here is to create a digital journal that captures not just thoughts and feelings but also the context of where and when those experiences occurred. This allows users to revisit their memories in a more immersive and meaningful way. This mode would allow users to not only log individual entries but also create continuous, chronological records of their journeys through an interactive map that displays the user's route with markers for each journal entry. The name 'Trek' was chosen as it means to perform a long and sometimes difficult journey which reflects what this app is trying to capture through journal entries.

<strong>Features include</strong>

• The ability to add photos, notes, and even short audio recordings to each point on the timeline.

• Timeline view that allows users to scroll through their journey chronologically, with entries displayed alongside the map.

• Group and filter entries

• View travel history through an engaging and minimalistic interface

• Creation of context awareness through the usage of the MapBoxes API and Media Capture API

<strong>Pros</strong>

Conceptually combines the core functionality from the reviewed existing solutions to achieve the goal seen in the Venn diagram. Displaying daily events paired with an interactive map to show the days events in chronological order allow for a rich and immersive form or journaling unseen in traditional forms. The extensive amount of information available to the user allows for deeper contextualisation by linking location to time to gain an understanding of how their environment and activities can influence their thoughts and feelings.

<strong>Cons</strong>

In contrast to the benefits seen in the lightweight nature of the Hiker's Logbook application, this apps wide range of tracking and functionality may pose a threat of being overly complex and may go against the goal of achieving minimalism, preserving the authentic feel of journaling and spending less time on technology. A lot of consideration must be put on designing the user interface to not overwhelm and stress the user with special focus to human, cultural, and social factors.

#### Trek Home Page GUI ####

![Image](Images/coneptOne.png)

This low fidelity GUI prototype made in Pencil displays what the home screen of the Trek application could envision to adhere to the goal of being minimal.

***
### Realisation 2: Hue - A Mood Tracker using Microbits ###

This potential project direction utilises Micro:bit hardware with an application to capture and visualise the user's mood throughout their daily journey. This could be achieved by using the broad range of Micro:bit's compatible sensors of accelerometers, light sensors, and buttons to detect environmental changes, and manual input such as mood level. This idea branches away from the geolocation concept to focus on how other forms of being context-aware can be incorporated in this task. Acts as an emotional journal with the Micro:bit asking how was the day on the LED screen and results with the user selecting a response e.g., happy, sad, excited. The app communicates with the Micro:bit and allows the user to  journal that day in greater detail and add further context to what the Micro:bit has collected. This application also stores and lets the user revisit previous entries.

<strong>Pros</strong>

Interactive physical product to creating an engaging and simple platform for self reflection. Can make use of a wide range of sensors to add in the moment data to journal entries. Quick and easy action to journal with a press of a button which links back to the goal of disconnection.

<strong>Cons</strong>

Is overly simplified and offers less function in comparison to the other solutions. The form factor of a Micro:bit and loose parts may be an issue to travel with and will need further design put on casing. Hard to journal in detail on the go with the limited input options of a Micro:bit. Relies on battery life. Offers a lot less flexibility than a software based solution such as seen in realisation 1.

#### Microbit Foundation Block Code ####

![Image](Images/microbit.png)

The above Micro:bit block code is a draft of how hardware can be used to journal emotion. The above lets the user select an input ranging from 1-5 on how they are feeling. This displays the core idea behind this realisation and would need to be extended to word with different sensors and implement communication with an application to properly document journal entries in order to achieve the task goal.

***
### Realisation 3: Quests - Making Journaling into a Game ###

This third idea is exploring the engagement aspect sought after in this project. This would be an application which turns journaling into a game by rewarding the user when journaling. This is done through random daily quests which are given to the user such as 'walk 1km' or 'journal for 3 straight days' to unlock achievements. Data collected while journaling can provide useful insights into the user's well-being and lifestyle patterns to generate personalised recommendations for further exploration or self-improvement. This aims to satisfy the task rationale of encouraging users to explore the outdoors to improve wellbeing with the assistance of this application.

<strong>Pros</strong>

Increased engagement and habit formation through daily quests to encourage journaling. Implements motivation and goal setting for long term goals set by either the user or application. App can provide a personalised experience based on user input and user activity. Encourages exploration of outdoors and physical activity through a simple user interface while providing back a sense of accomplishment.

<strong>Cons</strong>

Users may become overly focused on earning rewards rather than the intrinsic value of journaling and self-reflection which takes away from the purpose of which this task is trying to achieve to offer an app/environment for genuine reflection and an authentic journaling experience. A game like experience may not be effective for all users with some users  finding it as a distracting or demotivating form of journaling. A personalised experience is a critical feature, but is also complex to design and create in comparison to the other realisations.

#### Quest Low Fidelity Home Page ####

![Image](Images/game.png)

The UI designed in Pencil shows the home page with buttons to direct the user to the various functions that the application offers. This includes logging history, a map view, journaling streak, account level and daily quest information. This proposal combines journaling with the experience of a game to offer a new form to journaling.

***

### Realisation Findings ###
The three realisations formed reveal a unique and interesting way in response to the task project designing a location-based diary application. These solutions will be evaluated against the tasks goal, rationale and purpose as well as through the consideration of human, and social aspects to see how user's are affected, and with further review into the complexity and effectiveness of the application to see if it suits the time constraints of this project.

<strong>Reminder Checklist</strong>

<ins>Purpose</ins>- To create a context-aware web application that enhances user experience through responsiveness and innovation.

<ins>Rationale</ins>- To support a healthier relationship with technology in everyday life. This involves promoting digital wellbeing, mindfulness, and moment awareness through the app's design and functionality. The app should encourage users to connect with their surroundings and reflect on their experiences

<ins>Goal</ins>- To develop a responsive application that allows users to record and reflect on their experiences in a meaningful way.

• Location tracking and mapping

• Context-awareness

• Responsive and accessible on a wide range of devices

• Journal entries with text, images, and timestamps
    
• Timeline view of entries

<strong><ins>Realisation 1 of the 'Trek' application is selected</ins></strong> as the most appropriate for to be continued throughout this projects design process due to the idea being the best at balancing all the features requested and best suits the mid point of the Venn diagram from earlier. The combination and support of multiple media formats would allow Trek to be best at satisfying the core requirement needs stated in the goals list above. The minimalistic UI proposed in the low fidelity GUI aims to fulfil the goal of a lightweight and understandable aesthetic to promote physical exploration and journaling to promote improved well-being. This user interface complements the user experience to create a design which is centred around the human wants and needs of the user by creating a space for self-reflection while preserving the authentic journal and scrapbook experience, which is highly beneficial to the user. Trek pleases social and cultural factors through mindful engagement with technology to effectively connect with the real world in the trend of digital detox while catering to the human need for belonging and connection with private entries to look back on.

***
## 1.5	Development of Selected Concept ##

The Trek application will be further developed in accordance with the double diamond model. The end of section 1.4 clearly defined what is expected and will be used as the criteria for effectiveness throughout the development stage going forward. 

Although this application is designed to be a cross platform service, the initial test versions from this development will be made as a web app with HTML, CSS, and JavaScript to test the concept before designing specially for various platforms. Feedback from prior tasks will be utilised in the development later on, suggesting to use CSS Grids and flex boxes to achieve responsiveness in adjusting to varying screen sizes. The core functionality and application concept were planned on the sitemap below to draft how the pages will link with one another.

#### Sitemap ####

![Image](Images/sitemap.png)

The web application is designed with hierarchy as the various core functionalities branch from the central home page which can quickly access all areas of the application. Research from the existing application Strava determined that the Mapbox API is best suited for geolocation features in this task which will support additional input from the universal RESTful and media capture APIs. The home page would have summaries from the main features, as inspired from the UI in realisation 1, with links to a calendar to view all entries through either a calendar or list view. Additional features that can be present here is being able to group, filter or search through entries. The map page displays the interactive map from Mapbox and is used to plan out journeys. The log page is the central function which lets the user input text and start recording their day. The Google Timelines feature inspires another possible which would be to automatically record the day in the background and then the log page is used to add context to this information and sort the day as a detailed timeline. These pages will now be drafted on Figma to test the aesthetic choices of the user interface as well as responsiveness and feature implementation in greater detail from the low fidelity GUIs.

07/10/2024

![Image](Images/figma.png)

The design choices from the initial UI aesthetic were kept in the Figma design but how the grid will need to adjust to different screen sizes were planned here for responsiveness across tablets and phones. Here the goal of being both lightweight and informative is achieved and will be unchanged going forward. Although this visualises only what the home page will look like so another UI was designed regarding the logging page.

![Image](Images/demo.gif)

This HTML file displays an interactive timeline made with CSS and JavaScript connecting to events. The idea from earlier about having two sides to a journal entry of part scrapbook and part map were incorporated here. These flex boxes and shapes are for the moment place holder information. This page in future development requires functionality to POST and GET information through REST API to display and store the entries that the user inputs. 

This idea will now be delivered as a presentation to gather feedback before the development of a fully programmed web application begins as the end of the define stage of the double diamond methodology nears.


***
## 2	Front End Programming ##

06/11/2024

The development of the Trek realisation will be done seperated into three steps to be done in order being

1. Designing a responsive HTML template

2. Incorprating API and front end functionality

3. Back end, sever support and launch

These steps give an order of goals to achieve before shifting the development process to ensure the foundations are executed well to support further development. This was clear from the early prototypes from the conceptualisation stage of this project and prior unrelated projects (Task 1) where challenges arose in creating a responsive web template which can adjust to a change in screen size while maintaining a consistant user interface. The Figma GUIs from section 1.5 of the journal where used as inspiration to create HTML and CSS files with a sole focus on design without planning for functionality.

***
## 2.1	Home Page Layout ##

Feedback from prior projects insisted using flexible grid containers with the contents inside being set to take 100% width, which as seen in the image above was highly effective in adjusting to a change in screen size. The blank space will be where a map is displayed with the text boxes displaying recent activity which for now store placeholder text to test how the concept can be displayed. This is the I index/home page where it holds a summary of all functionality and information while maintaining the minimalistic aesthetic aimed for in the conceptualisation research.

![Image](Images/v1.png)

This sketch over the index HTML image visualises the grid containers in the red rectangles. The drawn blue lines is the changes needed to get the desired boxes seen in the figma design. This will require the creation of 3 smaller grid boxes in this division.

![Image](Images/plan.png)

A map was designed in Mapbox Studio to be displayed in the blank placeholder space in the home page. This map is purely to display the users location and isn't where the journaling occurs. Initaly a monochrome map with use of serif fonts was decided to achieve that aesthetic of a map a reader would see in a novel and enhance that disconnection experience with the minimal usage of colours.

![Image](Images/studio.png)

A tokenid and style link was generated which allows the custom map and api functionality to be incorprated in the application. The image bellow displays the first test of using mapbox api in Trek.

![Image](Images/woops.png)

A single CSS file was made rather than using style tags in the html files for greater organisation throughout the repistitory and allowed for easier throubleshooting.
This was fixed with the following CSS

```
.map-section {
    display: flex;
    flex-direction: column;
    gap: 16px;
    margin-bottom: 2rem;
}
```

```
.map-container {
    background-color: #ffffff;
    border-radius: 12px; /* White boarder around map for a more tidy user interface*/
    padding: 1%;
    height: 400px; /* Width uses 100% of map-section and flexes with it*/
    overflow: hidden;
    position: relative; /* Respond with flexing section which the map is inside*/
}
```

```
@media (max-width: 768px) { /* When width is less than 768px then update classes*/
    .app-container { /* App container encompassing everything but the nav*/
        grid-template-columns: 1fr;
    }

    .nav-sidebar { /* Nav bar becomes horizontal and is placed at the bottom of the screen*/
        position: fixed;
        bottom: 0;
        left: 0;
        width: 100%;
        height: 60px;
        flex-direction: row;
        justify-content: space-around;
        padding: 0.5rem;
        border-top: 1px solid #eaeaea;
        background-color: #ffffff;
        z-index: 1000; /* Is layered in front of everything through the z axis*/
    }

    .main-content {
        padding: 1rem;
        padding-bottom: 70px;
    }
}
```

![Image](Images/indexmap.png)

```
mapboxgl.accessToken = 'pk.eyJ1IjoiYXRyb3VnaHRvbjAiLCJhIjoiY20ydTVobzk2MDZ4aTJxcG52ZWVmbTVoayJ9.0-MtCojihJsfD5HW-1Z7jw';
                    const map = new mapboxgl.Map({
                        container: 'map',
                        style: 'mapbox://styles/atroughton0/cm35kt3c900zb01pwgl3qbkz7',
                        zoom: 14
                    });
```

2 other Map styles and controls were added from the Mapbox API documentation (https://docs.mapbox.com/api/overview/) as the bright white map is not for best use practicaly. Added was an outdoor map which highlights different landscapes and the classic satelite view to add further engagement.

![Image](Images/mapchange.gif)

***
## 2.2	Designing the Journaling User Interface ##
Trek is intended to be a multipurpose and adaptable journaling application and therefore must be able to accept journal entries wheather they have geolocation data or not. This will be split into two html pages with one recording coordinate journies while the other page does the text input. As a map is the core function here, I tried to recycle code from the index html page and see what can be reused and modified.

![Image](Images/journalv1.png)

The desired layout for this page would be maily ocupied by the map and have buttons to start, stop, and potentialy drop markers down to refer to in later text journaling. This is a very basic design but highly effective at only giving the user the essential information which is required as conveyed in our goal for disconnection. The map-containers and map-section style classes in the CSS were adjusted to achieve this with two buttons made. All that is required is creating JavaScript utalising html geolocation module to gather, display and send geolocation data. The outdoor style is set to default in this section over the monochrome design.

![Image](Images/map.png)

```
                let tripCoordinates = []; // Array starts as empty
                let tripActive = false; //Recording is off by default

                // Function to start recording the trip
                function startTrip() { //defining the function of starting a trip and what is then performed
                    tripActive = true; //recording becomes true
                    tripCoordinates = [];
                    if (navigator.geolocation) {
                        navigator.geolocation.watchPosition(recordLocation, showError, { enableHighAccuracy: true }); //watch position notes the users position overtime with high accuracy on
                    }
                    alert("Trip recording started."); // popup message to alert the user
                }
```

```
                    function recordLocation(position) { //function to record position
                    if (tripActive) { //if trip is being recorded
                        const currentLocation = [position.coords.longitude, position.coords.latitude]; //find coordinates to define user location
                        tripCoordinates.push(currentLocation);

                        // Update map with trip path and draw visable line of the journey using tripCoordinates dictionary
                        map.getSource('tripLine').setData({
                            "type": "FeatureCollection",
                            "features": [{
                                "type": "Feature",
                                "geometry": {
                                    "type": "LineString",
                                    "coordinates": tripCoordinates
                                }
                            }]
                        });
                    }
                }
```

```
function stopTrip() {
                    tripActive = false; // when trip is stopped
                    alert("Trip recording stopped."); // alert the user
                    console.log("Recorded Trip:", tripCoordinates); // send journey coordinates to the console log as saving requires backend
                }
```

For now this collected the coordinates of a users journey and saved it to tripCoordinates which is then used to draw the journey and is sent to the console log. In a finalised version with a backend to manage data, this would send the data through restful api to be saved and used in other pages such as the log.html

![Image](Images/log.png)

08/11/2024

The next aspect to journaling is text input. This would have the user select a date, write a description and upload an image if they wanted to. This date will be used as a value to connect to trip journaling is a date is shared. This would be done in python but for now only the user interface was being designed at the current stage.

![Image](Images/textv1.png)

```
                <div>
                        <label for="date">Date</label>
                        <input type="date" id="date" name="date" required> <!-- Required means date and description must be selected before sending -->
                    </div>
                    
                    <div>
                        <label for="entry">Journal Entry</label>
                        <textarea id="entry" name="entry" rows="4" placeholder="Write about your trek..." required></textarea> 
                    </div>
                    
                    <div>
                        <label for="image">Photos</label>
                        <input type="file" id="image" name="image" accept="image/*"> <!-- Image files will be determined in python file -->
                </div>

```
The initial design without styling displays how minimal needs to be while providing the needed functionality. Just like the journal.html file prior, styling is fairly straightfoward and will consist of a flexable box taking 100% width in the app section will the input boxes from the original design.

```
.journal-entry-section form {
    display: flex;
    flex-direction: column;
    gap: 1.5rem;
    max-width: 800px;
    margin: 0 auto;
}

.journal-entry-section label {
    font-weight: 500;
    color: #666;
    display: block;
    margin-bottom: 0.5rem;
}

.journal-entry-section input[type="date"] {
    width: 100%;
    padding: 0.75rem;
    border: 1px solid #e0e0e0;
    border-radius: 8px;
    font-size: 1rem;
    color: #1a1a1a;
    background-color: #f8f9fa;
}

.journal-entry-section textarea {
    width: 100%;
    padding: 0.75rem;
    border: 1px solid #e0e0e0;
    border-radius: 8px;
    font-size: 1rem;
    min-height: 200px;
    resize: vertical;
    background-color: #f8f9fa;
}

.journal-entry-section input[type="file"] {
    width: 100%;
    padding: 0.75rem;
    border: 1px solid #e0e0e0;
    border-radius: 8px;
    background-color: #f8f9fa;
}
```

This CSS is visualised in the image below.

![Image](Images/textjournal.png)

The two remaining pages to be designed is the calendar and settings html files. The calendar page would need to feature a dynamic api which has its display made through user input and therefore requires the construction of the flask python file as a backend to send and recieve user input from storage files either being json, csv, or database files. The settings page in final lauch will idealy by were the user would adjust the look of the app such as fonts, colours, and access account information such as logging in and out but these options will not be prioritised in this task and will only be done if it fits the limited time constraints.

***
## 3. Backend support with Flask ##

Flask is a web framework for python and allows to view and test the Trek webapplication locally with access to backend features such as retrieving data from storage files. Twp JSON files will be selected to be used to storage location trip data, and text journal inputs as the nested structure of JSON files and the support for arrays makes it the ideal choice when querying both the trip and journal details when required. 

```
from flask import *
import random, sqlite3, requests, json, os
webapplication = Flask(__name__)
webapplication.secret_key = "session"

##Load Index HTML page##
@webapplication.route("/", methods=['GET'])
def WebRoot():
    return render_template("index.html")

#---------------------------------------------------------#
##Create URL Links to HTML Files##
@webapplication.route("/journal")
def journal():
    return render_template("journal.html")

@webapplication.route("/list")
def list():
    return render_template("text.html")

@webapplication.route("/settings")
def setting():
    return render_template("setting.html")

@webapplication.route('/calendar')
def calendar():
```
At the moment all this python file with the module flask is doing is it allows for the html files to load by defining the url and the file which is loaded. A couple of minor adjustments were made to have the application work run from python. Firstly the code for navigation in the html files were adjusted slightly to reference the route rather than the file name. Flask requires for the HTML files to be placed in a holder called 'templates' and the style.css and images used were placed in a folder called 'static'.

```
<a href="journal.html">  --- CHANGED TO ---> <a href="/journal">
```

***
## 3.1 Using HTTP Requests ##

REST API in the Trek application will be used to send data by communicating with http requests from the frontend and backend of the application. This creates the core functionality of having user inputs displayed in other parts of the application. As seen in the itital design of the index page in section 2.1, requests are required to gather stored data to calculate the monthly insights. This though requires user data to be present first so we will start with creating the method to get the trips stored in a trips.json file.

The javascript used to send trip details to the console in section 2.2 of the journal already collects the information needed and only requires slight adjustment to communicate with the python file. 

```
 if (tripData && tripData.length > 0) {
                    drawJourneyPath(); // Draw the trip on the map using the coordinates recorded
                    
                    const tripDetails = { // get what values are stored in tripDetails
                        dayOfWeek: getDayOfWeek(tripData[0]?.timestamp), // Only record the day part from the timestamp
                        startTime: formatTimestamp(tripData[0]?.timestamp), //The timestamp when the trip started
                        endTime: formatTimestamp(tripData[tripData.length - 1]?.timestamp), //The timestamp when the trip ended
                        coordinates: tripData.map(entry => ({ // Records location and at what time
                            timestamp: formatTimestamp(entry.timestamp),
                            location: entry.coordinates
                        })),
                        distance: Math.round(runningDistance), //Round distance in metres
                        duration: tripData[tripData.length - 1]?.timestamp - tripData[0]?.timestamp //Calculate how long the trip was
                    };

                    fetch('/save_trip', { //Communication method with flask file
                        method: 'POST', //Method is POST
                        headers: {
                            'Content-Type': 'application/json', //For json file
                        },
                        body: JSON.stringify(tripDetails) //Formatted to be stored as a json file using jsonify module
                    })
                    .then(response => response.json())
                    .then(data => console.log("Trip data saved:", data)) //For trouble shooting if successfull
                    .catch(error => console.error("Error saving trip data:", error)); //For troubleshooting an error
                    console.log(tripData) //Display values in console
                } else {
                    alert("Tracking data is empty. Try moving around and restarting tracking."); //If trip failed, alert the user
                }
```

This javascript allows for the collected values to be gathered under tripDetails and send to the python file using the 'POST' method. Now the function of '/save_trip' must be defined in the python file. 

```
JOURNAL_FILE = 'journal_entries.json' #The json files are globally defied
TRIPS_FILE = 'trips.json'
```

```
@webapplication.route("/save_trip", methods=['POST']) # Matching route and method to the JavaScript
def save_trip():
    try:
        trip_data = request.json # Give a value to the json file
        if os.path.exists(TRIPS_FILE):
            with open(TRIPS_FILE, 'r') as f: # Find and read the json file
                trips = json.load(f)
        else:
            trips = []
        
        trip_data['id'] = len(trips) + 1 # Gives a unique id to a trip by adding 1 based on the total amount of entries
        trips.append(trip_data) # Add trip to trips
        
        with open(TRIPS_FILE, 'w') as f: # Open json file to write
            json.dump(trips, f, indent=2) # Better organisation
```

This function allows for user input of from journal.html and stores trip data using geolocation apis.

```
{
    "dayOfWeek": "Friday",
    "startTime": "08/11/2024 22:28:41",
    "endTime": "08/11/2024 22:28:41",
    "coordinates": [
      {
        "timestamp": "08/11/2024 22:28:41",
        "location": [
          153.04146398847675,
          -27.236568437880734
        ]
      }
    ],
    "distance": 0,
    "duration": 0,
    "id": 1
  },
```

This first test was started and ended within a second so the distance, duration and timestamps wont look too interesting but this displays that the concept works. Next is to have these trips sorted into dates and displayed on another page.

Before this though the text input page '/list' needed updating to send its data and images to the 'journal_enties.json' file. Html only required the addition of 1 line to communicate with flask

```
<form action="/save_journal_entry" method="POST" enctype="multipart/form-data">
```

A python file had to be defined which not only collected this data like the trips one, but needed to manage how images were accepted and organised. It was decided that for ease of organisation, a sub folder will be automaticly generated inside uploads for the journal entry date that the image is apart of. This allows for images which share a date to be easily grouped in contrast to programming a naming convention which got complex really quickly.

This is the defined function in flask to manage text journal inputs and is split into 2 snipits to see more clearly what does what

```
@webapplication.route("/save_journal_entry", methods=['POST'])
def save_journal_entry():
    raw_date = request.form['date'] #Set the value for the date selected
    try:
        date_obj = datetime.strptime(raw_date, "%Y-%m-%d") #Get just the date without the second part of the timestamp
        formatted_date = date_obj.strftime("%d/%m/%Y") #Format to d/m/y
        folder_date = date_obj.strftime("%d-%m-%Y")  # Format for folder name
    except ValueError:
        formatted_date = raw_date
        folder_date = raw_date.replace('/', '-') #Swap / for - in folder name, looks nicer :)

    entry_text = request.form['entry'] #Set value for text inputted
    image = request.files.get('image', None) #Request for the imaged collect if uploaded
    
    entry_data = { #Bunch collected data to be stored in json
        "date": formatted_date,
        "entry": entry_text,
        "image_path": None
    }
```

```
#Part 2 - Image storage
if image:
        # Create date-specific folder
        date_folder = os.path.join(UPLOAD_FOLDER, folder_date) #Get date
        os.makedirs(date_folder, exist_ok=True) #Make only if isnt already existing
        
        filename = secure_filename(image.filename)
        image_path = os.path.join(date_folder, filename)
        relative_path = os.path.join(folder_date, filename)  
        image.save(os.path.join('static/uploads', relative_path)) #Save date in the folder just made
        entry_data["image_path"] = relative_path

    if os.path.exists(JOURNAL_FILE): #Read json file
        with open(JOURNAL_FILE, 'r') as f:
            journal_entries = json.load(f)
    else:
        journal_entries = []

    # Update existing entry or add new one
    existing_entry = next((entry for entry in journal_entries  #Add entry if new, append if date exists
                         if entry['date'] == formatted_date), None)
    if existing_entry:
        existing_entry.update(entry_data)
    else:
        journal_entries.append(entry_data)

    with open(JOURNAL_FILE, 'w') as f: #Write these changes
        json.dump(journal_entries, f, indent=2)

    return redirect(url_for('journal')) #Load page
```
Copiolet AI assistance was used in troubleshooting how to upload images after many errors. This function was successful at storing text input which again will be later referd to when viewing entries for a date. Storing output can be seen below along with the folder creation for dates with an image assigned.

```
{
    "date": "10/11/2024",
    "entry": "testing testing",
    "image_path": "10-11-2024/Screenshot_2024-11-09_at_9.55.38_pm.png"
  },
```

![Image](Images/folder.png)

***
## 3.2 Displaying trips ##

09/11/2024

The idea is that all trips will need to be made visable on a page which allows the user to select a trip to view the journal entries for that day. This was done initialy by using the following html

```

```

the python allowing for this to happen was

```

```

This generated the following page

![Image](Images/calendarv1.png)

As displayed, trips are organised by there date -'startTime'- and provide a summary of the trips statistics. This displays that details of a trip is being recieved but the python, html and css will need to be adjusted to achieve the ideal user interface depicted in the sketch below. This has only the date of trips displayed which will then direct the user to a log page which combines all the entries sharing a date and displays text input and images with the same date. Another issue is that only trips are currently displayed here and will also need to display text entries without a trip.

![Image](Images/calendarsketch.png)

This had the '/calendar function' changed to satisfy these needs

```
@webapplication.route('/calendar')
def calendar():
    try:
        # Load trips data
        with open(TRIPS_FILE, 'r') as f:
            trips = json.load(f)

        # Load journal entries data
        with open(JOURNAL_FILE, 'r') as f:
            journal_entries = json.load(f)
        
        # Extract dates and details from trips
        trip_events = [
            {
                'tripDate': trip['startTime'].split()[0],
                'time': trip['startTime'].split()[1],
                'day': trip['dayOfWeek'],
                'description': f"Trip #{trip['id']} - Distance: {format_distance(trip['distance'])}"
            }
            for trip in trips
        ]
        
        # Extract dates and details from journal entries
        journal_events = [
            {
                'tripDate': datetime.strptime(entry['date'], "%d/%m/%Y").strftime("%d/%m/%Y"),
                'time': None,
                'day': datetime.strptime(entry['date'], "%d/%m/%Y").strftime("%A"),
                'description': "Journal Entry"
            }
            for entry in journal_entries
        ]

        # Combine events by date, both trip and text entries
        combined_events_dict = {}
        for event in trip_events + journal_events:
            date = event['tripDate']
            if date not in combined_events_dict:
                combined_events_dict[date] = {
                    'tripDate': date,
                    'day': event['day'],
                    'events': [event['description']]
                }
            else:
                combined_events_dict[date]['events'].append(event['description'])

        # Sort combined events in descending order by date
        combined_events = sorted(
            combined_events_dict.values(),
            key=lambda x: datetime.strptime(x['tripDate'], "%d/%m/%Y"), #Formats the day into d/m/y as this is not the default standard
            reverse=True #Order is reversed to display the most recent trip first
        )

        # Pass combined events to the calendar template
        return render_template('calendar.html', events=combined_events) # Sorted order is sent
```

This css was refined to achieve the look of a traditional calendar as put in the snipit below

```
.calendar-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: 12px;
    padding: 16px;
    width: 100%;
}
```

And finally the html section was updated to accomedate a dynamic system of dates being added and redirecting the user to the page of the date selected

```
 <div class="calendar-container">
                {% if events %}
                    {% for event in events %}
                        <div class="date-group" onclick="location.href = '/log?date={{ event.tripDate }}'">
                            <h2>{{ event.day }}</h2>
                            <h5>{{ event.tripDate }}</h5>
                        </div>
                    {% endfor %}
                {% else %}
                    <p class="no-events">No trips recorded yet.</p>
                {% endif %}
            </div>
```

Numerous of dates were added to the json file to test how multiple dates would look like. This final generated design can be seen below along demonstarting how responsiveness was achieved to adjust to a changing in screen width.

![Image](Images/calendar.png)

![Image](Images/calendaradjust.gif)

***
## 3.3 Viewing Individual Entries ##

Now approaching the end of what is required regarding the functionality criteria in the development stage of the double diamond process is creating the page which combines and displays all the location, text, and image records in the one place. This page will be called log.html and is accessible by clicking the date box displayed in calendar.html (as made possible through this line 

```
<div class="date-group" onclick="location.href = '/log?date={{ event.tripDate }}'">
```

In the project pitch for Trek, we aspired to deliver a journal system where it was more like a scrapbook where you can adjust pieces of the page, and draw freely to recreate that authentic journaling experience but due to the time constraints of the task and limitations of html and JavaScript will have the goal changed to just display a timeline, drawn map, text input and images. This provides a detailed summary of a recorded day efficiently in html. This design was sketched below to display roughly how it can look to achieve this goal.

![Image](Images/logsketch.png)

A timeline feature as planned would used pins which would be an additional button when recording trips to save a point with coordinates to refer to later like a checkpoint. This feature is not yet done and would be done later if there is time. For now a map will be drawn using the combined coordinates if multiple trips are assigned to one date and will list the individual trips with text input and images which share that same timestamp.

The map script and styling is the same that was used in the home page and journal.html but with its diamentions changed to be more square. Is also simular to the calendar page which uses if and for statements to retrieve data in a loop. The html code to produce this page can be seen below along with the first attempt design.

```
<main class="main-content1">
            <header class="header">
                <h1 class="app-title">Trek Journal - Event Log</h1>
                <p>Details for: <strong>{{ selected_date }}</strong></p> <!-- Display the date of the journal entry in the title -->
            </header>

            <div class="map-trip-container"> <!-- Map part of the page -->
                {% if trips|length > 0 %} <!-- If amount fo dates is greater than 0, produce a map -->
                <div class="map-container2">
                    <div id="map"></div>
                    <!-- Buttons inside map container -->
                    <div class="layer-controls"> <!-- Map style buttons -->
                        <button onclick="changeMapStyle('mapbox://styles/atroughton0/cm35kt3c900zb01pwgl3qbkz7')" title="Novel">📖</button>
                        <button onclick="changeMapStyle('mapbox://styles/atroughton0/cm377mlbj003001q33hnm157q')" title="Outdoors">⛅</button>
                        <button onclick="changeMapStyle('mapbox://styles/atroughton0/cm3ax49si00g301ptcqgrh7ar')" title="Satellite">🛰️</button>
                    </div>
                </div>
                {% endif %}

                <div class="trip-details"> <!-- Individual trips section of the page -->
                    <ul class="event-list"> <!-- Displayed as a list -->
                        {% for trip in trips %}
                            <li class="event-item"> <!-- Details of the trip -->
                                <h3>Trip {{ loop.index }}</h3>
                                <p><strong>Start Time:</strong> {{ trip.startTime }}</p>
                                <p><strong>End Time:</strong> {{ trip.endTime }}</p>
                                <p><strong>Distance:</strong> {{ trip.distance }} meters</p>
                            </li>
                        {% endfor %}
                    </ul>
                </div>
            </div>

            {% if journal_entry %}
                <section class="journal-section"> <!-- Text entry and image display -->
                    <h2>Journal Entry</h2>
                    <p>{{ journal_entry.entry }}</p>
                    {% if journal_entry.image_path %} <!-- If folder exist for the entry date, gather image -->
                        <img src="{{ url_for('static', filename='uploads/' + journal_entry.image_path) }}" 
                             alt="Journal Image">
                    {% endif %}
                </section>
            {% endif %}
        </main>
```

![Image](Images/logv1.png)

The first design already has some cropped text and doesn't adhere to the goal for responsiveness but displays that the concept was met and needs some refinement to improve this. Displayed are the map which as the trip was less than a second doesnt have it drawn, the trip/s, the text and the image uploaded. This has created a successful way to journal while using multimedia and demonstartes the core functionality that is expected from Trek.

These refinements produced this final view. This date has no text input and displays how it can dynamically adjust and remove to a section with no input. 

![Image](Images/finallog.png)

***
## 3.4 Last Refinements ##

12/11/2024

This web application is now capable of retrieving input from the user, gathering location date through geolocation api,  communicating the input to other pages of the web app, and displaying a complete journal entry with the Mapbox API. The functional requirements have been achieved but can be further improved and refined before the dilivery part of the double diamond process.

![Image](Images/goals.png)

This note displayed the final parts of the web application which needed attention. Most are small changes to styling to improve responsiveness but one more complex feature was to go back to the home page and display replace the placeholder values in monthly insights with values calculated with user input.

It was determined to change this to weekly as monthly is too long of a time range to really be useful.

The index route in the python file was updated to perform these tasks and can be seen below.

```
@webapplication.route("/", methods=['GET'])
def index():
    try:
        # Load trip data #opens trip json file to read
        with open(TRIPS_FILE, 'r') as f:
            trips = json.load(f)

        # Get the date 7 days ago
        today = datetime.today() #Finds the present date
        seven_days_ago = today - timedelta(days=7) # subtracts 7 to find the start to the week

        # Filter trips from the last 7 days
        recent_trips = [
            trip for trip in trips 
            if datetime.strptime(trip['startTime'].split()[0], "%d/%m/%Y") >= seven_days_ago
        ]
        
        # Calculate weekly insights for the three text boxes
        total_distance = sum(trip['distance'] for trip in recent_trips) # Sum of distance in the past week recorded
        total_entries = len(recent_trips) # Number of trips
        total_duration = sum(trip['duration'] for trip in recent_trips) # sum of trip duration in the past week

        # Format and group the insights to be post
        weekly_insights = {
            "distance": format_distance(total_distance),
            "entries": total_entries,
            "duration": format_duration(total_duration),
        }

        # Extract details for each trip 
        trip_events = [
            {
                'tripDate': trip['startTime'].split()[0],
                'day': trip['dayOfWeek'],
                'coordinates': trip['coordinates'][0]['location'] if trip['coordinates'] else None,
                'description': f"Trip #{trip['id']} - Distance: {format_distance(trip['distance'])}"
            }
            for trip in recent_trips
        ]

        # Sort trips by date in descending order
        recent_events = sorted(
            trip_events, 
            key=lambda x: datetime.strptime(x['tripDate'], "%d/%m/%Y"), 
            reverse=True
        )[:3]

        # Pass insights and recent events to the index template
        return render_template('index.html', 
                               recent_trips=recent_events, 
                               weekly_insights=weekly_insights)
```
This replaces the placeholder values with actual recorded data.

***
## 4 Delivery and Reflection ##

14/11/2024

Looking back at the start of the journal where the idea was developed from a simple prompt, you can see how the idea has changed and been formed overtime throughout this journal. Before the delivery through hosting server, the goals and ideations will be compared to the developed Trek web application to see how successful it is at meeting the task goals and the desired functionality requirements.

![Image](Images/Padlet.png)

Trek almost perfectly satisfies the prompt which started this whole project. Trek allows the user to record days and capture them in great detail. Learning my lessons from prior tasks (task 1), a lot more time was invested into styling in CSS to make the application responsive through more approapiate usage of grid and flex containers with its items using 100% of the width. Is absolutely a mapped diary but only falls short on a map which has its images placed on where it was taken as inspired by one of the existing designs senn in Apple Maps but would have been overkill and out of the scope of the design purpose fueling this project.

✅ The ability to add photos, notes, and even short audio recordings to each point on the timeline.

The application does support multimedia, although not to the level of supporting audio recordings and a timeline but you could say the failure to add this range of note taking is a blessing in disguise when you consider the task purpose of taking away distractions, staying disconnected and not spending alot of time focusing on what is added to the journal and maintaining its minimal aesthetic.

❌ Timeline view that allows users to scroll through their journey chronologically, with entries displayed alongside the map.

A timelines and marked locations was not included in the final version of Trek and would definitely be an area to expand on in future versions of the app but as mentioned with the last point it isn't a major miss and didn't effect the effectiveness of achieving the task goal.

✅ Group and filter entries

This is displayed in the calender.html with its entries grouped into days and then displayed in a calendar like format and again in the home page with the calculated insights which dynamically change through the use of grouped and filtered entries which output from the python file

✅ View travel history through an engaging and minimalistic interface

The log.html page was highly effective at capturing a day in displaying its data as minimal as possible while being understandable and engaging to the user

✅ Creation of context awareness through the usage of the MapBoxes API and Media Capture API

APIs were fundamental to how this app works and would not be possible without geolocation API to gather location data, and Mapboxes API to display the data with context awareness. Media capture API was however not included but wasn't required as the python file did all the image handeling but can be useful as being able to take pictures directly from the application which will be discussed in future improvements below.

***
## 4.1 Hosting ##

With Trek completed it was time to see if the web application can connect to a server and be accessed over the web for external access. Pythonanywhere, Replit, and Railway were all tried but each came back with errors about loading templates or data not working. Due to the time constraints, it seemed like the apps code would have to be all changed to be dedicated to these hosting services and was unrealistic when trying to test the app. To test responsiveness and mobile usage, the app connected to the laptop by changing the port to 'flask run --host=0.0.0.0' to be listenable on all networks and was used in the final demonstration video. Support for servers and hosting will be explored further in section 4.2 below.

***
## 4.2 Future Improvements ##

I am extremely happy with Trek and its functionality despite a few minor features which were not present in the final project. The main part that I would like explored in future refinements is incorprating a scrapbook like form of journaling and make that you can freely draw, place videos, audio snipits, and more, and a timeline feature with markers in the trip journaling and log pages. As we found out, these features cannot be effectively made on a web application without making another dedicated web to perform these tasks (scrapbook). This suggests that Trek would be more suitable as a mobile app with access to local storage to keep user data secure and take advantage of the power of the users' devices. If it remains a web app, a data base and log in features is a must as all user data can be reviewed by another is another user has access to this web application which greatly goes against data protection guidelines. For hosting, Node.js and Node Express may be the easier option of making Trek accessible over Flask and allow for improve maintenance, scaliability, and flexable form. 

I hope the readers and all involved stakeholders can see the how the task rationale and design goals have been achieved in Trek and see how these ideas flowed from start to finish. Please view the demonstration video below to see Trek in action.

<strong> Rationale </strong> - The goal and expected outcome for this project's application to achieve by the end of the design process would be to support a healthier relationship with technology in everyday life by embracing digital wellbeing, promoting mindfulness, as well as presenting moment awareness through the simplicity of an adaptive journal to store meaningful experiences. 

***
## 4.3 Demonstration ##
