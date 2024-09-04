# Welcome to the Unstructured Technical Challenge!

This application provides a GUI to interact with the [Unstructured Serverless API](https://unstructured.io/api-key-hosted). It may look quite complete, but there are still plenty of bugs to fix before this application is ready to launch.

Please [duplicate](https://help.github.com/articles/duplicating-a-repository/) this repository on Github, and [make the repository private](https://help.github.com/articles/setting-repository-visibility/). We will coordinate who to add as collaborators later.

All we want you to do at this point is get it installed, get familiar with the code, and [provision an API Key](https://unstructured.io/api-key-hosted). Running it in the browser and messing around is also recommended, but we aren't asking you to do any coding outside the interview!

If you have any problems at all, please reach out to your interview coordinator to pair you up with someone to fix whatever issue you might be having. **We ask each other for help all the time, don't be shy if you get stuck!**

Once you have the project running you should see something like the image below at [http://localhost:5173/](http://localhost:5173/).

![an API GUI, labeled "Unstructured.io API GUI." The interface consists of five steps:Step 1: A field to input the "Unstructured.io API Key."Step 2: A section where users can select the files they want to process, with a button that says "Select a file to upload" and an image of a file icon.Step 3: Users can select a strategy for processing documents. There are four options:Fast default, currently selected.High Resolution: Suitable for PDFs with embedded text in images or for greater precision in recognizing element types.OCR Only: Runs documents through Tesseract for OCR.Auto: Selects the best mode for processing, with fallback to "hi_res" if needed.There's an option to expand "Optional Settings."Step 4: A button labeled "Process selected documents" to submit the selected files for processing.Step 5: A large black box titled "Explore and download the generated JSON" with the text "Upload files to see results.](./screenshots/screenshot.png)

## Recommended Documentation

- [Remix docs](https://remix.run/docs)
- [Unstructured Serverless API docs](https://docs.unstructured.io/welcome)

## Dependencies

Run the install command:

```sh
npm install
```

## Development

Run the dev server:

```sh
npm run dev
```

## Deployment

First, build your app for production:

```sh
npm run build
```

Then run the app in production mode:

```sh
npm start
```
