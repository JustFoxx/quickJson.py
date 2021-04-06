# quickJson.py
Easy version of using json in python

**How to install?**
download `quickJson.py` file and add to your project

**How o use?**
```py
 import quickJson

db = quickJson.File("file.json") #without this you cant run project, this set file to edit

db.set("player.name","Adam") #this set variable in json

db.add("player.feed",1) #this add thing to variable

db.get("player.name") #with this you can get thing from variable in json

db.delete("player.items") #delete variable from json
