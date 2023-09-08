# Dog_API_with_Fetch

## Notes on using the fetch() method to send a POST request instead of the default GET request.

- "method indicates the type of request."
- "The headers for the request are usually contained within an object."
- "application"/json is the media type for a JSON response. This communicates to the server that the data has been encoded with JSON."
- "In POST requests, values are sent to the server in the body of the request. First, the form data needs to be "strigified," or transformed into a JSON string."
- "The method JSON.stringify() here is being used to convert the values of name and comment into a JSON string."
  -- These above comments are quotes by Guil Hernandez, from his lesson on "Posting Data with fetch()" in his "Working with the Fetch API" module of the "Intro to Programming" course at Team Tree House. They came from notes that I jotted down while following along with his interactive and video-based tutorial, which I used to produce this project.
