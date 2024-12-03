# VS Code Custom Snippets

A collection of curated custom snippets for various programming languages to boost your productivity in VSCode.

## 🚀 How to Use

### 1. Fork the Repository
Click the Fork button in the top-right corner of this repository’s GitHub page to create a copy under your account.

### 2. Clone the Repository

```bash
git clone https://github.com/your-username/your-snippets-repo.git
```

### 3. Set Up Snippets

Create a [symbolic link](https://en.wikipedia.org/wiki/Symbolic_link#:~:text=9%20External%20links-,Overview,exists%20independently%20of%20its%20target.) to use these snippets in VSCode. By default, VSCode's custom snippets are stored at `~/Library/Application\ Support/Code/User/snippets`, but if your path is different, change accordingly.

```bash
ln -s /path/to/your-snippets-repo/* ~/Library/Application\ Support/Code/User/snippets
```

Replace `/path/to/your-snippets-repo` with the path to your cloned repository.

### 4. Stay Updated

If you want to pull updates from the original repository:

Add the original repo as a remote:

```bash
git remote add upstream git@github.com:mrjwei/vscode-snippets.git
```

Fetch and merge updates from the original repository:

```bash
git fetch upstream
git merge upstream/main
```

### 5. Reload VSCode

After linking, reload VSCode to apply the snippets:

- Open Command Palette (Cmd+Shift+P or Ctrl+Shift+P)
- Type `Reload Window` and select it.

## ✍️ How to Add Your Own Snippets

### 1. Edit or Add Snippets

Modify existing .json files for the language you want or add new .json files if the language isn’t covered.

### 2. Commit and Push Changes

```bash
git add .
git commit -m "Add/update snippets"
git push
```




