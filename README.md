mm_rain = 0

rainfall = {
  "Hamilton": "56",
  "Oakland": "74",
  "binbrook":mm_rain,
  "Toronto": "92",
  "ottawa": "36"
}

mm_rain = input("mm of rain:")
citychoice = input("enter city name:")

x = rainfall.get(citychoice) + mm_rain

print(x)

