# Portfolio Website



A personal portfolio website that showcase my skills, background, and achievements



\### Local environment set up



1\. Create the project folder 

```git

mkdir -p portfolio \&\& touch ./portfolio/index.html ./portfolio/style.css

```



2\. Create the folder containing the picture

```linux

cd /portfolio \&\& mkdir img

```



3\. Initialize the local  project folder as a git repository to track changes.



```git

cd portfolio/

git init .

```



4\. Proceed the the Website development

\## Push Code to GitHub



1\. Create a \*\*new public repository\*\* on GitHub.

&nbsp;   

2\. Add the newly created remote repository to local Git repository 

```git 

git remote add origin https://github.com/charlemanxD/PLP-Hackathon-1-Portfolio-Website.git

```



3\. rename the current Git branch to `main`



```git

git branch -M main



```



4\. \*\*Pushes local changes to the remote repository\*\*



```git

git push -u origin main



```

\## Deploying Portfolio to Vercel



\### Step 1: Create a Vercel Account



The easiest way for  me is to link it to my GitHub account.



1\. Go to the \[Vercel website](https://vercel.com "null").

&nbsp;   

2\. Click on \*\*"Sign Up"\*\* or \*\*"Log In"\*\* you already have an account.

&nbsp;   

3\. Choose to sign up with your \*\*GitHub account\*\*. This will authorize Vercel to access your GitHub repositories.

&nbsp;   

\### Step 2: Importing Project



Once logged into Vercel:



1\. On the Vercel dashboard, click \*\*"Add New"\*\* > \*\*"Project"\*\*.

&nbsp;   

2\. Vercel will displays a list of GitHub repositories. Find the repository for your portfolio and click \*\*"Import"\*\*.



\### Step 3: Configure and Deploy



1\.  For a simple static site, I left all the default settings.

&nbsp;   

2\. The \*\*"Framework Preset"\*\* was set to \*\*"Other"\*\*. I left it as it was.

&nbsp;   

3\. Under \*\*"Root Directory"\*\*, I also let default configuration and ensured it points to the folder(toot) containing my `index.html` file. .

&nbsp;   

4\. Finally, click the \*\*"Deploy"\*\* button.



\### 
Step 4: Check Live URL

<img width="1084" height="398" alt="Screenshot 2025-08-03 213953" src="https://github.com/user-attachments/assets/2e926a08-2fee-4e6b-944f-9e2887c9bf1a" />

\##### Live portfolio website URL

https://plp-hackathon-1-portfolio-website.vercel.app/

