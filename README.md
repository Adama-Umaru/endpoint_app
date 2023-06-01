In this code, we modify the "Subject" header of the email message to include the subject text wrapped in HTML <span> tags with the specified CSS styles for bold font and red color. We also add the line message.replace_header('Content-Type', 'text/html') to ensure that the email is treated as HTML content.

With this modification, the subject of the email will appear in bold font and red color when it is received by the recipient.

Please note that you need to replace "smtp.example.com", "your-email@example.com", and "your-password" with the appropriate SMTP server details and your email credentials.






