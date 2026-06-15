# Feature :: Add Slip by uploading image

## User Story
As a user, I want to be able to add a slip by uploading an image, so that I can easily input slip information without manually entering data.   

## Acceptance Criteria
1. The user can upload an image of a slip through the web interface.
2. The system uses OpenAI's Chat Completion API to analyze the uploaded image and extract relevant information from the slip.
3. The extracted information is displayed to the user for confirmation before being stored in the CSV file.
4. The system should handle errors gracefully, such as unsupported file formats or issues with the OpenAI API, and provide appropriate feedback to the user.

## Implementation Steps
1. Create a new route in the web application to handle slip uploads.
2. Implement a file upload mechanism in the web interface, allowing users to select and upload an image file.
3. Use the OpenAI API to analyze the uploaded image and extract relevant information.
4. Display the extracted information to the user for confirmation.
5. If the user confirms the information, store it in the CSV file using the csv library.
6. Implement error handling for unsupported file formats and API issues, providing feedback to the user.
7. Test the feature to ensure it works as expected and meets the acceptance criteria.