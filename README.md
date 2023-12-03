# Quiz Code API

The Quiz Code API is a collection of JSON files containing multiple-choice questions focused on JavaScript. It is hosted on GitHub Pages, providing a straightforward way to access coding questions for learning and assessment.

## Overview

The Quiz Code API is designed to assist developers in enhancing their proficiency in JavaScript by providing a curated set of coding questions. Whether you are preparing for technical interviews, coding assessments, or just want to improve your coding skills, this API offers a diverse range of questions to challenge and educate.

### How to Use

1. **Access JSON Data:**
   - The JSON data containing coding questions is available at the following URL:
     ```
     https://github.com/martindocs-bootcamp/quiz-code-api/codeQuiz.json
     ```

2. **Retrieve Data using Fetch API:**
   - In your JavaScript code, use the Fetch API to retrieve JSON data from the Quiz Code API:
     ```javascript
     const apiUrl = 'https://github.com/martindocs-bootcamp/quiz-code-api/codeQuiz.json';

     fetch(apiUrl)
       .then(response => response.json())
       .then(data => {
         // Process the retrieved data
         console.log(data);
       })
       .catch(error => {
         console.error('Error fetching data:', error);
       });
     ```

3. **Integration with Your Application:**
   - Integrate the fetched JSON data into your application as needed, such as creating quizzes or presenting questions to users.

## Feedback and Contributions

We welcome feedback and contributions to improve the Quiz Code API. If you encounter issues or have suggestions, please open an issue or submit a pull request on our [GitHub repository](https://github.com/martindocs-bootcamp/quiz-code-api/issues).

## Credits

N/A (Open for contributions).

## License

Please refer to the [LICENSE](./LICENSE.md) file in this repository for details on how this project is licensed.