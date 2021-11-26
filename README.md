# Novo Home Assistant (252 Term Project) :houses:

## Installation: :computer:
1. Clone my repo
2. Be sure to have **Python** (`brew install python`), **Rasa** (`pip install rasa[full]`), and **Keras Tensorflow** installed (`pip install tensorflow`)
3. Navigate (`cd`) to the cloned repository.
4. Run `rasa run actions` and leave this running.
5. Open a new terminal window and run `rasa shell`
6. Chat with the bot! (A full list of commands to interact with the bot is seen below).



## Short Demo: :link:
#### 1) Changing the color of the lights:


![change_lights_example](https://github.com/r1cummings/252TermProject-NovoHomeAssistant/blob/main/references/change_lights_example.gif)

#### 2) Adding to your shopping list:

![shopping_list_example](https://github.com/r1cummings/252TermProject-NovoHomeAssistant/blob/main/references/shopping_list_example.gif)

## Suggested Conversation Flows / Story Lines:
##### *Multi-Turn conversations:*
1) **Type: `Hi`** \
   Bot will respond: `Hi! How can I help you?` \
   **Type: `Turn the lights on`** \
   Bot will respond: `Turning lights on!` \
   **Type: `Change the color of the lights`** \
   Bot will respond: `What color do you want the lights to be?` \
   **Type: `Red`** \
   Bot will respond: `The lights are now Red!` 
   
   <br>

2) **Type: `Hi`** \
   Bot will respond: `Hi! How can I help you?` \
   **Type: `Add to my shopping list`** \
   Bot will respond: `Okay, what would you like to add to your shopping list?` \
   **Type: `Steak`** \
   Bot will respond: `Okay, I'll add Steak to your list.` \
   **Type: `How many items are on my shopping list?`** \
   Bot will respond: `There are 1 item(s) on your shopping list.` \
   **Type: `Add to my shopping list`** \
   Bot will respond: `Okay, what would you like to add to your shopping list?` \
   **Type: `Chicken`** \
   Bot will respond: `Okay, I'll add Chicken to your list.` \
   **Type: `How many items are on my shopping list?`** \
   Bot will respond: `There are 2 item(s) on your shopping list.` \
    <br>
3) **Type: `Hi`** \
   Bot will respond: `Hi! How can I help you?` \
   **Type: `TV on`** \
   Bot will respond: `The TV is now on. Enjoy!` \
   **Type: `Change the channel on the tv`** \
   Bot will respond: `What channel would you like me to change it to?` \
   **Type: `ESPN`** \
   Bot will respond: `The TV is now set for ESPN!` \
   <br>

4) **Type: `Hi`** \
   Bot will respond: `Hi! How can I help you?` \
   **Type: `Set a timer`** \
   Bot will respond: `How long would you like me to set the timer for?` \
   **Type: `10 minutes `** \
   Bot will respond: `10 minutes and counting!`



##### *Single way conversations:*
1) 
   **Type: `Hi`** \
   Bot will respond: `Hi! How can I help you?` \
   **Type: `Turn the crypto miners on`** \
   Bot will respond: `The crypto miners are now on!` \
    <br>
2) 
   **Type: `Hi`** \
   Bot will respond: `Hi! How can I help you?` \
   **Type: `Tell the vacuum to go home`** \
   Bot will respond: `The vacuum has stopped and is returning to it's charging station.` \
    <br>
3) 
   **Type: `Hi`** \
   Bot will respond: `Hi! How can I help you?` \
   **Type: `Turn the pool heater on`** \
   Bot will respond: `The pool heater is now on. Please wait about 20 minutes for it to be fully warmed up!` \
    <br>
4) 
   **Type: `Hi`** \
   Bot will respond: `Hi! How can I help you?` \
   **Type: `How long is my drive to work?`** \
   Bot will respond: `Your drive to work will take about 35 minutes, with slight traffic on Palmdale Blvd adding 3 minutes to your drive.` \
    <br>
5) 
   **Type: `Hi`** \
   Bot will respond: `Hi! How can I help you?` \
   **Type: `What time is it?`** \
   Bot will respond with current date and time. \
    <br>
6) 
   **Type: `Hi`** \
   Bot will respond: `Hi! How can I help you?` \
   **Type: `Feed the dogs`** \
   Bot will respond: `Okay, I'll feed the dogs.` 

###### ***BONUS***
   **Type: `Hi`** \
   Bot will respond: `Hi! How can I help you?` \
   **Type: `Are you a robot?`** \
   Bot will respond: `Of course not! I'm definitely a human. Beep Beep Boop. Umm, sorry.`


## Full List of Commands: 
###### *Ellipsis(...) here is representing phrases that are along the lines of what is being shown.*
###### *Multi turn conversations are marked with an exclamation (:exclamation: )*

`Alarm Set`:
- "Turn on the alarm"
- "Set the alarm"
- ...

`Pool Heater`:
- "Turn on the pool"
- "Pool on"
- ...

`Open blinds`:
- "Open the blinds"
- "Can you open the blinds?"
- ...

`Close blinds`:
- "Close the blinds"
- "Please close the blinds"
- ...
  
`Lights on`:
- "Turn on the lights"
- "Lights on"
- ...

`Lights off`:
- "Turn off the lights"
- "Lights off"
- ...

`Change Light color`:
- "I want to change the color of the lights" :exclamation:
- "Change light color" :exclamation:
- ...

`Vacuum on`:
- "Tell the vacuum to clean"
- "Vacuum on"
- ...

`Vacuum off`:
- "Tell the vacuum to go home"
- "vacuum off"
- ...

`Miners on`:
- "Turn on the crypto miners"
- "Crypto on"
- ...

`Miners off`:
- "Turn off the crypto miners"
- "Crypto off"
- ...

`Feed Dogs`
- "Feed the dogs"
- "Can you feed the dogs?"
- ...

`AC on`:
- "Turn the AC on"
- "AC on"
- ...

`AC off`:
- "Turn the AC off"
- "AC off"
- ...

`Heater on`:
- "Turn the heater on"
- "Heater on"
- ...

`Heater off`:
- "Turn the heater off"
- "Heater off"
- ...

`Lock Door`:
- "Lock the door"
- ...

`Unlock Door`:
- "Unlock the door"
- ...

`Fan on`:
- "Turn on the fan"
- "Fan on"
- ...

`Fan off`:
- "Turn off the fan"
- "Fan off"
- ...

`Weather`:
- "Whats the temperature outside?"
- "weather today"
- ...

`Drive time`:
- "Check the traffic today"
- "How long is my drive to work?"
- ...

`Timer`:
- "Please set a timer"
- "Set a timer"
- ...

`Washer on`:
- "Turn on the washer"
- "Washer on"
- ...

`Washer off`:
- "Turn off the washer"
- "Washer off"
- ...

`Dryer on`:
- "Turn on the dryer"
- "Dryer on"
- ...

`Dryer off`:
- "Turn off the dryer"
- "Dryer off"
- ...

`Music on`:
- "Turn on the radio"
- "Play music"
- ...

`Music off`:
- "Turn off the radio"
- "Stop the music"
- "Radio off"
- ...

`TV on`:
- "Turn on the tv"
- "TV on"
- ...

`TV off`:
- "Turn off the tv"
- "TV off"
- "Change the channel on the tv" :exclamation:
- ...

`TV Change Channel`:
- "Change the channel on the tv" :exclamation:
- ...

`Shopping`:
- "Add to my shopping list" :exclamation:
- "How many items are on my shopping list?"
- ...

`Time`
- "What time is it?"
- "Tell me the time"
- ...

## Bonus Command(s):

- `Are you a robot?`
