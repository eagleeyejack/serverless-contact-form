# Lambda API AWS | Serverless contact form

To deploy to the server use command

`serverless deploy`

Edit the email template `email.html` and then copy that into `handler.js`

Data is passed from the contact form on Gatsby.

If you're sending an email from your self, you need to modify the email otherwise you'll get a delivery failure email. 

https://dev.to/adnanrahic/building-a-serverless-contact-form-with-aws-lambda-and-aws-ses-4jm0

- [ ] Change variables setup from the custom secrets file.
- [ ] Embed HTML into the file to remove dupliate code
