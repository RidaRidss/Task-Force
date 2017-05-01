# Task-Force

TaskForce will be a cross platform (android/iphone) application that will act as a personal assistant and will manage and remind day to day task and keep personal notes. It will also help to share any task or note within app social circle (delegates) by an email.

# Splash Screen

The screen will have:

 Application Logo and Name

It will be automatically redirect to “Login Screen” after 3 seconds.

# Login Screen

The screen will have:

 Application Logo and Name

 Email Address (Text Field)

 Password (Text Field)

 Login (Button)

 Forget Password (Hyperlink)

 Signup (Hyperlink)

> ##### Login: In case of registered and matched email address and password, redirect to the “To-Do List Screen (Home Screen)”. If username and password is not registered or unmatched, then show a message box with message “The entered username is not registered” or “The password is not matched” respectively.

> ##### Forget Password: It will redirect to “Forget Password Screen”.

> ##### Signup: It will redirect to “Signup Screen”.

# Forget Password Screen

The screen will have:

 Back (Button)

 Email Address (Text Field)

 Reset Password (Button)

> ##### Back: It will redirect to “Login Screen”.

> ##### Reset Password: In case of registered email address, send the password on entered email address and show a message box with message “The password has been sent on your email”. If email address is not registered then show a message box with message “The entered email address is not registered”.

# Signup Screen

The screen will have:

 Back (Button)

 Email Address (Text Field)

 Password (Text Field)

 Confirm Password (Text Field)

 Name (Text Field)

 Contact No (Text Field)

 Signup (Button)


> ##### Back: It will redirect to “Login Screen”.

> ##### Signup: In case of unregistered email address, save the credentials and redirect to the “Complete Profile Screen”. If email/username is registered then show a message box with message “The entered email/username is already registered”.

# Complete Profile Screen

The screen will have:

 Profile Picture (Attachment)

 Name (Text Field) – (Fetch from database)

 Contact No (Text Field) – (Fetch from database)

 Email Address (Text Field) – (Fetch from database)

 Blood Group (Text Field)

 Emergency Contact Person Name (Text Field)

 Emergency Contact Person No (Text Field)

# Menu Option

The option will have:

 Back (Button)

 User Picture with Name (Button and Hyperlink)

 Home (Hyperlink)

 Delegates (Hyperlink)

 Change Password (Hyperlink)

 Logout (Hyperlink)

> ##### Back: It will close the “Menu” and remain on the same screen at which it will be open.

> ##### User Picture with Name: It will redirect to “Profile Screen”.

> ##### Home: It will redirect to “To-Do List Screen (Home Screen)”.

> ##### Delegates: It will redirect to “Delegates Screen”.

> ##### Change Password: It will redirect to “Change Password Screen”.

> ##### Logout: It will logout the current user and redirect to “Login Screen”.

# Profile Screen:

The screen will have:

 Back (Button)

 Update Profile (Button)

 Profile Picture

 Name

 Contact No

 Email Address

 Blood Group

 Emergency Contact Person Name

 Emergency Contact Person No

> ##### Back: It will redirect to “To-Do List Screen (Home Screen)”.


> ##### Update Profile: It will redirect to “Update Profile Screen.”

# Update Profile Screen:

The screen will have:

 Back (Button)

 Profile Picture (Attachment) – (Fetch from database)

 Name (Text Field) – (Fetch from database)

 Contact No (Text Field) – (Fetch from database)

 Email Address (Text Field) – (Fetch from database)

 Blood Group (Text Field) – (Fetch from database)

 Emergency Contact Person Name (Text Field) – (Fetch from database)

 Emergency Contact Person No (Text Field) – (Fetch from database)

 Update (Button)

> ##### Back: It will redirect to “Profile Screen”.

> ##### Update Button: It will replace all credentials (either modified or not), but first email will be checked; if newly entered email is not exist in database then it will be replaced with previous one and a message box will be showed with a message “Profile has been updated” otherwise a message box will be showed with a message “The entered email is already registered”.


# Delegates Screen:

The screen will have:

 Back (Button)

 Add (Button)

 Delegates (List)

> ##### Back: It will redirect to “To-Do List Screen (Home Screen)”.

> ##### Add: It will redirect to “Add Delegate Screen”.

# Add Delegate Screen:

