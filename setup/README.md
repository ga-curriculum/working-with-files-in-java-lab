<h1>
  <span class="headline">Working with Files in Java Lab</span>
  <span class="subhead">Setup</span>
</h1>

## Setup

Open your Terminal application and navigate to your <code class="filepath">~/code/ga/labs</code> directory.

```bash
cd ~/code/ga/labs
```

Clone the [Working with Files in Java Lab starter code](https://git.generalassemb.ly/modular-curriculum-all-courses/working-with-files-in-java-lab-starter) repository with this command:

```bash
git clone https://git.generalassemb.ly/modular-curriculum-all-courses/working-with-files-in-java-lab-starter.git working-with-files-in-java-lab
```

> 💡 The `working-with-files-in-java-lab` at the end of this command will place the contents of the `working-with-files-in-java-lab-starter` repo into a directory named <code class="filepath">working-with-files-in-java-lab</code>.

Next, `cd` into the newly created directory:

```bash
cd working-with-files-in-java-lab
```

You don't want GA commits on your work, so remove the existing Git information from this starter code:

```bash
rm -rf .git
```

To get this work to GitHub, initialize a new Git repository:

```bash
git init
git add .
git commit -m "initial commit"
```

Make a new repository on your personal GitHub account named `working-with-files-in-java-lab`.

Link your local work to your remote GitHub repo:

```bash
git remote add origin https://github.com/<github-username>/working-with-files-in-java-lab.git
git push origin main
```

<blockquote class="warning">
  🚨 Do not copy the above command. It will not work. Your GitHub username will replace <code>&lt;github-username&gt;</code> (including the <code><</code> and <code>></code>) in the URL above.
</blockquote>

Open IntelliJ IDEA Community Edition and open the project by selecting the **Open** option on the launch screen.

Next, navigate to the `working-with-files-in-java-lab` directory you just created and open the project.

Trust the project if you are prompted.
