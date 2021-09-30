# Self-Care Center (Solo Challenge)
Turing School of Software & Design
Mod 1 2108 FEE - Mid-Mod Solo Challenge

A web app that helps to remind users of their inherent value by cycling through a number of affirmations and mantras at the click of a button. User chooses which of the two they want to see. They can 'like' any messages which will add them to a 'favorites messages' grid. 

### Deployable Link
<https://kbergsund.github.io/self-care-center/>

## Languages/Technology
Javascript, HTML, CSS, Chrome Dev Tools, Github

### Learning Goals

* Gain experience building an application from scratch that utilizes HTML, CSS and JavaScript
* Write HTML and CSS to match a provided comp
* Understand how to listen to and respond to user events
* Individualize your programming skill set by completing chosen challenges of varying complexities
* Continue gaining experience with refactoring & cleaning up code

### Setup

1. Fork this project to your own Github account
2. Clone the repository to your local machine
3. `cd` into the project
4. View web app by running `open index.html` via your terminal.

### Project Overview

We were given a design comp that we had to recreate using HTML and CSS. After that, we had to make it functional, implementing Javascript so that users could successfully choose affirmation/mantra using radio buttons and cycle through messages. There is some error handling- a user cannot click 'receive message' without first determining which kind of message they want to see. Also, once they are cycling through messages, they can click a 'clear' button to reset the homepage- the message disappears, the meditating image reappears, and the radio buttons deselect. Users also have the ability to favorite, or 'like', messages. Using Google Material Design icons, I added a heart icon underneath each message that turns pink when clicked or gray when clicked again. The message will only be 'liked' if left pink. If the message appears again in the rotation, the heart will already be pink, indicating that the message has already been liked. Once viewing messages, a 'view favorites' button appears underneath the 'clear' button. Clicking it will take users to a separate page where all of their favorited messages appear in a single column. They can remove any individual messages from the page and their list of favorites by doble clicking on it. On that page,there is a button that will take them bak to the main message generation page. As a final extension, I adjusted the message generation mechanics so that no repeat affirmations or mantras will show until the full list of each has been cycled through. Before any repeats appear, a message appears that alerts users that they will start seeing repeats. The 'like'button will not be visible for this message. 

### Web App Attributes
1. Standard message generation based on selection & clear button

![Message Generation   Clear Button](https://user-images.githubusercontent.com/49960644/133011453-e6428c12-9c78-47c7-badc-365be357af56.gif)

2. 'Like' button, Favorites Messages grid display & double click to delete.

![Favorite Message Button   Grid](https://user-images.githubusercontent.com/49960644/133014143-44abb562-3047-4953-b775-66f2ca70548f.gif)

3. No repeat messages until all of that type have cycled through. Alert message when this has happened. Previously liked messages will remain liked.

![No Repeats](https://user-images.githubusercontent.com/49960644/133014128-fd4cad85-7ef4-404d-818a-b2f77a6f0c78.gif)

### Contributors
Kyra Bergsund
