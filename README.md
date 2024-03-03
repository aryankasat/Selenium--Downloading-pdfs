# Selenium--Downloading-pdfs
I have created a Selenium script which can download pdfs from a webpage.


## One needs to install node and npm before running the .side file in the terminal or command prompt

## One needs to install the selenium side runner to run the script
```
    npm install -g selenium-side-runner
```

## After this one needs to install the browser of their choice (in my case it is Chrome)
```
    npm install -g chromedriver
```

## Finally we just need to launch the runner and also mentioning the driver one is using for execution of the script
```
    selenium-side-runner -c "browserName=chrome" "/path/to/your-project.side"
```

# Note : One needs to change the default settings of the driver so that the pdf is downloaded and not opened on a new tab in the browser.