The screen will have:

 Back (Button)

 Picture (Attachment)

 Name (Text Field)

 Contact No (Text Field)

 Email Address (Text Field)

 Add (Button)

> ##### Back: It will redirect to “Delegates Screen”.

> ##### Add: It will check delegates’ count; if less than 5 then add the details as delegate and redirect to “Delegates Screen”.

# Change Password Screen:

The screen will have:

 Back (Button)

 Password (Text Field)

 New Password (Text Field)

 Confirm New Password (Text Field)

 Change Password (Button)

> ##### Back: It will redirect to “To-Do List Screen (Home Screen)”.

> ##### Change Password: It will match the password with database, if match then replace with new password in case of new password and confirm new password is matched and show a message box with message “Password has been changed”. Otherwise show a message box with message “Incorrect password” or “Password doesn’t match” respectively.

# To-Do List Screen (Home Screen)

The screen will have:

 Menu (Button)

 Add (Button)

 Archive (Button)

 Notes (Tab)

> ##### Menu: It will be open on half “To-Do List Screen (Home Screen)” from left.

> ##### Add: It will redirect to “Create To-Do Screen”.

> ##### Archive: It will redirect to “Archive To-Do List Screen”.

> ##### Notes: It will redirect to “Notes Screen”.

> ##### To-Do List Item: It will redirect to “View To-Do Screen”.

# Create To-Do Screen:

The screen will have:

 Back (Button)

 Title (Text Field)

 Date and Time (Date and Time)

 Description (Text Field)

 Save (Button)


> ##### Back: It will redirect to “To-Do List Screen (Home Screen)”.

> ##### Save: It save the To-Do and will redirect to “To-Do List Screen (Home Screen)”.

# View To-Do Screen:

The screen will have:

 Back (Button)

 Edit (Button)

 Delete (Button)

 Title (Text Field)

 Date and Time (Date and Time)

 Description (Text Field)


> ##### Back: It will redirect to “To-Do List Screen (Home Screen)”.

> ##### Edit: It will redirect to “Update To-Do Screen”.

> ##### Delete: It will delete the To-Do and redirect to “To-Do List Screen (Home Screen)”.

# Update To-Do Screen:

The screen will have:

 Back (Button)

 Title (Text Field)

 Date and Time (Date and Time)

 Description (Text Field)

 Update (Button)


> ##### Back: It will redirect to “View To-Do Screen”.

> ##### Update: It will update the To-Do and will redirect to “View To-Do Screen”.

# Archive To-Do List Screen

The screen will have:

 Menu (Button)

 To-Do (Tab)

 Notes (Tab)


> ##### Menu: It will be open on half “Archive To-Do List Screen” from left.

> ##### To-Do: It will redirect to “To-Do List Screen (Home Screen)”.

> ##### Notes: It will redirect to “Notes Screen”.

> ##### Archive To-Do List Item: It will redirect to “View Archive To-Do Screen”.

# View Archive To-Do Screen:

The screen will have:

 Back (Button)

 Title (Text Field)

 Date and Time (Date and Time)

 Description (Text Field)


> ##### Back: It will redirect to “Archive To-Do List Screen”.

# Notes Screen

The screen will have:

 Menu (Button)

 Add (Button)

 To-Do (Tab)


> ##### Menu: It will be open on half “Notes Screen” from left.

> ##### Add: It will redirect to “Create Note Screen”.

> ##### To-Do: It will redirect to “To-Do List Screen (Home Screen)”.

> ##### Notes List Item: It will redirect to “View Note Screen”.

# Create To-Do Screen:

The screen will have:

 Back (Button)

 Title (Text Field)

 Note (Text Field)

 Save (Button)


> ##### Back: It will redirect to “Notes Screen”.

> ##### Save: It save the Note and will redirect to “Notes Screen”.

# View Note Screen:

The screen will have:

 Back (Button)

 Edit (Button)

 Delete (Button)

 Title (Text Field)

 Note (Text Field)


> ##### Back: It will redirect to “Notes Screen”.

> ##### Edit: It will redirect to “Update Note Screen”.

> ##### Delete: It will delete the Note and redirect to “Notes Screen”.

# Update Note Screen:

The screen will have:

 Back (Button)

 Title (Text Field)

 Note (Text Field)

 Update (Button)


> ##### Back: It will redirect to “View Note Screen”.

> ##### Update: It will update the Note and will redirect to “View Note Screen”.
