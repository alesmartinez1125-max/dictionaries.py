# dictionaries.pyusing I will create a list of interests and use different methods to manipulate the items in the dictioary created 

favorites = {'games':'Tekken', 'anime':'Bleach', ''music':'rap'}

# I will start off invoking a part of the dictionary I will edit to show a before, and then edit, and invoke once more to show the change 

favorites.get('games')
  output 'Tekken'

favorites['games'] = 'GOW'
favorites['games']
  output 'GOW'

# Next I will add a whole new item, and use popitem to delete it

favorites['comics'] = 'Batman'
  output 'comics':'Batman'

# Finally I will remove a specific item using the pop method 

favorites.pop('anime')
  output 'Bleach'
  


