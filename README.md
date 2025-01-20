# leet2git

`leet2git` is an extension that automatically commits and pushes your LeetCode solutions to your GitHub repository. With this tool, you can effortlessly track your progress and build a portfolio of your LeetCode solutions without needing to manually commit and push them.

## Features

- **Automatic GitHub commit**: Push your solutions to your GitHub repository with minimal effort.
- **Supports Markdown and Code**: Automatically formats your LeetCode solution into a markdown file with the correct question title, description, and your solution code.
- **Integration with LeetCode**: Fetches the problem details directly from the LeetCode problem page.
- **Customizable commit message**: Set your own commit messages for each solution.
- **Easy setup**: Simply clone the repo, configure your settings, and start pushing your LeetCode solutions to GitHub.

## How It Works

- This extension fetches the problem's description from the LeetCode problem page using the meta tags in the HTML.
- It formats the problem description and your solution code into markdown.
- The markdown file is then committed to your GitHub repository with the commit message of your choice.
- It automatically pushes the changes to GitHub, keeping your repository up to date.

## Setup

### Prerequisites

- Git should be installed and set up on your machine.
- A GitHub account with a repository to store your LeetCode solutions.
- Node.js and npm installed.

### Steps to Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/leet2git.git
   cd leet2git

2. go to extensions setting(turn on dev mode on extension seeting) and click load unpack
3. load this extension , fill up all info , click the auto update button


Once setup is complete, you can start using leet2git to automatically commit and push your solutions.

## Usage

1. **Submit your LeetCode solution**: After solving a problem on LeetCode, This extension will automatically add it to the github repo.

2. **Generate the markdown**: The extension will convert the problem description and your solution into markdown format.

3. **Commit and push**: The markdown file is automatically committed to your GitHub repository with a custom commit message.

4. **View your solutions**: Check your GitHub repository for all the problems you’ve solved and their solutions.


## Acknowledgments

This project was inspired by [Leet-To_Github](https://github.com/Willisaur/LeetCode-to-GitHub). While the original repository laid the foundation for automating LeetCode solution uploads, it lacked several important features. I expanded upon it by adding these missing features and introducing numerous new functionalities, making the tool more comprehensive and user-friendly. 

Special thanks to the creator of the original repository for providing the backbone of this project!

