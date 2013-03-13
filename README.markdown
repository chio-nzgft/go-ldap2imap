Here's a little IMAP client in Go.

* `.` contains the "imap" package that implements the IMAP protocol client
* `imapsync` contains a "main" package that uses the "imap" library to list or download gmail labels (= inboxes)

This hasn't been tested against anything but gmail's IMAP yet, and will likely eat your mail, etc.

To run imapsync:
* `bin/imapsync list username password`
* `bin/imapsync fetch username password MAILBOXNAME`
