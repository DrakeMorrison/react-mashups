# React Mashups

## Mockup
![Mockup](https://github.com/nss-nightclass-projects/react-mashups/blob/master/mashup_mockup.png)

## Requirements
- As a user, I want to be able to see all my animal mashups on page load.
- As a user, I want to be able to submit a new animal mashup using a form. When I submit the form, I want to see my new animal mashup immediately on the page.

## Technical Requirements
- Use Firebase to hold the mashup data
- Use React
- With [axios](https://github.com/axios/axios#example), make a GET request to firebase to get your mashups
- With [axios](https://github.com/axios/axios#example), make a POST request to post a new mashup to firebase

## Seed Data
```json
{
  "mashups": {
    "mashup1": {
      "name": "horsrog",
      "imgUrl": "https://www.pleated-jeans.com/wp-content/uploads/2013/10/Animal-Mashups19-1.jpg",
      "description": "Makes a good pet. May hop away."
    },
    "mashup2": {
      "name": "sparrrel",
      "imgUrl": "https://www.pleated-jeans.com/wp-content/uploads/2013/10/Animal-Mashups15-1.jpg",
      "description": "You should hear this one sing."
    },
    "mashup3": {
      "name": "b-eagal",
      "imgUrl": "https://www.symbiancreate.co.uk/wp-content/uploads/2017/03/bald-beagle.jpg",
      "description": "The b-eagle is a breed of small hound that is similar in appearance to the much larger foxhound, crossed with the spirit of America."
    },
    "mashup4": {
      "name": "dird",
      "imgUrl": "https://pbs.twimg.com/media/BWaop-FIgAAaIwH.jpg",
      "description": "It has a mighty bite."
    },
    "mashup5": {
      "name": "puffaroo",
      "imgUrl": "https://i.pinimg.com/originals/eb/1b/f2/eb1bf20520c377434c32586c1da4d566.jpg",
      "description": "Great for birthday parties."
    }
  }
}
```
