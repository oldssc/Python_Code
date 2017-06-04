people={
   'Alan':{
       'location':'China',
       'height':"5'11",
       'favorite_color':'red',
   },
   'Johnny':{
       'location':'Barrington',
       'height':"5'8",
       'favorite_color':'blue'
   },
   'Mike':{
       'location':'Barrington',
       'height':"6'1",
       'favorite_color':'yellow'
   }
}
for name, value in people.items():
   print(name+"'s info are:\n")
   print("Location is: "+value['location'])
   print("height is: "+value['height'])
   print("favorite color is: "+value['favorite_color'])
