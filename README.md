### Documentation:
#### Design Choices:
   a. **Input Validation:**
      - Added a `try-except` block to handle non-integer input for menu choices.
      - This prevents the program from crashing when a user enters a non-numeric value.
   b. **User-Friendly Input:**
      - Used `int(input())` to ensure that the user enters a numeric choice.
   c. **Exception Handling:**
      - Added error handling to deal with potential input issues, enhancing the robustness of the program.
#### Challenges Faced:
   a. **Input Validation:**
      - Ensuring that user input is validated correctly and handling potential errors.
   b. **User Interface:**
      - Balancing simplicity with user interaction to maintain a straightforward and user-friendly interface.
### Testing:
Thoroughly test the code by running various scenarios:
   - Displaying an empty to-do list.
   - Adding tasks.
   - Marking tasks as completed.
   - Removing tasks.
   - Quitting the program.
Fix any identified bugs or issues during testing.
### Conclusion:
The implemented code adheres to best coding practices, readability, and modularity. It incorporates user-friendly input handling and error checking. Testing ensures the robustness of the program. This documentation provides insights into design choices, challenges faced, and the rationale behind the code structure.
