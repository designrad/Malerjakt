# Job proposal
To qualify, please send me a short plan, technical description and cost/time estimate how you would execute this project. Also, for any technical decisions (database, language, backend) please provide reason why that one was selected. I am interested in a re-usable architecture and dev stack, and appreciate a developer with not only appropriate skills, but also a technical sparring partner. Also, comment on any technical issues we might have during the development. For example, using native camera (iOS/Android), detecting geolocation in image, parsing geolocation form image in backend UI, issues since app used outside (no wifi), over-the-air update procedures, etc. I cannot blindly accept developers who only send hourly rate and amount without any plan. If you have a plan, then I know you actually read and understood the task. Thank you!

### Update 1:
App should be in testing before summer, and released early summer. The app will only be used during a 4-8 week period in the autumn 2017.

- Estimated amount of submissions: under 1000.
- Estimated amount of participants: under 100.


# THE APP:
Architecture and development of a mobile app, with a few simple scenarios:

- User scenario 1:
Take image with native camera, write comments, and send to database

- User scenario 2:
Select image from gallery and send to database

- User scenario 3:
Read more page: about the project/species

- User scenario 4:
View history/log page with image, date+time, geolocation

- User scenario 5:
Subscribe to email list

- User scenario 6 / Administrative use:
Browse and mark submitted images Correct, Incorrect, Other.

- User scenario 7 / Administrative use:
Download All/Correct/Incorrect/Other geolocations in a geojson (or other) file

- User scenario 8 / Administrative use:
View submitted smart phone details (used only to distinguish phone model and how many individual participants the project has). Any unique or "almost unique" information from the smart phone can be used.

Database Admin UI (this is very simple, we can use default db admin interface, to save time):
- view images and sender info
- browse and view images in large size
- mark image as reject/approved (or, just delete Incorrect images and keep Correct ones)
- default mark: unchecked
- delete message
- create export file:
- image geolocation as .geojson file
- image link to file in img/
- login/logout/forgot password
