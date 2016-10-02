# Specto

We know that credit card theft is prominent in our society today, so we wanted to create an application that added extra security to credit card usage.Our application uses facial recognition to map a face to a credit card number, so when a credit card is used, the application will know if the right person is using it. We enrolled and verified the identity of individuals by inserting Kairos's open-source Rest API by converting images into a base64 string and posting them to kairos's server, where an algorithm deconstructs the face using facial geometry. Then, when another image is used to verify the identity, the algorithms uses a standard deviation as means for comparison and returns a confidence level. If the confidence is within a specific range below 90%, we then re-enroll the new image to ensure the algorithm is dynamic. We used HTML/CSS to create the user interface.
