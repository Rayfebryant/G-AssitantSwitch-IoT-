# G-Assistant Switch

# Hardware Requirements
ESP8266 dev board

Relay Module (5v)

Jumper Cables

Smartphone with google assistant

# Software Requirements
Account at IFTT 

Account at Adafruit IO

Arduino IDE

# Setting up Adafruit IO
Once you login, choose feeds and make new feeds, click feeds > create a new feed. 

When finished creating a feed now switch to the Dashboard menu and do the same thing as creating a feed.

Now click on + to add a block here we using toogle block.

Now click on key icon to see your AIO Key and AIO Username

# Setting up IFTTT
Once you login, click on "My Applets" and then click on "New Applet"

On the page you will see a heading "If this then that", here click on "this"

In the search box type "Google" and select the "Google Assistant"

Now select the first trigger "Say a simple phrase"

Here we will add some phases we want the assistant to recognize and do a task, I have used "Turn on relay 1" as the trigger, below there are two more optional where we can add the phrases in different forms.

Finally in the last field we have to add a response phrase which the google assistant will use to give a replay. I have use "Switch on"

Now click on "Create Trigger" to finalize the trigger.

Now we have to select "that". Here we will create what happens when the trigger is set.

In the search bar type "Adafruit" and then choose send data to adafruit IO to connect our IFTTT with Adafruit IO.

Choose your feed and set the data to save. here i made two applets which one is save on data and the other one is save off data. 
