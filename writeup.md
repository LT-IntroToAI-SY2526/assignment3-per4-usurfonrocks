# Assignment 3 - Write UP

## Description
This assignment completes our movie chatbot system by implementing action functions that query our movie database and building a natural language interface. You implemented functions to search for movies by year, director, and actors, as well as the core search system that matches user queries to appropriate database operations. This builds directly on the pattern matching work from Assignment 2 to create a functional conversational AI system.

## What to complete
1. Complete all action functions in `a3.py` (title_by_year, title_by_year_range, etc.)
2. Implement the `search_pa_list` function to handle pattern matching and responses  
3. Add at least one new movie to the database with proper formatting
4. Create a new pattern/action pair and add it to the pa_list
5. Ensure all provided assert statements pass
6. Complete the reflection questions below
7. Push your code to github for grading

## Reflection Questions

1. What are some key programming concepts or techniques that you learned while completing this assignment?
 I learned how to work with different data types, I also learned how to switch from numbers to strings. I was also able to find the year and date using integers, but when i was looking for the movie titles and directors I had to call a string. I also learned how to write functions that search through lists of dictionaries, and how to return results based on user input. This helped me understand more about conditionals, loops, and how to structure code for specific tasks.


2. How does the overall movie chatbot system work? Explain the flow from when a user types a query to when they receive an answer.
When someone types in the key words, the chatbot then responds with the correct output after identifying what you typed in. When a user types something like "What movies came out in 2010?" the program compares this input to patterns defined in the pa_list. Once a pattern matches, the corresponding action function is called.


3. What are some real-world applications where this type of pattern-matching chatbot system could be useful? How might you extend or improve this system for practical use? It can be really helpful in many areas, such as customer service where it can quickly answer common questions, online shopping to help people find exactly what they want, or to guide people with appointment bookings for anything. Also I’d add some natural language processing so it can understand different ways people ask questions, fix typos more easily.