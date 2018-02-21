# Code Notes

- Some modification could be made to the initial api call to prevent errors when an entry is returned without a corresponding image. It might be good to implement a placeholder image, I have filtered these out for the moment.
- The function sorting the individuals by last name was set to reverse the list by first name rather than order by last name.
- Made search box case insensitive.
- If there were more data, it may be desired to give ordering options to search results.
- Code could be restructured to use framework such as Redux to store information and logic, to reduce state changes in component.
