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
