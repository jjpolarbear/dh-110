# FamJam
Jay Jay Phoemphoolsinchai | DGT HUM 110 | Spring 2023

## Project Description:
An app that allows for members of a family to post updates in a timeline fashion. The posts can be one of many different types: text only, text and pictures, pictures only, text and music, and so on. This would allow members to simply post what they want without needing to follow a strict format. Potential features may include having music playing throughout the app picked by a designated family member for the day or having a "family drive" whose content can be embedded in the posts. The goal is to create a comprehensive timeline for the day with many family members creating interleaving posts, allowing members that may not live near each other to still remain in close contact with each other and know what is happening in each other's lives.

## Nielsen's 10 Heuristics:

1. Visibility of System Status
    * The design should let the user know what is happening with noticeable feedback.
1. Match between system and the real world
    * The design should only use language that is familiar to the user, or otherwise language that would commonly be found in the real world.
1. User control and freedom
    * The design should allow users to backtrack if they performed an action on accident.
1. Consistency and standards
    * The design should follow the conventions and standards of the platform.
1. Error prevention
    * The design should include guard rails that prevent users from causing problems.
1. Recognition rather than recall
    * The design should avoid making users recall information and instead focus on making important pieces of information visible.
1. Flexibility and efficiency of use
    * The design should incorporate the use of shortcuts that allow power users to perform actions efficiently.
1. Aesthetic and minimalist design
    * The design should not have any visual clutter and only focus on important pieces of information.
1. Help users recognize, diagnose, and recover from errors
    * The design should include human-friendly error messages that point the user to the problem and illustrate a way to resolve the error.
1. Help and documentation
    * The design should have helpful documentation that allows users to perform the actions they want to perform if they get stuck.

## Severity Ratings:

1. Cosmetic problem only
1. Minor usability problem
1. Major usability problem

---

## App 1: [FamilyWall](https://www.familywall.com/en/index.html)
![Introductory Screen](/resources/images/assignment1/FW_0.jpg)

A family organizer app that includes shared calendars, lists, meal planners, and more. However, a decent chunk of the features are hidden behind a premium subscription, which may be offputting to some looking for a free option.

**Overall evaluation**: An app that has many features, but it is unfortunate that sometimes when you press on a part of the app, a screen comes up saying to buy premium. The design also feels sometimes *too* generic, making it seem like there wasn't much polish. However, using it is definitely very robust, and it gets the job done without many bumps.

1. Visibility of system status	
    * There is a red dot on the user's profile button on the top-left of the screen, signaling that there is something unseen. This also applies to pill overlay on the bottom. Additionally, when adding an event to the calendar, a small popup appears signaling that the operation was successful.
    ![Adding an event](/resources/images/assignment1/FW_1.jpg)

1. Match between system and the real world
    * The various services are listed using simple terms that everyone would be able to understand, regardless of age. There are also simple pictures attached with each service term that helps people visualize.
    ![Home screen](/resources/images/assignment1/FW_2.jpg)

1. User control and freedom
    * When viewing a list and adding an item, it seems that there is not a way to cancel that action. To get out of adding an item, the user must either add a random item or navigate backwards using the back arrow, which is unideal. For example, since adding an item makes an autosuggestion dropdown appear, it blocks the view of the rest of the list items. Additionally, there is not a way to cancel the process of adding.
     
    * **Severity (2)**

    * **Recommendation**: Touching in the empty space either in the top list title panel or bottom list panel removes the autosuggestion dropdown, and typing brings it up again. Replace the square tick box when adding an item, which has no functionality, with a trash can icon with delete functionality.

    ![Adding an item to a list](/resources/images/assignment1/FW_3.jpg)

1. Consistency and standards
    * The app does not appear to take advantage of modern Android features, since when prompting for permissions, it redirects the user to the Settings app and has the user add the permissions manually. This is different from most other apps.
     
    * **Severity (3)**

    * **Recommendation**: Ask the user for permission directly in the app instead of navigating the user to the Settings app and apply the permissions manually.
    
    ![Asking user for permission](/resources/images/assignment1/FW_4.jpg)

1. Error prevention	
    * When creating an event in the calendar, the cursor automatically appears in the title field and preps the user for typing, signaling that the field should be filled out.

    ![Adding an event](/resources/images/assignment1/FW_5.jpg)

1. Recognition rather than recall	
    * When viewing a list, there is an option to add items from history. This allows users to both avoid typing long items and also instantly remember something that they would need since their brain would be prompted to think about the item and realize that they're out of it and would like to buy it again. This avoids the issue of forgetting something that was needed or walking around and worrying if they're forgetting something.

    ![Adding item from history](/resources/images/assignment1/FW_6.jpg)

1. Flexibility and efficiency of use
    * There does not seem to be many tricks for power users to take advantage of, and many things are "face-up".
     
    * **Severity (2)**

    * **Recommendation**: Add more gesture interactions. For example, allow users to delete items from a list by swiping right (or left). As of now, users must first touch the item they want to delete, which makes another screen appear, and then press the delete button. This is slow and can be annoying if many items needed to be deleted.

    ![Detailed list screen](/resources/images/assignment1/FW_7.jpg)
    ![Detailed list item screen](/resources/images/assignment1/FW_7.1.jpg)

1. Aesthetic and minimalist design	
    * A clean, simple color palette combined with a design free of visual clutter makes for an enjoyable user experience. Additionally, the icons chosen are very minimal yet convey the meaning clearly.

    ![Secondary home screen](/resources/images/assignment1/FW_8.jpg)

