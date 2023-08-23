# Tarot Reader Cyber Mystic

## Usage

### Question about your fortune

1. The application should list the previous entries with edit button, displaying the question asked, and organized by date.
2. The application will instruct the user to type out their question.
3. When the question is submitted 9 cards, divided into three groups, will be displayed.
4. The meanings of each individual card is then revealed.
5. A text box will allow you to store what you think the reading means.
6. You can edit previous entries to see what you think the fortune was saying after.

### Curious about your fortune

1. Button will be pressed
2. Five cards will return with meaning revealed
3. You can write what you think the cards are saying

## Development

### Inquiries

1. Fetch previous questions from database and list them.
2. Text field will be looking for a question.
3. On submit root data will be pulled from api, randomize the order and meaning, split into three arrays of random sizes, combined in random order, and finally returning the first 9.
4. The nine cards returned will fetch an image from another api to display each card and place them into three arrays past:[0-2],present:[3-5], future:[6-8].
5. Each card meaning will be revealed after 7 seconds: one per second.
6. The text field will be displayed for the user to type what they think it means.
7. On enter the cards and thoughts will be posted to database.
8. Editing will update the entry's thoughts in database.
9. Deleting will delete the post in database

### Entertainment

1. Fetch previous readings, and list them.
2. When the button is pressed the root data will be randomized, as well as the meaning, and split into two arrays of random size.
3. The Arrays are randomly combined, and the first 5 cards are pulled.
4. The images of each card are placed into a grid, with their corresponding meanings, in the shape of a cross.
5. The text field underneath will ask what the user thinks the cards mean.
6. If no response is given then no post will be made to database.
7. You can edit the thoughts later on, but the app will not allow an empty text field.
