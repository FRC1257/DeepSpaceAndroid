# Team 1257 Scouting App: 2019
This app, by FRC Team 1257 (Parallel Universe) is meant to be used for scouting for the 2019 FRC game of Destination: Deep Space.

Planned Layout:
ScrollView [nav]
 TextView [onclick -> instructions visible]
 TextView [onclick -> objective visible]
 TextView [onclick -> pit visible]
 TextView [onclick -> send visible]
 TextView [onclick -> settings visible]
 
ScrollView [instructions] - already exists

ScrollView [objective] - already exists

ScrollView [pit] - already exists

ScrollView [send] - 
 LinearLayout [horizontal]
  Button [onclick -> accept connections]
  Button [onclick -> read file]
  Button [onclick -> clear text box]
  Button [onclick -> reset]
 TextEditInputLayout - box for sending and receiving data
 LinearLayout [horizontal]
  Button [onclick -> send objective]
  Button [onclick -> send pit]

ScrollView [settings] - 
 LinearLayout [horizontal]
  EditText - objective prefilled link
  Button [onclick -> set objective link]
 LinearLayout [horizontal]
  EditText - pit prefilled link
  Button [onclick -> set objective link]
 Spinner - set scouting robot
 
