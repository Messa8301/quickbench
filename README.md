# 🏃 quickbench - Run AI agent tests locally

[![Download quickbench](https://img.shields.io/badge/Download-quickbench-1f6feb?style=for-the-badge)](https://github.com/Messa8301/quickbench)

## 📦 What quickbench does

quickbench is a local benchmark tool for AI agents. It helps you run tests on your own computer with no cloud setup.

Use it to:

- compare agent runs
- check result quality
- keep tests repeatable
- store signed benchmark results
- work offline
- avoid sending data to cloud services

It is built for people who want clear results and a simple local setup.

## 💻 Before you start

You need:

- a Windows PC
- internet access for the first download
- a recent version of Node.js if you want to run from source
- enough free disk space for test data and results

For most users, the main goal is simple: visit the download page, get the app, and run it on your PC.

## ⬇️ Download quickbench

Open the download page here:

https://github.com/Messa8301/quickbench

From there, get the latest release or the main project files, then follow the steps below to run quickbench on Windows.

## 🪟 Install on Windows

1. Open the download page in your browser.
2. Download the Windows build or the project files.
3. If the download comes as a ZIP file, right-click it and choose Extract All.
4. Open the extracted folder.
5. If you see an installer, double-click it and follow the prompts.
6. If you see a terminal app or project files, use the run steps below.

If Windows asks for permission, choose Yes so the app can run.

## ▶️ Run quickbench

If you downloaded a ready-to-run Windows app:

1. Open the app file.
2. Wait for the main screen to load.
3. Start a demo benchmark or open your own test set.

If you downloaded the source files:

1. Open Command Prompt.
2. Move into the quickbench folder.
3. Run:

npm run demo

This starts the demo benchmark flow and gives you a fast first run.

## 🧭 First run checklist

When quickbench opens, check these items:

- the app starts without errors
- the demo benchmark loads
- your test data appears in the list
- the run begins and finishes on your PC
- results save to a local folder

If you run the demo, you should see a full eval flow without needing cloud access.

## 🧪 What you can test

quickbench helps you measure how an AI agent performs in common tasks such as:

- task completion
- instruction following
- tool use
- result consistency
- response quality
- run-to-run repeatability

This makes it useful for local AI work, model checks, and agent testing.

## 🔒 Privacy and local use

quickbench is built for local-only use. That means your benchmark data stays on your machine.

This setup helps when you want:

- no cloud uploads
- no shared test data
- full control over results
- offline testing
- simple local review

It also fits work where you need signed results for later review.

## 🧾 Signed benchmark results

quickbench can use cryptographic signatures for benchmark output. This helps you know when a result came from a specific run and was not changed later.

That is useful when you need:

- stable test records
- traceable results
- repeatable evaluations
- local proof of what ran and when

## 🛠️ Common setup path

For a simple Windows setup, use this path:

1. Visit the GitHub page.
2. Download the latest release or project files.
3. Extract the files if needed.
4. Open the app or run `npm run demo`.
5. Review the results on your computer.

If you want to run more than the demo, keep the folder in a place you can find again, such as Documents or Desktop.

## 📁 Suggested folder layout

You can keep quickbench files like this:

- `quickbench` folder for the app
- `benchmarks` folder for test cases
- `results` folder for saved runs
- `logs` folder for run history

This helps you stay organized when you compare runs over time.

## ⚙️ Basic use

A typical quickbench flow looks like this:

1. Choose a benchmark.
2. Run an AI agent on the task.
3. Wait for the run to finish.
4. Review the output.
5. Compare the result with past runs.
6. Save the benchmark record.

Use the same test data each time if you want fair comparisons.

## 🧰 Useful tips

- Keep your test prompts short and clear
- Use the same settings for each run
- Save old results before you change a setup
- Start with the demo before you use your own tests
- Run on the same PC when you want steady comparisons

These habits make your results easier to trust.

## 🧩 Who this is for

quickbench fits:

- AI agent builders
- product teams that test models
- researchers who need local evals
- developers who want repeatable checks
- users who want offline testing
- teams that care about privacy and data control

You do not need to be a developer to use the demo flow. The app is set up to get you to a first run fast.

## 📚 Project topics

This project covers:

- agent evaluation
- AI testing
- benchmark runs
- local AI
- offline-first use
- privacy-first setup
- reproducible ML work
- TypeScript
- Node.js
- MLOps
- model evaluation

These topics match a tool built for local benchmark work on AI agents.

## ❓ Help with common issues

If the app does not open:

- check that the files finished downloading
- extract the ZIP file first
- try running it from a simple folder path
- make sure Windows did not block the file
- try the demo command again from the project folder

If the demo does not start:

- check that Node.js is installed
- open Command Prompt in the quickbench folder
- run `npm run demo` again
- make sure you are in the right folder

If results do not save:

- confirm that you have write access to the folder
- try a folder in Documents
- close the app and open it again

## 🔍 File types you may see

Depending on the download path, you may see:

- `.exe` for a Windows app
- `.zip` for a packaged download
- `package.json` for a Node.js project
- `README.md` for setup steps
- folders with benchmark data and results

Each file type has a simple use. The app file runs the tool. The ZIP file needs extraction first. The project files may need the demo command.

## 🧭 Quick path for first use

1. Visit https://github.com/Messa8301/quickbench
2. Download the Windows file or project files
3. Extract the download if needed
4. Open the app or run `npm run demo`
5. Load a benchmark
6. Review the result on your PC