1. Help users recognize, diagnose, and recover from errors	
    * When adding an event without a title, an error message appears with an arrow pointing to where the error originates, which lets the user know what to do to resolve the error.

    ![Adding event without title error](/resources/images/assignment1/FW_9.jpg)

1. Help and documentation	
    * There is a help menu available, which seems to embed a website page. However, the website does not mimic the style of the app, which creates a visual discrepancy. This also creates load time since unlike navigation between different screens in an application, the application has to fetch the contents of the page.
     
    * **Severity (2)**

    * **Recommendation**: Make a native help section.

    ![External help screen](/resources/images/assignment1/FW_10.jpg)

---

## App 2: [Share(d)](https://share-d.com/en/)
![Introductory Screen](/resources/images/assignment1/S_0.jpg)

Described as "THE app for ALL families", the app allows families to organize themselves using shared calendars, budgets, lists, among others. They also have more of a focus on separated parents than other similar apps. Additionally, unlike other apps, they include the ability to make certain things private, such as events or lists, meaning that the app can also be used for one's personal life in addition to their familial life, allowing for one to organize both those parts of life in one app.

**Overall evaluation**: Overall a neat app that has some unique features that some other similar apps do not. However, sometimes the actual usage feels a little clunky, since sometimes it can be difficult to do things that should feel trivial to do. Also, seeing uncaught errors makes the product seem a little unfinished.

1. Visibility of system status	
    * When updating a list item, it shows a popup saying that the item has been updated. However, it seems that there is sometimes there is a disconnect between the number of items in a list when viewing it on the "Lists" screen and the actual number of items, since it sometimes shows "`NaN` tasks" when that is clearly not the case or a mismatch (for example, displaying 1 task on the overview screen but actually have 2 tasks when navigating into the specific list's screen). This can also be seen by the "All my tasks" task accumulator. 
     
    * **Severity (3)**

    * **Recommendation**: Fix whatever is causing miscommunication between components of the app so that information is coherent and accurate.

    ![Task count disconnect](/resources/images/assignment1/S_1.jpg)
    ![Task update popup](/resources/images/assignment1/S_1.1.jpg)

1. Match between system and the real world
    * As mentioned earlier, sometimes the number of tasks in a list would should as `NaN`. However, this is uncommon language and many would not know that it stands for "not a number". Other than that, all the terms and visuals used in the app are basic and would be understandable by the average user.
     
    * **Severity (1)**

    * **Recommendation**: Catch the error and display something to the user that the average user would be able to understand.

    ![NaN](/resources/images/assignment1/S_2.jpg)

1. User control and freedom
    * When viewing a guide in the "Help Center", there is no way to exit the guide other than going through all the slides of the guide.

    * **Recommendation**: Allow users to leave the guides at any point.
     
    * **Severity (3)**

    ![Guide](/resources/images/assignment1/S_3.jpg)

1. Consistency and standards
    * Unlike the previous app, this app takes advantage of Android's ability to ask users for permissions directly in the app, which is the expected behavior for most apps.

    ![Asking for permission in-app](/resources/images/assignment1/S_4.jpg)

1. Error prevention	
    * When creating an event, the app does not immediately prompt the user to fill in a title. This also applies to creating a list.
     
    * **Severity (2)**

    * **Recommendation**: Immediately make the event title field focused when creating an event, since it is required. Users will have to do it anyways, which also means it saves time.

    ![Creating an event](/resources/images/assignment1/S_5.jpg)

1. Recognition rather than recall	
    * Events on the calendar are not shown on the main home screen, so users must navigate to the calendar to see details. This could create instances where the users forget they have something planned, and don't bother to check the calendar since they don't think they have anything.

    * **Severity (2)**

    * **Recommendation**: Show upcoming events on the home screen so that users know they have something coming up. Allow users to think "Oh yeah, I have that event coming up!" instead of "Hmm, do I have anything coming up? I don't think so".

    ![Detailed calendar view](/resources/images/assignment1/S_6.jpg)

1. Flexibility and efficiency of use
    * It can be difficult to do simple actions. For example, when viewing a list, if the user wants to delete an item, they have to navigate through two more screens. First, they have to press the ellipsis icon, and then press the vertical ellipsis icon in the top-right, and then finally press the delete action. However, on the other hand, they do have easy access to delete lists by swiping left. They just didn't extend that to list *items*, for whatever reasons. Another example is when trying to change the name of a list. Instead of long-pressing on the list name, pressing the list name, having an edit icon next to the list name, or anything, it's hidden in a menu *in another menu*.
         
    * **Severity (3)**

    * **Recommendation:** Add gestures that allow for easy access to important actions. Also make things easier to access in general without hiding them in menus within menus.

    ![Trying to delete a task](/resources/images/D/S_7.jpg)

1. Aesthetic and minimalist design	
    * The main color scheme of blue and white is pleasing to the eyes. There are no real distractions that detract from the overall immersiveness of the app.

    ![Home screen](/resources/images/assignment1/S_8.jpg)

1. Help users recognize, diagnose, and recover from errors	
    * When in the screen to add a partner to the Circle, leaving a required field blank highlights the field red, puts an warning sign, and creates a toast asking if the user forgot to fill in a field.

    ![Trying to add a partner without a name error](/resources/images/assignment1/S_9.jpg)

1. Help and documentation	
    * There is a "Help Center" available in the app that has many different services: it has guides on using specific parts of the app, a FAQ section, a way to get in contact with customer service, and also the privacy policy.

    ![Help center screen](/resources/images/assignment1/S_10.jpg)