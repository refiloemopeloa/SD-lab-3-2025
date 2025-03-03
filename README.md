# SD-lab-3-2025

# Music Titles by Year Lab

## Objective
The objective of this lab is to assess your ability to manipulate arrays of objects and export functions in JavaScript. You will write a function that processes an array of music track objects and organizes them by release year.

## Instructions

1. **Setup**
   - Create a new file named `<student_number>-lab3.js` (e.g., `6054654-lab3.js`).

2. **Function Implementation**
   - Write and export a function named `getMusicTitlesByYear` that takes in an array of music track objects.
   - Each music track object has the following properties:
     - `title`: The title of the track (string).
     - `artist`: The artist of the track (string).
     - `year`: The year the track was released (number).
   - The function should return an object where the keys are the years and the values are arrays of music track titles released in that year.

3. **Additional Requirements**
   - **Sorting**: Ensure that the arrays of music track titles are sorted alphabetically.
   - **Error Handling**: Implement error handling to manage cases where the input data is not in the expected format.
   - **Edge Cases**: Consider edge cases such as empty arrays, missing properties, and non-numeric year values.

4. **Example**
   - Given the following array of music tracks:
     ```javascript
     const tracks = [
       { title: 'Blinding Lights', artist: 'The Weeknd', year: 2020 },
       { title: 'Levitating', artist: 'Dua Lipa', year: 2021 },
       { title: 'Save Your Tears', artist: 'The Weeknd', year: 2020 },
     ];
     ```
   - The function `getMusicTitlesByYear(tracks)` should return:
     ```javascript
     {
       2020: ['Blinding Lights', 'Save Your Tears'],
       2021: ['Levitating']
     }
     ```

5. **Submission**
   - Ensure your file is named correctly following the pattern `<student_number>-lab3.js`.
   - Submit your file as a single JavaScript file.

## Evaluation Criteria
- Correct implementation of the `getMusicTitlesByYear` function.
- Proper handling of the array of music track objects.
- Correct export of the function.
- Code readability and organization.
- Implementation of sorting and error handling.
- Consideration of edge cases.

## Test Cases
Your function will be tested against the following scenarios:
1. Basic functionality with multiple tracks in the same year.
2. Multiple tracks in different years.
3. Tracks in consecutive years.
4. No data.
5. Malformed data (missing year).
6. Malformed data (year is not a number).
7. Sorting of track titles.
8. Error handling for invalid data.

Each test case will contribute to your overall score. Ensure your function handles all scenarios correctly.

## Evaluation
Your submission will be automatically tested using a script that checks for the above criteria. Ensure your file meets all the requirements to pass the tests.

Notes:
- File names and required texts such as commit messages and text on html pages must appear EXACTLY as briefed. 
- Incorrect file names and text will be considered a fail and will not be remarked.

Good luck!

# Submission 
Please submit to the Google drive below. 

Please create a folder titled your student number **ONLY**. 
Then inside the folder, place your *.js file  
**Note**: the submission link will close at 17:00. Please submit before then

[Submission link](https://drive.google.com/drive/folders/11nDwyd4xOgmSm9jjPFXmtFN9PzM88os2) 
