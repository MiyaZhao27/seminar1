This repository contains material and an instruction for seminar 1. 

## Setting Up GitHub

### 1. Install Git

#### Windows:
- Go to: https://git-scm.com/download/win
- Download and run the installer
- **Recommended settings**: accept all defaults

#### macOS:
Check if git is installed:
- Open terminal and type `git`
- If Git is not installed, macOS will prompt you to install it.

If this does not work, go to https://git-scm.com/downloads/mac (use Homebrew) or type in terminal:
```bash
brew install git
```

### 2. Check that Git is installed

In your terminal:
```bash
git --version
```

### 3. Create a GitHub account

- Go to https://github.com
- Sign up with your email, username, and password
- Verify your email address
- Log in to GitHub with your account details

You can apply for student benefits via https://education.github.com/benefits?type=student

### 4. Configure Git with your GitHub identity

In your terminal:
```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

### 5. Set up SSH authentication

- Navigate to the folder where you would like to locate the repository on your computer with `cd` (change directory)

- Then, go to the ME314 repository on Github: [https://github.com/me314-lse/lectures.git](https://github.com/me314-lse/seminar1.git)

- On your repository page on GitHub, click on **Code** and copy the URL (https)

- In your terminal:
```bash
git clone <url>
```

- You will now be asked to enter your user name and password, for this we will have to create an access token as the last step in this setup (note: some users are instead asked at this point to enter their password via a pop-up window - in this case, no access token has to be created manually and you can skip the next slide)

- On GitHub, click on the alias in the upper right hand corner → **Settings** → **Developer settings** → **Personal access tokens** → **Tokens (classic)** → **Generate new token**

- Pick a name, e.g. "repo", choose an expiration, select "repo" (this will allow to access private and public repos from the command line), and click **Generate token**

- Copy the token (it will only be visible once) and enter it somewhere visible on your machine (i.e. in a note)
- Now go back to the command line, enter your GitHub user name and as password enter the token:

**Attention:** you will have to enter the token manually, it will not work via copy/paste. Also, be prepared to not see what you are typing into the terminal as it will not be shown for security reasons.

- Now delete the token that you have stored.

## Set Up VS Code

### Installing VS Code and Quarto

- Go to [https://code.visualstudio.com/](https://code.visualstudio.com/)
- Select your OS
- Follow instructions

- Go to [https://quarto.org/docs/get-started/](https://quarto.org/docs/get-started/).
- Select your OS
- Follow the instructions

  
Now open VS Code and click on **File** → **Open…** and select the `Seminar1.qmd` file.
