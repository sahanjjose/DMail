# DMail - Django Email Client

Created - 28th August, 2020. Publicly Available - 31st January, 2024.

## Features

- **Send Mail:**
  - Compose and send emails with specified recipients, subject, and body.
  - Emails sent are stored in the sent mailbox.

- **Mailbox:**
  - View emails in the Inbox, Sent, or Archive mailboxes.
  - Display emails with sender, subject, timestamp, and read/unread status.
  - Unread emails have a white background, while read emails have a gray background.

- **View Email:**
  - Click on an email to view its details, including sender, recipients, subject, timestamp, and body.
  - Mark emails as read when viewed.

- **Archive and Unarchive:**
  - Archive and unarchive emails in the Inbox and Archive mailboxes.
  - Archiving emails removes them from the Inbox and vice versa.

- **Reply:**
  - Reply to emails with a pre-filled composition form.
  - The recipient field, subject line, and body are pre-filled appropriately for a quick response.

## Functioning

1. **Send Email:**
   - Navigate to the "Compose" view.
   - Fill in recipient(s), subject, and body.
   - Click the "Send" button.
   - The email is sent, and the sent mailbox is loaded.

2. **Mailbox:**
   - Click on Inbox, Sent, or Archive buttons.
   - The appropriate mailbox is loaded with emails.
   - Each email is displayed with sender, subject, timestamp, and read/unread status.

3. **View Email:**
   - Click on an email in any mailbox.
   - The full details of the email are displayed, and the email is marked as read.

4. **Archive and Unarchive:**
   - In the Inbox, click on an email and use the "Archive" button to move it to the Archive.
   - In the Archive, click on an email and use the "Unarchive" button to move it back to the Inbox.

5. **Reply:**
   - Click on an email in any mailbox.
   - Click the "Reply" button to open the composition form with pre-filled details.
   - Modify if needed and click "Send" to send the reply.

*Note: The application is designed as a single-page app (SPA) using JavaScript to control the user interface. The backend is implemented using Django, providing a RESTful API for email operations.*
