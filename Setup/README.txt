GITHUB FOR UNITY

Github for Unity is a feature that allows you to use Github directly in Unity. It's pretty nice.

Unfortunately, this app doesn't support cloning existing repos. However, with a little outside setup, we can work around it and make commits to an existing repo anyway.

There are three main things to do: 1) Cloning the repo, 2) Creaing a Unity Project with the repo, and 3) Setting up Github for Unity

CLONING THE REPO
	1) Download Github Desktop at https://desktop.github.com/
	2) Sign in (or sign up)
	3) Select "Clone Repository from the Internet"
	4) Input the repo given on slack for Repository URL and choose a local path
	5) Click "Clone"

	Now you have a local repository for Github.

CREATING A UNITY PROJECT WITH THE REPO

	1) Create a new project in Unity
	2) Under your path variable, copy the path for your local repository and paste it under "Location"
	3) Click "CREATE"

	From here, everything you save will go directly to the repo, and you can commit and push in Github Desktop. However, we can do better - we can set up Github so we can use it directly in the editor.

Setting up Github for Unity
	1) Go to Window -> Asset Store
	2) Search for "Github for Unity"
	3) Purchase it (it's free), download it, and import it
		- If it asks for any confirmation, click "Yes"

	4) Go to Window -> Github

	Now you have Github in Unity

GENERAL GITHUB PRACTICE

	I probably don't have to write this, but just for good hygiene:
		1) Whenever you're going to commit changes, first fetch, then pull, then push

