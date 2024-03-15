Add Items to Shopping List 2
Medium
Create a shopping list app using React.
The app should have a list of categories, and
when the user clicks on a category, the items for that category should be displayed.
Initially, the first category should be displayed.
The user should also be able to add new items to the selected category.
We have already provided you with an array of categories, where each category object has a name property and an items property.
The app should have the following functionality:
The app should display the list of categories. Each category should be displayed as a div with the class category, and when clicked, should update the activeCategory state variable and highlight the div by adding active class to that particular div.
The app should display the items for the selected category. The items should be displayed as a list of divs with the class item.
The app should have an input field where the user can enter a new item for the selected category. The input field should be a controlled component, meaning that its value should be stored in the newItem state variable and updated on change.
The app should have a button to add the new item to the selected category. The button should have a click event, which adds the new item to the items property of the active category, and update the categories state variable with the new copy of the array.
Finally, the newItem state variable should be reset to an empty string.
This is how the App should look like:

Note:
**Do not remove the existing classes and ids from the boilerplate. **
**. active class is provided in the CSS boilerplate. **
Test Cases

1.  Fruits list should be displayed as the app loads
2.  Vegetables list should be displayed on clicking the Vegetable category
3.  Dairy list should be displayed on clicking the Dairy category
4.  Adding item to fruits category and checking the fruits list
5.  Adding item to vegetable category and checking the vegetable list
6.  Adding item to dairy category and checking the dairy lis
