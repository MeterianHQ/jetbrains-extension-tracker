# Notifications & Snoozing

Meterian Security is designed to be informative without being noisy. You have full control over when and how often it interrupts you.

## Snoozing a single finding

To suppress a specific vulnerability without fixing it:

1. Open the **actions** menu on the affected line (hover on the highlighted dependency and press `more actions..` or  hover and press `Alt+Enter`)
3. Snooze the vulnerability for your desired duration

The finding is hidden for the chosen period. When the snooze expires, it reappears automatically.

## Snoozing an entire manifest file

To silence all findings for a specific file (e.g. while you're mid-refactor):

1. Right-click the manifest file in the **project view**
2. Select **Snooze Meterian notifications for this file**
3. Choose a duration

To undo: right-click the file again and select **Unsnooze Meterian notifications**.
