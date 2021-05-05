============================ Multi Theft Auto San andreas Native UI V2.1 Beta =============================

Created By : Ş¢໐໐๓คคli #7395

Discord Server : https://discord.gg/GeVnaNcSbb

Scripted By : Lua

Youtube : https://www.youtube.com/channel/UCs8fIJ_a0J-COQzqWB8THJg

------------------------------------------------------- Functions -------------------------------

[Client_Side]

int CreatePool(string WindowTitle = "NativeUI", string WindowDescription "My Window" [, string backgroundDestination = "NORMALE", bool useBackSpaceFunction false ] )

#WindowTitle : the title of the menu 

#WindowDescription : the blue text in the 2eme rectangle 

#Destination : the title background 

#useBackSpaceFunction : true = whene player click backspace the window wil be closed automatique

return window id 

[Client_Side]

setVisible(int windowID, bool visible)
 
#windowID : the index of the window will be invisibled or visibled

#visible : the value of the visiblity 

[Client_Side]

int addTab(int windowID, string tabType, string tabText [, string tabEvent, table selectTable ])

#windowID : id of parent window 

#tabType : "Button" | "Check" | "Select"

#tabText : text in the tab 

#tabEvent : the event will be assign in it will enter event handled 

#selectTable : (only with "Select" type !) the elements in the select tab 

#DeletePool 






