# selenium-videorecording

How to record in video Java/Selenium WebDriver-based tests executions

## Application context

Selenium is an open-source tool that automates Web browsers. It provides a single interface that lets you write test scripts in programming languages like Java, among others.

## Implementation

Easy video recording of your Java/Selenium WebDriver-based tests by just putting couple instructions.

This code allows easily record video of your Java/Selenium WebDriver-based tests by just putting couple instructions. In fact, this code is the minimum to do the video recording of a test automation based on Java/Selenium WebDriver.

Everything that goes between:

```
videoRecord.startRecording();
```

and

```
videoRecord.stopRecording();
```

is recorded.

The generated video is saved in the "downloadFiles" folder of the project, with the date and time of the recording.

This project uses a library called Monte Media Library (http://www.randelshofer.ch/monte/).

Searching on Google is the solution that the testers give.

This project also uses https://github.com/bonigarcia/webdrivermanager instead of chromedriver.

## Deliverable

that includes:

Java EE Eclipse project with the source code. You should use Maven build because the project is clean.

Download the files as a zip using the green button, or clone the repository to your machine using Git.
