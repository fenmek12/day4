# How to Use HTML and CSS Files on GitHub

## 1. Uploading HTML and CSS Files to GitHub

1. Create a GitHub repository (if you haven't already).
2. Navigate to your repository and click on **Add file > Upload files**.
3. Select your **.html** and **.css** files and upload them.
4. Commit the changes by clicking **Commit changes**.

## 2. Accessing Your HTML File

### Method 1: Opening the File Directly
- Once uploaded, go to your repository and click on your HTML file.
- Click on the **Raw** button.
- Copy the URL and open it in your browser (this method may not load CSS properly).

### Method 2: Using GitHub Pages
1. Go to your repository's **Settings**.
2. Scroll down to the **Pages** section.
3. Under "Branch," select **main** (or the branch where your HTML file is located) and click **Save**.
4. GitHub will generate a link to access your HTML file as a webpage (e.g., `https://yourusername.github.io/repositoryname/`).
5. Ensure your CSS file is linked correctly in your HTML file.

## 3. Linking CSS to HTML
Make sure your HTML file includes a link to your CSS file, like this:
```html
<link rel="stylesheet" href="styles.css">
```
Place both files in the same directory for proper styling.

## 4. Cloning the Repository to Your Local Machine
If you prefer working locally:
```bash
git clone https://github.com/yourusername/repositoryname.git
cd repositoryname
```
Then open the **.html** file in your browser.

## 5. Editing Files and Pushing Changes
If you edit the files locally, push the changes back to GitHub using:
```bash
git add .
git commit -m "Updated HTML and CSS"
git push origin main
```

Now your changes will be live!

---
This guide helps you host and use your HTML and CSS files efficiently on GitHub. Happy coding!

