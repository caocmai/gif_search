### How To Run Flask Appilcation

```bash
export FLASK_ENV=development
flask run
```


### Division of Labor
[Trello Board](https://trello.com/b/TGQ3SeYq/gifsearch) - Board is public anyone can view




### Requirments
- [x] The page must use templates
- [x] The page must display GIFs (10 at the most)
- [x] GIFs should appear in a single vertical list
- [x] GIFs should appear in a single vertical list
- [x] Below the title there should be a search bar with a “Search” button near it (placement up to you, but needs to be on one side of the bar)
- [x] Users should be able to type a string into the search bar, press the search button, and be shown up to 10 GIFs related to the search query
- [x] GIFs should be displayed on a fresh load of the page, i.e. before a query has even been typed.
- [x] GIFs should only update once a user has pressed the “Search” button
- [X] If no GIFs could be found for the search term, display an error message saying that no GIFs could be found, and to try another search quer
- [ ] The following elements should have some custom styling (i.e. CSS rules) added to them:
    1. Page Title
    2. Search Bar
    3. Search item
- [X] All code must be commented with a description of what the code is doing, expected input, and expected output


### Stretch Goals
- [x] Add a gitignore file and edit it so that “.DS_Store” and “.env” won’t get tracked in Git. What else shouldn't be tracked?
- [ ] Center-align everything on the page
- [x] Display the GIFs in a grid instead of a list
- [x] [Add a button that displays the top 10 trending GIFs on Tenor](https://tenor.com/gifapi/documentation#endpoints-trendinggifs)
- [ ] [Add a button that displays 10 random GIFs on Tenor](https://tenor.com/gifapi/documentation#endpoints-random)
- [ ] Type-ahead: as the user types in the search box, the page is reloading the gifs to match the search query in real time (no longer needing to click the search button)

### Rubric
[Project rubirc here](https://docs.google.com/document/d/1u8zn_w9kQceK1y0f0F6QEWWgP8T7KRsQvQOIvlzyMi0/edit)


### Resources

You may find the following resources helpful in your development process:

1. [Tenor API Documentation](https://tenor.com/gifapi/documentation) - useful for understanding which URL we want to visit in order to make an API request for GIFs
2. [BEW 1.1 Lesson on Flask](https://make-school-courses.github.io/BEW-1.1-RESTful-and-Resourceful-MVC-Architecture/#/./Lessons/03-Intro-to-Flask/README)
3. [BEW 1.1 Lesson on Templates](https://make-school-courses.github.io/BEW-1.1-RESTful-and-Resourceful-MVC-Architecture/#/./Lessons/04-Flask-Templating/README)
4. [BEW 1.1 Lesson on APIs](https://make-school-courses.github.io/BEW-1.1-RESTful-and-Resourceful-MVC-Architecture/#/./Lessons/05-URLs-HTTP-REST-and-Reading-Errors/README)
# gif_search
