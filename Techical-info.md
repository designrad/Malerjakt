# Technical details
- Development language: React Native
- Code commenting: in English
- Platform: web app, iOS, Android
- Development environment: https://github.com/designrad/Malerjakt
- App name: Målerjakt
- App languages: 2, Norwegian and English

## Clickable prototype (coming later!):

- Home screen: image
- App icon:
- Camera: native UI
- Gallery: native UI
- History: image

## Notifications:
App needs to be able to notify of possible error situations, like:
  - no network
  - no geolocation available
  - no space on device
  - can't reach database
  - new version available
  - new version installed
  - submission period ended (extra feature)
  - image missing geolocation

## Homescreen, label, milestone
- visual desig
- visual elements extracted
- buttons for subpages (read more, camera, gallery, map)
- form for mailinglist

## Read more page
  - about the species
  - about the project
  - sponsors
  - website address with link
  - contact info (name, email)

## Register older photo /
  - open gallery
  - add comments
  - add geolocation
    - pin a location in device map app
  - send to database

## Database:
  - device or user info
  - image
  - geolocation
  - comment
  - switch: approved/rejected + username + timestamp

## Database Admin UI:
  - view images and sender info
  - browse and view images in large size
  - mark image as reject/approved
  - default mark: unchecked
  - delete message
  - create export file:
    - image geolocation as .geojson file
    - image link to file in img/
  - login/logout/forgot password

## User scenario 1:
Take image and send to database

## User scenario 2:
Select image from gallery and send to database

## User scenario 3:
Read more about the project/species

## User scenario 4:
View history/log page with image, date+time, geolocation

## User scenario 5:
Subscribe to email list

## User scenario 6 / Administrative use:
Browse and mark submitted images Correct, Incorrect, Other.

## User scenario 7 / Administrative use:
Download All/Correct/Incorrect/Other geolocations in a geojson (or other) file

## User scenario 8 / Administrative use:
View submitted smart phone details (used only to distinguish phone model and how many individual participants the project has). Any unique or "almost unique" information from the smart phone can be used.
