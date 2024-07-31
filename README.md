# Build A Telephone Number Validator

This project checks if a number is a valid phone number in the United States

## UX

**Getting Started**

In the input field, enter a phone number.  Click on Check or Press Enter.  You will see if the entered phone number is valid or not.

**User Stories**

1.  As a user, I expect an `input` element with an `id` of `user-input`.

2.  As a user, I expect a `button` element with an `id` of `check-btn`.

3.  As a user, I expect a `button` element with an `id` of `clear-btn`.

4.  As a user, I expect a `div` element with an `id` of `results-div`.

5.  As a user, when I click on the `#check-btn` element without entering a value in the `#user-input` element, an alert should appear with the text "Please provide a phone number"

6.  As a user, when I click on the `#clear-btn` element, the content within the `#results-div` element should be removed.

7. As a user, when the `#user-input` element contains `1 (555) 555-5555` and the `#check-btn` element is clicked, the `#results-div` element should contain the text "Valid US number: 1 (555) 555-5555"

8. As a user, when the `#user-input` element contains `5555555555` and the `#check-btn` element is clicked, the `#results-div` element should contain the text "Valid US number: 5555555555"

9. As a user, when the `#user-input` element contains `555-555-5555` and the `#check-btn` element is clicked, the `#results-div` element should contain the text "Valid US number: 555-555-5555"

10. As a user, when the `#user-input` element contains `(555)555-5555` and the `#check-btn` element is clicked, the `#results-div` element should contain the text "Valid US number: (555)555-5555"

11. As a user, when the `#user-input` element contains `1(555)555-5555` and the `#check-btn` element is clicked, the `#results-div` element should contain the text "Valid US number: 1(555)555-5555"

12. As a user, when the `#user-input` element contains `555-5555` and the `#check-btn` element is clicked, the `#results-div` element should contain the text "Invalid US number: 555-5555"

13. As a user, when the `#user-input` element contains `5555555` and the `#check-btn` element is clicked, the `#results-div` element should contain the text "Invalid US number: 5555555"

14. As a user, when the `#user-input` element contains `1 555)555-5555` and the `#check-btn` element is clicked, the `#results-div` element should contain the text "Invalid US number: 1 555)555-5555"

15. As a user, when the `#user-input` element contains `1 555 555 5555` and the `#check-btn` element is clicked, the `#results-div` element should contain the text "Valid US number: 1 555 555 5555"

16. As a user, when the `#user-input` element contains `1 456 789 4444` and the `#check-btn` element is clicked, the `#results-div` element should contain the text "Valid US number: 1 456 789 4444"

17. As a user, When the `#user-input` contains `123**&!!asdf#` and `#check-btn` is clicked, `#results-div` should contain the text "Invalid US number: 123**&!!asdf#"

18. As a user, when the `#user-input` element contains `55555555` and the `#check-btn` element is clicked, the `#results-div` element should contain the text "Invalid US number: 55555555"

19. As a user, When the `#user-input` element contains `(6054756961)` and the `#check-btn` element is clicked, the `#results-div` element should contain the text "Invalid US number: (6054756961)"

20. As a user, when the `#user-input` element contains `2 (757) 622-7382` and the `#check-btn` element is clicked, the `#results-div` element should contain the text "Invalid US number: 2 (757) 622-7382"

21. As a user, when the `#user-input` element contains `0 (757) 622-7382` and the `#check-btn` element is clicked, the `#results-div` element should contain the text "Invalid US number: 0 (757) 622-7382"

22. As a user, when the `#user-input` element contains `-1 (757) 622-7382` and the `#check-btn` element is clicked, the `#results-div` element should contain the text "Invalid US number: -1 (757) 622-7382"

23. As a user, when the `#user-input` element contains `2 757 622-7382` and the `#check-btn` element is clicked, the `#results-div` element should contain the text "Invalid US number: 2 757 622-7382"

24. As a user, when the `#user-input` element contains `10 (757) 622-7382` and the `#check-btn` element is clicked, the `#results-div` element should contain the text "Invalid US number: 10 (757) 622-7382"

25. As a user, when the `#user-input` element contains `27576227382` and the `#check-btn` element is clicked, the `#results-div` element should contain the text "Invalid US number: 27576227382"

26. As a user, when the `#user-input` element contains `(275)76227382` and the `#check-btn` element is clicked, the `#results-div` element should contain the text "Invalid US number: (275)76227382"

27. As a user, when the `#user-input` element contains `2(757)6227382` and the `#check-btn` element is clicked, the `#results-div` element should contain the text "Invalid US number: 2(757)6227382"

28. As a user, when the `#user-input` element contains `2(757)622-7382` and the `#check-btn` element is clicked, the `#results-div` element should contain the text "Invalid US number: 2(757)622-7382"

29. As a user, when the `#user-input` element contains `555)-555-5555` and the `#check-btn` element is clicked, the `#results-div` element should contain the text "Invalid US number: 555)-555-5555"

30. As a user, when the `#user-input` element contains `(555-555-5555` and the `#check-btn` element is clicked, the `#results-div` element should contain the text "Invalid US number: (555-555-5555"

31. As a user, when the `#user-input` element contains `(555)5(55?)-5555` and `#check-btn` is clicked, `#results-div` should contain the text "Invalid US number: (555)5(55?)-5555"

32. As a user, when the `#user-input` element contains `55 55-55-555-5` and the `#check-btn` element is clicked, the `#results-div` element should contain the text "Invalid US number: 55 55-55-555-5"

33. As a user, when the `#user-input` element contains `11 555-555-5555` and the `#check-btn` element is clicked, the `#results-div` element should contain the text "Invalid US number: 11 555-555-5555"

## Features

Allows the user to check if the entered phone number is valid.

## Technologies

Uses HTML5, CSS3 and JavaScript.

## Testing

Make sure all user stories have been met.

## Deployment

Deployed on [GitHub Pages](https://derektypist.github.io/build-a-telephone-number-validator/) at the main branch.

## Credits

### Acknowledgements

[FreeCodeCamp - JavaScript Algorithms and Data Structures](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures-v8/)
