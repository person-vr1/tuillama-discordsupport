## Information
This is a continued version of tuillama by the user 'astingraye', but instead everything will be rewritten with discord support. You can easily toggle it on and off using the .env file that will be created.
Tuillama-DiscordSupport will also contain automatic switching between scripting model and conversation model, and if you want you can use a uncensored model.

## Settings
Your .env file should look like this:
```env
OLLAMA_ENDPOINT=localhost:11434
OLLAMA_MODEL=qwen2.5
DISCORD_SUPPORT=false
DISCORD_TOKEN=NzYwMjExMzk2MzY0MzEwMTg1.XYg-5A.fy5YJh9XUJbV6s2lw_0Veqkj5z4
```
### (THE DISCORD TOKEN IS A PLACEHOLDER, IT IS NOT REAL AND YOU SHOULD NEVER SHARE YOUR DISCORD TOKEN!!!)
Of course, you can change the model to your liking, but the OLLAMA_ENDPOINT should never change.

## Prerequisites
- Node.js 20.x or higher (i use v22.11.0)
- Windows, Linux, or if it works, macOS (i am not creating a vm just to test it out).

## Dependencies
None, heres the nodejs dependencies i installed in the project though:
- ink
- react 

## Installation
1. Clone the repository:
```
git clone https://github.com/person-vr1/tuillama-discordsupport.git
cd tuillama-discordsupport
```
2. Install the dependencies and start the project:
```
npm install
npm start
```

## Notes from me
This project will not be as good as the other one, just adds a few more features, but if theres any bugs, report it in the issues tab.

## Last Updated
This README was last updated on **1th of December**.

### This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
