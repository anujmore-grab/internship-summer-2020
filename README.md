# Grab Internship for Software Engineering (Fullstack)

Hi, congratulations on getting shortlisted for Software Engineering (Fullstack) Internship at Grab. As a programming exercise for the first coding round, please solve the following question.

## Rules first!

* The exercise consists of a frontend assignment. You can use any JavaScript/CSS frameworks of your choice (Personally, I would recommend a modern JS framework like React or Angular)
* Use SCM of some kind (like Git) to track your project
* The expected time to be spent on this exercise is *not more than 6 hours* from understanding the problem to design to implementation, though you can start on the task whenever you please
* Zip the project and email it with instructions on how to run the project in the README within *one week* of getting this email (It is recommended to work on the assignment without uploading to SCM hosting websites or keeping the repo private until submission)
* Document any learnings that you get from this project and add it to the final README

## Criteria

You will be judged by clarity and correctness of your solution, documentation, design and mobile-readiness, and extensibility.
Additional points for caching, and using a solution for state management.

## Assignment

Star Wars API ([SWAPI](https://swapi.co/documentation)) is a free-to-use API that we are going to use to create our tiny web app. Prepare a single page application that displays information about the resources that are provided in the API.

It is expected for you to create a `:resource` (or list) page (eg. showing information on https://swapi.co/api/people/) and a `:resource/:id` (or instance) page (eg. https://swapi.co/api/people/1/). It is also expected for the ID page to link to other IDs. (eg. /api/people/1/ should link to relevant "film", "species", "vehicles" resources)

There are many resources, but making a details page for `people`, `planets`, and `starships` with proper links between them should be enough.

## Bonus

We know displaying the textual information can make the pages look a bit bland. To solve this, you can use the Google Images API by [SerpAPI](https://serpapi.com/images-results#gsc.tab=0) to fetch images that can be inserted in the corresponding `:resource/:id` views.
