# timestamp
FCC Timestamp Microservice

FCC Timestamp Microservice

User stories:

1 - I can pass a string as a parameter, and it will check to see whether that string contains either a unix timestamp or a natural language date (example: January 1, 2016).

2 - If it does, it returns both the Unix timestamp and the natural language form of that date.

3 - If it does not contain a date or Unix timestamp, it returns null for those properties.

Example usage:
https://macogiltimestamp.herokuapp.com/
https://macogiltimestamp.herokuapp.com/December 15, 2015
https://macogiltimestamp.herokuapp.com/ 7584395739
Example output
{ "unix": 5784395793, "natural": "December 15, 2015"}
