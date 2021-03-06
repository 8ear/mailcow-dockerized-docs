## Method 1 (IMAP, SMTP, DAV)

Email, contacts and calendar can be configured automatically on Apple devices by installing a profile. It configure IMAP, CardDAV and CalDAV.

1. Download and open <span class="client_variables_unavailable">the file from <i>https://${MAILCOW_HOSTNAME}/mobileconfig.php</i></span><span class="client_variables_available"><a class="client_var_link" href="mobileconfig.php">mailcow.mobileconfig</a></span>.
2. Enter the unlock code (iPhone) or computer password (Mac).
3. Enter your email password three times when prompted.

## Method 2 (Exchange ActiveSync emulation)

On iOS, Exchange ActiveSync is also supported as an alternative to the procedure above. It has the advantage of supporting push email (i.e. you are immediately notified of incoming messages), but has some limitations, e.g. it does not support more than three email addresses per contact in your address book. Follow the steps below if you decide to use Exchange instead.

1. Open the *Settings* app, tap *Mail*, tap *Accounts*, tap *Add Acccount*, select *Exchange*.
2. Enter your email address<span class="client_variables_available"> (<code><span class="client_var_email"></span></code>)</span> and tap *Next*.
3. Enter your password, tap *Next* again.
4. Finally, tap *Save*.
