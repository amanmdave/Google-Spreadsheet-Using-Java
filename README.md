# Read and Write to Google Spreadsheet using Java

This is a boilerplate project that can be used to read and write from a Google Spreadsheet! 

<hr/>

### Prerequisites

The foremost task, go to the following link and give it a read.
https://developers.google.com/sheets/api/quickstart/java

- Make sure you complete [Step 1](https://developers.google.com/sheets/api/quickstart/java#step_1_turn_on_the).
- Download the `credentials.json` and keep it handy

<hr/>

### Installing

- `git clone https://github.com/wizArD-1910/Connect-To-Google-Spread-Sheet-Using-Java.git`
- `gradle build`
- Copy `credentials.json` to `src/main/resources`
- `gradle run`
- A browser window will open, accept and allow google for permissions after reading them
- Output should be displayed

<hr/>

### Reading 

- Go to `ReadFromSheet.java`
- Change the spreadsheet id
- Go to `build.gradle`
- Change `mainClassName = 'SheetsQuickstart' ` to `mainClassName = 'ReadFromSheet'`
- `gradle run`

<hr/>

### Writing

- Go to `WriteToSheet.java`
- Change the spreadsheet id
- Go to `build.gradle`
- Change `mainClassName = 'SheetsQuickstart' ` to `mainClassName = 'WriteToSheet'`
- `gradle run`

## Important Information

After changing SCOPE or SpreadSheetId of your project, delete your `tokens` folder and rerun the application


### Project Structure

```
|-src
    |-main
        |-java
            |-ReadFromSheet
            |-SheetsQuickstart
            |-WriteToSheet
        |-resources
            |-credential.json
|-build.gradle
|-settings.gradle
|-README.md
```

## Ending Notes
- The repository follows ` Conventional Commits ` and `Gitmoji` styling
- The `.idea` folder contains files that will change project settings for better understanding of comments
- For comments follow:
    - `//TODO:` When you want users to complete some tasks
    - `//INFO:` Add external Information
    - `//Bug:` To suggests for bugs in code
    - `//URL:` For adding URLs
    
![Comment Styling](/src/main/assets/comment_styling.png)

    
