import itertools

minecraftSword = {
  "Diamond" : {
    "damage": "7 attack damage",
    "attack speed":"1.6 attack speed",
    "durability":"1561"
  },

  "Iron" : {
    "damage":"6 attack damage",
    "attack speed":"1.6 attack speed",
    "durability":"250"
  },

  "Wooden" : {
    "damage":"4 attack damage",
    "attack speed":"1.6 attack speed",
    "durability":"59"
  },

  "Stone" : {
    "damage":"5 attack damage",
    "attack speed":"1.6 attack speed",
    "durability":"131"
  },

  "Golden" : {
    "damage":"4 attack damage",
    "attack speed":"1.6 attack speed",
    "durability":"32"
  },

  "Netherite" : {
    "damage":"8 attack damage",
    "attack speed":"1.6 attack speed",
    "Durability":"2031"
  },

  
}
results = input("_____ of a type of sword: ")
if results == "Attack Speed":
  def getAttack():
    LookupAtk = input("Attack Speed of _____ Sword: ")
    y = minecraftSword[LookupAtk]
    sliceAtk = dict(itertools.islice(y.items(),1,2))
    print(sliceAtk)
  
  getAttack()

elif results == "Attack Damage":

  def getspeed():
    LookUpDam = input("Attack Damage of _____ Sword: ")
    x = minecraftSword[LookUpDam]
    slicedDam = dict(itertools.islice(x.items(), 0 ,1)) 
    print(slicedDam)
    
  getspeed()
  
elif results == "Durability":
  def getDurablity():
    LookupAtk = input("Durability of _____ Sword: ")
    z = minecraftSword[LookupAtk]
    sliceAtk = dict(itertools.islice(z.items(),2,3))
    print(sliceAtk)
  
  getDurablity()

else:
  print("Stats Unavailable")
