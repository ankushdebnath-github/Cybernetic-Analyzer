Cybernetic Password Analyzer & Breach Center
Project Description
The Cybernetic Password Analyzer is a comprehensive, themed security tool designed to help users understand and improve their digital security. It provides a suite of features in a slick, cyberpunk-inspired interface, complete with a "Matrix" style animated background.

The application is split into two main modules: a real-time Password Analyzer for evaluating password strength and a Breach Center for managing and checking a simulated database of breached email accounts. The entire application is fully responsive and works seamlessly on desktop, tablet, and mobile devices. For persistence, it leverages a Firebase Firestore backend with offline capabilities.

Core Features
1. Password Analyzer
This tab provides instant, detailed feedback on password strength as you type.

Real-time Strength Calculation: Calculates the estimated time for a powerful computer to crack the password based on its entropy.

Visual Entropy Meter: A glowing "Energy Core" orb visually represents the password's randomness, filling up and changing color from red (weak) to green (strong).

Dynamic Checklist: A comprehensive checklist validates the password against essential criteria:

Minimum length (12+ characters)

Presence of uppercase and lowercase letters

Inclusion of numbers and symbols

Avoidance of common, easily guessable passwords

Detection of simple patterns (like aaa or 123)

Dual-Mode Password Generator:

Random Mode: Creates cryptographically secure random passwords with customizable length and character sets.

Diceware (Anime) Mode: Generates strong, memorable passphrases using a list of over 100 iconic anime moves and character names, intelligently adding numbers and capitalization to meet security rules.

Robotic Typing Animation: Generated passwords are typed into the input field character-by-character for a more immersive feel.

2. Breach Center (with Live Database)
This tab allows you to create, manage, and check a personal, persistent database of simulated breached email accounts.

Breach Creator & Manager:

Add any email address to your simulated breach database.

Specify how many randomized, detailed breach records to generate for that email (e.g., "Username leaked from AnimeFanForums").

View a live list of all emails you've added.

Delete any email entry from the database with a confirmation step.

Breach Checker:

Enter an email to check it against your personal database.

If a match is found, a "High Alert" pop-up displays the detailed (simulated) breach records.

If no match is found, it gives a "good news" confirmation.

Persistence & Offline Mode: Powered by Firebase Firestore, the database is saved between sessions and will even work offline, syncing any changes you make once you reconnect.

How to Use
Switch Between Modules: Use the tabs at the top to navigate between the "Password Analyzer" and the "Breach Center."

Analyzing a Password:

Simply type a password in the input field on the first tab. All meters and checklists will update in real-time.

Click the "Generate" icon to open the password generator, choose your mode, and create a new secure password.

Managing the Breach Database:

Navigate to the "Breach Center" tab.

In the "Breach Creator & Manager" section, enter an email, choose the number of breaches to create, and click "Add Email to Database."

Your added emails will appear in the list below, where you can delete them.

Checking for a Breach:

In the "Breach Checker" section, enter an email and click "Check Email."

The system will query your personal database and show the results, triggering the alert pop-up if a match is found.
