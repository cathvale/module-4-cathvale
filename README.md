# Creating Form using React!
In this documentation, we will walk through the process of how I created a form using React, along with validation. Below are the dependencies or applications that I used to create this project.

## Dependencies
- Tailwind CSS
- Yup

## Form Content
- Personal Information
- Address Information
- Account Information

## Detailed Content
### Personal Information
This section contains three main fields, and each field has validation using Yup:
- Full Name: The name needs to be a string, and the field is set as required.
- Email Address: The email must contain the '@' character, and the field is set as required.
- Birth Date: The date must not be later than the current date, and the field is set as required.

### Address Information
This section contains four main fields, and each field has validation using Yup:
- Street Address: The address must contain 15 or more character, and the field is set as required.
- City: The city must contain 4 or more character, and the field is set as required.
- State: The state must contain 4 or more character, and the field is set as required.
- Zip Code: The zip code must contain 5 number digits, and the field is set as required.

### Account Information
This section contains two main fields, and each field has validation using Yup:
- Username: The username must contain 8 or more character, and the field is set as required.
- Email Address: The password must contain 8 or more character include at least one lowercase letter, one uppercase letter, one number, and one special character, and the field is set as required.