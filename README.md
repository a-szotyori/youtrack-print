# youtrack-print

## Print square YouTrack tickets

Search for the issues you want to print and click the print button.

![Select the issues to print](select_issues.png)

On the print page open the Developer Tools (⌥⌘I or Ctrl+Shift+I), select Sources and open the `_resourceBundle` folder. Select the css file that starts with `bundledCss-`. Copy the contents of the `tickets.css` and paste it into the css file of the YouTrack print page.

![Override the css file with tickets.css](override_css.png)

The tickets are now ready for printing. The size of the squares is about the same as a standard Post-It note.

![Ready to be printed](ready_to_print.png)