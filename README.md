# MOBA
This project is about an application with a connection to a Z21 control center from roco. Communication takes place via UDP over the network. The application is able to be informed when a certain feedback point has been crossed.

This means that when a train crosses a certain track section, this is reported to the control center, which then sends this information to our application. Based on this message, various actions should now be triggered, such as a train announcement or a station announcement. E.g. Next stop, Bielefeld main station, exit in direction of travel on the right. Or entry at track 1 receives the RB 69.
