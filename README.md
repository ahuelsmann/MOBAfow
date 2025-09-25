# MOBAflow
The program in this project communicates bidirectionally with a Z21 from Roco via UDP.  The app receives a notification when certain feedback points (on the tracks) are passed.
This means that when a train passes a route on the track, this is reported to the control station, which then forwards this information to the App. 
Based on this message, various actions could be triggered on the windows based pc system, such as a train announcement or a station announcement. For example: Next stop, Bielefeld Central Station, exit on the right side in direction of travel.
Of course, part of an action could also be to send digital commands back.

## Current situation
Work is currently ongoing on an MVP level in Azure DevOps. Once the project with minimal features is complete, it will be published soon here on GitHub.
The project is set up regarding best practices. WinUI 3 is used for the UI. The MVVM pattern is used, as well dependency injection. All view models are stored in a separate class library so that any UI framework could be used later on.
