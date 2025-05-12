## [Project brief](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Structuring_planet_data#project_brief)

You are working at a school; currently your students are studying the planets of our solar system, and you want to provide them with an easy-to-follow set of data to look up facts and figures about the planets. An HTML data table would be ideal — you need to take the raw data you have available and turn it into a table, following the steps below.

### [Steps to complete](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Structuring_planet_data#steps_to_complete)

The following steps describe what you need to do to complete the table example. All the data you'll need is contained in the `plain.txt` file. If you have trouble visualizing the data, look at the image attached, or try drawing a diagram.

1. Open your copy of `index.html`, and start the table off by giving it an outer container, a table header, and a table body. You don't need a table footer for this example.
2. Add the provided caption to your table.
3. Add a row to the table header containing all the column headers.
4. Create all the content rows inside the table body, remembering to make all the row headings into headings semantically.
5. Ensure all the content is placed into the right cells — in the raw data, each row of planet data is shown next to its associated planet.
6. Add attributes to make the row and column headers unambiguously associated with the rows, columns, or rowgroups that they act as headings for.
7. Add a black [border](https://developer.mozilla.org/en-US/docs/Web/CSS/border) just around the column that contains all the planet name row headers.

## [Hints and tips](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Structuring_planet_data#hints_and_tips)

- The first cell of the header row needs to be blank, and span two columns.
- The group row headings (e.g. _Jovian planets_ ) that sit to the left of the planet name row headings (e.g. _Saturn_ ) are a little tricky to sort out — you need to make sure each one spans the correct number of rows and columns.
- One way of associating headers with their rows/columns is a lot easier than the other way.
