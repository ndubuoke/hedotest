# How I Deployed a Simple Static Website Using GitHub and GitHub Pages

In this guide, I’ll walk you through the exact steps I used to deploy a multi‑page static website, including how I structured my files, enabled GitHub Pages, and finally accessed my live site at:

👉 **https://hedobriggs.github.io/website/**

---

## Step 1: Create a GitHub Repository

Start by creating a new GitHub repository:

1. Go to **github.com**
2. Click **New Repository**
3. Give it a name (I used **website**)
4. Choose **Public**
5. Click **Create Repository**

This repository will hold all the files for your static website.

---

## Step 2: Create a Folder for Your Website Files

Inside the repository, create a folder to store your website pages.  
I named mine: website



Inside this folder, I added all my website files:

- `index.html`
- `pipeline.html`
- `about.html`
- `styles.css`
- `script.js`
- `diagram.webp` *(my architecture diagram)*

This structure is important because GitHub Pages will serve this folder as the root of your website.

---

## Step 3: Upload Your Files to GitHub

To upload your files:

1. Open your repository  
2. Click into the **website** folder  
3. Select **Add file → Upload files**  
4. Drag and drop your HTML, CSS, JS, and image files  
5. Click **Commit changes**

Your files are now stored in GitHub and ready to be published.

---

## Step 4: Enable GitHub Pages

This is the magic step that turns the folder into a live website.

1. Go to your repository  
2. Click **Settings**  
3. Scroll down to **Pages**  
4. Under **Source**, choose:
   - **Branch:** `main`
   - **Folder:** `/website`
5. Click **Save**

GitHub will take a few seconds to build your site.

Once it’s ready, GitHub shows a green success message with your live URL.

Mine was:

👉 **https://hedobriggs.github.io/website/**

This means your static website is now publicly available on the internet.

---

## Step 5: Test Your Pages

Because I created multiple pages (`index.html`, `pipeline.html`, `about.html`), I tested each one by visiting:

- **Home:**  
  https://hedobriggs.github.io/website/

- **Pipeline:**  
  https://hedobriggs.github.io/website/pipeline.html

- **About:**  
  https://hedobriggs.github.io/website/about.html

Everything loaded correctly once the file names matched exactly.

---

## Lessons Learnt from an Issue That Occurred

### **Homepage Image Was Not Rendering**

At first, my homepage image was not rendering because the `diagram.webp` file was not included in the repo.

### **Fixing the Image Issue**

The fix was simple:

- I uploaded the file into the **website** folder  
- I ensured the filename matched exactly (`diagram.webp`) as referenced in `index.html`

Immediately after committing the change, GitHub Pages rebuilt the site and the image displayed correctly.

---

## 🎉 Final Result

After following these steps, my static website was fully deployed and accessible online at:

👉 **https://hedobriggs.github.io/website/**

