# Lab Classes

In this section of our webpage, we showcase the results of the various assignments we were given
through the semester.

---

# Assignment 1 - Good and Bad Design

In this assignment, we explore examples of good and bad UI, focusing on what is done right and what should
be done differently.

## Examples of Good UI

### I. Circular Launchers

> Android launchers are apps that can spice up your phone's home screen (...) - [source](https://www.cnet.com/how-to/everything-you-need-to-know-about-android-launchers/)

Launchers for Android phones represent, in my opinion, an effective implementation of an original UI concept. The point of
launchers (in general) is to customise your home screen, making it functional and personal, depending on your own preferences.

**Circular launchers**, in particular, embrace a very interesting area of the mobile world: the thumb zone.

![](https://i.imgur.com/6b5Nwu0.png)

#### What's good about them?

Circular launchers succeed because they simply *play nice* with your thumbs. No matter how you're using your device (left or right handed, using one or
two hands), these are specifically designed for usability; you won't ever need to stretch your fingers to reach certain elements,
which is a very common problem.

In his book *Designing for Touch*, writer Josh Clark has recorded in-depth information on [how people hold their devices](https://www.smashingmagazine.com/2016/09/the-thumb-zone-designing-for-mobile-users/), obtaining
the following results:

![](https://i.imgur.com/yTgxOPd.png)

By focusing on the natural zone of the touchscreen, the circular launchers provide a very elegant solution to this common usability
issue, and thus represent a good, comfortable user interface.

### II. Slack
 
> Slack creates alignment and shared understanding across your team, making you more productive (...) - [source](https://slack.com/features)

Slack is a digital communication tool that helps an organization — all the pieces and the people — communicate with each other wherever they are. Slack provides a very pleasant and intuitive interface making it easier for the user to use and learn, which leads to a better user experience.
 
![](https://i.imgur.com/AfsC3fJ.png)
 
#### What's good about it?

- **Channels:** Channels are an intuitive away to split working subjects, keeping each topics' conversations well organized. Channels appear on the left side of the screen aligned vertically and organized in alphabetical order, which helps the user to quickly change beetween each one of them. 
- **Pinned Messages:** Pinned messages are a very good way to markdown important messages. They also make it easy, to people that were offline at the time, to find them. At the right side of the screen and click of a button away, everyone can find out a list of important messages that would be long lost by now. This way, everyone is able to keep up the pace whilst being updated with the latest discussions.
- **Search:** A simple way to search for keywords among every sent messages. Simply type a word in the search box in the upper-right corner to start looking.
- **Notifications:** Notifications are a very good way of letting the user know about items that need his attention. Regardless of his current working environment, notifications will make sure that the user will never miss important messages.

### III. Telegram

> A new era of messaging.

This application lets users exchange messages in a simple and effective way.

#### What's good about it?

Its interface allows the visualization of not only sent/received messages but also other relevant information for each message, such as its status or the remittee's name and photo.
It also offers a search bar and a menu with various other options.

![](https://i.imgur.com/OY1Anzm.jpg)

From its qualities, the following stand out:
- The names of the users visually stand out from the rest of the information, making it easier
to differentiate them from the rest of the text, facilitating the reading.
- One can access relevant message metadata such as last activity time and status without having to explicitly open those messages
- The UI spreads really nicely through the application window, and the boundaries of each section are well defined via colour combinations and backgrounds.
- The highlight colour that stands out when the user clicks some chat and the name/photo of the user associated with that chat make it really easy to "stay in the zone" (i.e. when minimizing and coming back, the user knows where he left off).

## Examples of Bad UI

### I. Complex (Digital) Forms

> Despite being one of the most important types of digital interaction, long/messy forms are often seen as very annoying.

Forms are a very difficult UI element to get right, especially when a lot of information is required. The responsible
developers should pay special attention to improving their forms and making them as usable as possible. At the end of the day, careful
design will have a huge impact on how fast and error-free the user provides the necessary information.

![](https://i.imgur.com/mESfSkf.png)

#### What are the problems?

When not carefully designed, different forms will suffer from different UI problems. The most common ones would be:

- **Multi-column layout:** Much more difficult to quickly scan the fields.
- **Wrong size of input fields:** The users may start to wonder if they correctly understood the label.
- **No Distinction between optional and required fields:** Specially for long forms, the less the user has to type, the better.

#### How can it be done better?

The most crucial (and arguably difficult) aspects of good form design come down to little visual cluttering, logical separation of
input fields and good hints/user-forgiving formatting. There have been several attempts at following these principles,
and I'd like to focus on one that I've stumbled across some time ago and find very unique. It's called [TypeForm](https://www.typeform.com):

![](https://i.imgur.com/WRIAKvb.png)

### II. Check Box *Clusters*
 
> Despite of being used alot in nowadays software, if they are not used carefully they can hamper users' interaction with the system.
 
Check Boxes are a very popular way to allow the user to choose beetween one or more atributes of a given system. However, there are certain details that the developer should care for while including them in his software. For example, when there is a lot of information for the user to choose from, check boxes may not always the best approach.

As the image bellow sugests, if we have a wide range of items to choose from, using check boxes can hamper users' capabilities to use the system, as well as providing a poorly user experience.

![](https://i.imgur.com/xeCNlaL.png)
Image sources: [SuperCook](http://www.supercook.com/#/recipes) and [MyFridgeFood](http://myfridgefood.com/)
 
#### What are the problems?
 
When using check boxes the developer should care about:

- **Item Quantity:** It makes it very hard for the users to find the options they are looking for, if there are a lot of check boxes from where they can choose from.
- **Positioning and Order:** It is also important to have a good check box positioning while maintaining some kind of order beetween them so they don't appear all mixed up around the screen, making it even harder for the user to navigate through the available options. 
 
#### How can it be done better?

Regarding the problems pointed out, check boxes are not a very good option to display a large number of data. Instead we should consider using a search box that uses a smart algorithm that can suggest the words as type them, making it easier and clean to the user to find/select what he needs.
 
![](https://i.imgur.com/8jPDbyl.png)

### III. RTP Play

This application allows users to follow live emissions of TV and radio, fully rewatch shows and access the RTP's programming. That being said, this interface's focus should be on letting the user search, filter and watch content with minimum effort.

![](https://i.imgur.com/kV8gfNH.png)

#### What are the problems?

- The colour choice isn't the best, considering that the colour blue is the less perceptible one to the human eye. Specifically, in the case of menu, mixing various tones of blue makes the reading even more difficult.
- The second menu could have its size reduced (or be more space-efficient), reducing those two sub-menus (by channel and by theme) to checkboxes.
- The menu icon could change when the menu is open, making it more clear that clicking on it again the second menu would be toggled off again.
- The space taken by each item of the results is badly optimised.
