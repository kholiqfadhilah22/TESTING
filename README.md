## 🛠️ Installation

**DOWNLOAD** this repository and **UPLOAD** to your new own repository to make the changes in your local system.

```git-bash
git clone https://github.com/YOUR-USERNAME/TESTING
cd TESTING
```

Now, this command creates a directory named *node_modules* and installs all the required packages in it.

```javascript
npm i
```

## Configuration

Please copy `.env_template` into `.env` below:

```shell
cp .env_template .env
```

Then set your own **credentials** below:

```shell
GIT_NAME=""         # Your name
GIT_EMAIL=""        # Your email
REPO_URL=""         # Repo URL
BRANCH_NAME="main"  # Branch
```

## Run

Finally, run the project to see what the moment package does.

```javascript
node index.js
```
