# Agent Hub
I built Agent Hub as a fork of the amazing work done by the maintainers of msitarzewski/agency-agents. I wanted to create a more personalized AI agency experience, with a focus on localization and ease of use.
## Installation
To get started, simply run the install script: `install.sh --tool copilot`. This will set up the necessary files and directories for you.
## Usage
After installation, you can localize agent names to your preferred language using the `localize-agents-zh.ps1` script. Simply run `powershell -ExecutionPolicy Bypass -File scripts/i18n/localize-agents-zh.ps1` to get started.
## What I changed
I added a new localization script to support Chinese (zh-CN) and made some minor improvements to the overall code structure and readability.
## Acknowledgements
Big thanks to the maintainers of [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents) -- this project started as a fork of their work and I built on top of it.