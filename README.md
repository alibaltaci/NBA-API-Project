# NBA-API-Project!
![NBA-API](https://user-images.githubusercontent.com/71599944/160829272-27a45eb6-9e05-410c-a89a-1d8e8f988ebb.png)

# Free NBA API Project Overview

Unofficial NBA API for Historical NBA Data

**Free NBA API URL:** https://rapidapi.com/theapiguy/api/free-nba/

**Fetch:**

2 different fetch methods were used in this project.

  1 - Player Name: This endpoint retrieves all players from all seasons.

  2 - Player ID: This endpoint retrieves a specific player.


# Example Response

**Player Name**

```
  "data":[
    {
      "id":237,
      "first_name":"LeBron",
      "last_name":"James",
      "position":"F",
      "team":{
        "id":14,
        "abbreviation":"LAL",
        "city":"Los Angeles",
        "conference":"West",
        "division":"Pacific",
        "full_name":"Los Angeles Lakers",
        "name":"Lakers"
      }
    }
    ...
 ],
 "meta": {
    "total_pages": 50,
    "current_page": 1,
    "next_page": 2,
    "per_page": 25,
    "total_count": 9999
  }
}
```
**Player ID**

```
{
  {
    "id":237,
    "first_name":"LeBron",
    "last_name":"James",
    "position":"F",
    "team":{
      "id":14,
      "abbreviation":"LAL",
      "city":"Los Angeles",
      "conference":"West",
      "division":"Pacific",
      "full_name":"Los Angeles Lakers",
      "name":"Lakers"
    }
  }
}
```
# NBA Color Palette
![blue](https://user-images.githubusercontent.com/71599944/160837040-9d461f7a-1898-44af-8320-a2026b728d34.png) 

Name: Dark Cornflower Blue

Hex: #17408B

RGB: (23, 64, 139)

CMYK: 0.834, 0.539, 0, 0.454


![white](https://user-images.githubusercontent.com/71599944/160837341-980a0360-6e6b-442e-8949-f610f93a609b.png)

Name: White

Hex: #FFFFFF

RGB: (255, 255, 255)

CMYK: 0, 0, 0, 0

![red](https://user-images.githubusercontent.com/71599944/160837372-9799ab04-5557-42f4-afcd-12e663a559d3.png)

Name: Philippine Red

Hex: #C9082A

RGB: (201, 8, 42)

CMYK: 0, 0.960, 0.791, 0.211
