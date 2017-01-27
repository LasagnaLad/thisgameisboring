# thisgameisboring

print("Hello, Welcome to a boring text-based game!  Don't play this unless you want to be bored! Are you ready to get started? (please type 'yes' or 'no')")
print()
answer=str(input())
discovery_items=['a lighter', 'a gun', 'a journal with the year 1953 on the cover', 'a can of food', 'a cell phone', 'a cell phone battery', 'a shoe', 'a wedding ring', 'a newspaper', 'a rusty old sword', 'a pen', 'a book on linguistics and crytography']
if answer=="yes":
    print()
    print("Alright, let's go!")
    print()
    print("What's your name, stranger?")
    name = str(input())
    print("Well... Nice to meet you, " + name + "!")
    print("Here's the problem... you're stuck somewhere in or around a house.  It's a large three story house.  Unfortunately, you don't know which floor you're on right now and the only way you can tell which room you are in is by looking at the room number (rooms 1-15).  What room number is showing on the door?")
    print()
    room=int(input())
    if room==1:
      print("You are in the first floor bathroom.  It's old.  There is a toilet, shower/bath, and a vanity with a sink in this room.")
    elif room==2:
      print("You are in the kitchen on the first floor.  The kitchen features a large brick oven, a sink, a 4 burner gas stove, an old white fridge, and a table set for 3 with a candle lit in the middle.")
    elif room==3: 
      print("You are in the library on the first floor.  There are several books on the shelves, but most look to be so old that they would fall apart when so much as touched.")
    elif room==4:
      print("You are in the foyer on the first floor.  This is a wide open room with nothing but a lamp in the corner, 2 wicker chairs, and an endtable in the middle of the chairs.")
    elif room==5:
      print("You are on the first floor stair landing, at the end of a long hallway.  The hallway seems to be decorated with pictures from long ago.")
    elif room==6:
      print("You find yourself standing in an empty room.  This room is so empty that it makes your head spin.  There is a door and not much else to look at, aside from four walls, a tiled floor and a ceiling with a light in the middle.")
    elif room==7:
      print("You find yourself in an old dusty office.  This office holds nothing new.  There is a desk, a large leather office chair, file cabinets, and a long table stacked with boxes.  On the wall there are a bunch of newspaper clippings connected by yarn and a map with connecting lines drawn on it.")
    elif room==8:
      print("You are staring at a reflection of yourself in a mirror.  You look around and see that you are in a large master suite.  The suite has a large bed, two dressers on each side of the bed, a desk, a small sitting area, and a bathroom attached that features a large clawfoot bathtub, a toilet, a long counter, and a large sink.  There is a closet in this room, and the closet door is open.  There is nothing in the closet, aside from a hanger that was left hanging.")
    elif room==9:
      print("You are in a small bedroom that is very lightly furnished.  All you see in the room is a small twin sized bed and a dresser.")
    elif room==10:
      print("You find yourself on the second floor landing of the stairs, at the end of a long hallway.")
    elif room==11:
      print("You find yourself on the third floor landing of the stairs.  You are at end of a long dark hallway.  This hallway has nothing on the walls.  There are two rooms on the left and two rooms on the right.")
    elif room==12:
      print("You find yourself in a large empty ballroom.  It seems as though there was a party in here long ago, but the decorations are still up, as though whoever had the party left in a hurry and didn't come back to clean up.")
    elif room==13:
      print("You are in a kitchen.  You hear a rumbling noise.  It's your stomach.  You're hungry.  This kitchen is small.  There is a sink, a fridge, an oven/stove, a row of cabinets along one wall, and a table. ")
    elif room==14:
      print("You're in a large sitting room.  There are couches and chairs sitting around a coffee table.  These are all covered with sheets.  There really isn't much else in this room.")
    elif room==15: 
      print("You are standing on a large terrace overlooking a wooded valley.  The terrace has plants growing everywhere.  This may have once been a beautiful place to sip some coffee and enjoy the view, but now it is so choked with vegetation that it is impossible to enjoy much.")
    else: 
      print("You wake up beneath a tree in the backyard of a very large house.  There is a tall perimeter fence around the house.  The yard is full of weeds and tall grass.  It appears as though this yard could have once been a wonderfully manicured lawn, but now it is something of an eyesore.")
    
    
else:
    print("Too bad.  You're missing out.")
