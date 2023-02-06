# Ruby Practice

 1. Open a file (e.g. `date_formatted.rb`) in the editor window.
 1. Modify the file per the instructions on top.
 1. Run your Ruby file by typing `ruby ` and then the name of the file you want to run in the terminal. If we want to run `date_formatted.rb`, we can write the command:

      ```bash
      ruby date_formatted.rb
      ```
   
      Remember, if there are multiple files with similar names, start typing the name and then just press <kbd>Tab</kbd> on your keyboard to let the terminal complete the name. You rarely need to type full filenames out — use **tab completion**!

1. To re-run this command, you can use the <kbd>Up ↑</kbd> and <kbd>Down ↓</kbd> arrow keys to look at the history of commands you've run in a terminal.
1. When you think you have the required output, run `rails grade` and proceed when the test passes without errors.

If you are struggling, **try to experiment directly in the IRB environment** by typing `irb` into the terminal and pressing enter. This will start an interactive Ruby terminal, where you can enter individual lines of Ruby to see their output. If you start `irb` then the terminal will no longer be in the `bash` environment so things like `rails grade` won't work. You will need to open a second terminal with the plus (+) icon and switch between the `irb` and `bash` terminals as needed. Alternatively type `exit` at the IRB terminal prompt to return to the `bash` environment.  


## Date

### date_formatted.rb

Should format and identify different parts of todays date.

```bash
"The year is: 2020, the calendar day is: 1, and the month is: 7."
```


### date_math.rb
Should output the number of days since Ruby was made.

Ruby released to the public on `December 21, 1995`.

```bash
"Ruby is 108937 days old!"
```

### date_monday.rb

Should output:
```bash
"Is today Monday? true"
```
if today is Monday, or
```bash
"Is today Monday? false"
```
if today is _not_ Monday.

## Specs
<details>
  <summary>Click here to see names of each test</summary>

date_math.rb should output '8959' when today is Jul 1, 2020 

date_math.rb is not 'hard-coded' to the current date' 

date_formatted.rb outputs 'The year is: 2020, the calendar day is: 1, and the month is: 7.' when today is July 1, 2020 

date_formatted.rb outputs the formatted dates for any past/future date 

date_formatted.rb should output 'Is today Monday? false', when today is not Monday 

date_monday.rb should output 'Is today Monday? false', when today is not Monday 

date_monday.rb should output 'Is today Monday? false', when today is not Monday 

</details>
