## Swift UI Tutorial [Swift UI Tutorial](https://developer.apple.com/tutorials/app-dev-training/getting-started)

- **Using Stacks to Arrange Views** [Using Stacks to Arrange Views](https://developer.apple.com/tutorials/app-dev-training/using-stacks-to-arrange-views) tutorial.

- **Creating a CardView** [Creating a CardView](https://developer.apple.com/tutorials/app-dev-training/creating-a-cardview) tutorial.

- **Displaying Data in a List** [Displaying Data in a List](https://developer.apple.com/tutorials/app-dev-training/displaying-data-in-a-list) tutorial.

- **Creating a Navigation Hierarchy** [Creating a Navigation Hierarchy](https://developer.apple.com/tutorials/app-dev-training/creating-a-navigation-hierarchy) tutorial.

- **Creating the Edit View** [Creating the Edit View](https://developer.apple.com/tutorials/app-dev-training/creating-the-edit-view) tutorial.

- **Passing Data With Bindings** [Passing Data With Bindings](https://developer.apple.com/tutorials/app-dev-training/passing-data-with-bindings) tutorial.

- **Managing State and Life Cycle** [Managing State and Life Cycle](https://developer.apple.com/tutorials/app-dev-training/managing-state-and-life-cycle) tutorial.

- **Updating App Data** [Updating App Data](https://developer.apple.com/tutorials/app-dev-training/updating-app-data) tutorial.

- **Persisting Data** [Persisting Data](https://developer.apple.com/tutorials/app-dev-training/persisting-data) tutorial.

- **Drawing the Timer View** [Drawing the Timer View](https://developer.apple.com/tutorials/app-dev-training/drawing-the-timer-view) tutorial.

- **Transcribing Speech to Text** [Transcribing Speech to Text](https://developer.apple.com/tutorials/app-dev-training/transcribing-speech-to-text) tutorial.

## Tour of the App

Many software engineering teams use daily meetings, known as scrums, to plan their work for the day. Scrums are short meetings where each attendee discusses what they accomplished yesterday, what they are working on today, and any obstacles that might impact their work.

This course guides you through the development of Scrumdinger, an iOS app that helps users manage their daily scrums. To help keep scrums short and focused, Scrumdinger uses visual and audio cues to indicate when and how long each attendee should speak. The app also displays a progress view that shows the time remaining in the meeting and creates a transcript that users can refer to later.

### Scrum List

The main screen of the app displays a summary of each of the user’s daily scrums. Users can tap a row in the list to view the details of a scrum or create a new scrum by tapping the Add (+) button in the navigation bar.
Screenshot of list of scrums under Daily Scrums heading

![Scrum List](/Images//ScrumList.png?raw=true "Scrum List")

### Scrum Detail and Edit

The detail view shows more information about a scrum, including the name of each attendee and a list of previous meetings. Users can modify any of the scrum’s attributes by tapping the Edit button. Tapping the Start Meeting button at the top of the list starts a new meeting timer.
Screenshot of scrum details shown in grouped lists, including Meeting info, Attendees, and History

![Scrum Detail and Edit](/Images/ScrumDetailandEdit.png?raw=true "Scrum Detail and Edit")

### Meeting Timer

The progress bar at the top of the meeting timer shows the elapsed and remaining time for the meeting. The app displays the name of the current speaker in the center of the screen and a button to advance to the next speaker at the bottom of the screen.

Each attendee is represented by a segment in a circular progress ring. When an attendee’s time is up, Scrumdinger plays a “ding” sound and adds a new segment to the ring. The meeting is over when the ring is full.

![Meeting Timer](/Images/MeetingTimer.png?raw=true "Meeting Timer")
