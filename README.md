# piPlantPrecipitation 🌱

### Members:
>Reegan Le,
Shivam Shah,
Maria Diaz,
Brendan Albert

### Statement of Purpose
>For busy people who can’t water their plants, piPlantPrecipitation APP to the rescue!

### Detailed Description

First Stage
- Hardware moisture sensor connected to Arduino or Raspberry Pi should activate water pump

Second Stage
- To be decided when we get there

Third Stage
- To be decided when we get there

Nice to haves if time permits:
- Gather temperature and humidity data


### Equipment:
- jumper wires
- raspberry pi / arduino
- breadboard
- aquarium tubing
- water pump(s)


### List of sensors:
- Moisture sensor (prongy boi)

Nice to haves:
- light intensity sensor
- DHT11 (temperature & humidity)

### UI:
- Cute pixel art
- mint green, pink

### Responsibilities:

Mars
- Code
- Hardware (Raspberry Pi version)
- Methods to connect everything, read data

Shiv
- Code
- Hardware, mainly electrical help
- Database work

Reeg
- Code
- Hardware (Arduino version)

Brandy
- Code
- UI and art assets



### Brain Stormings:
- User should be able to enter optimum data
- Comparison of optimal vs sensor, accept or reject
- Water schedule super important, for instance, orchids should not be watered more than 2x/week
- 5 points of data to determine optimal data
- watering categories / sunlight categories


### How to use Git and GitHub
##### Getting Started

###### Step 1, Make a new directory && make it your current directory, via terminal, to work on the project.
`$ mkdir piPlantPrecipitation && cd piPlantPrecipitation`

###### Step 2, Clone this github repo
`$ git clone https://github.com/brendanAlbert/piPlantPrecipitation.git`

###### Step 3, That's it!  You now have a cloned version of everything in the project at the moment.

##### How to add and commit changes

###### Check status
`$ git status`

- If there are no changes since last commit, or if you haven't commited yet, it will say so.
- If there are changes, but they have not been committed, it shows these files name's in red text.
- If there are changes, and they have been committed, it shows these files name's in green text.

###### Add a file
- you can add individual files but for our purposes we just want to add everything that has been changed
- so use the '.' to represent all files

`$ git add .`

###### Commit added files
`$ git commit -m 'Add a short message here in these quotes about what changes were made.'`

###### Push committed files up to GitHub
`$ git push`
