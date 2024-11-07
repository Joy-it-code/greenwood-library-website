 

---

# Capstone Project: Enhancing a Community Library Website

## Background Scenario

You are part of a development team tasked with enhancing the website for the Greenwood Community Library. The goal is to make the site more engaging and informative for visitors. The current website includes basic sections: Home, About Us, Events, and Contact Us. Your team decides to add a Book Reviews section and update the Events page with upcoming community events.

Two team members, Morgan and Jamie, will work on separate sections:

- **Morgan** will add the Book Reviews section.
- **Jamie** will update the Events page with new community events.

## Objectives

- Practice cloning a repository and working with branches in Git.
- Gain experience in staging, committing, and pushing changes.
- Create pull requests and merge them after resolving potential conflicts.

## Setup

### 1. Create a Repository on GitHub:

1. Name the repository `greenwood-library-website`.
2. Initialize it with a `README.md` file.

   ![Create Repository](./img/1.createRepo.png)

   ![Repository Name and README](./img/2.reponame-readme-createrepo.png)

### 2. Clone the Repository to Your Local Machine

Clone the repository using the following command:

```bash
git clone https://github.com/Joy-it-code/greenwood-library-website.git
```

![Git Clone](./img/4.gitclone.png)

## Tasks

### 1. Ensure Basic Web Pages Exist

In the main branch, using Visual Studio Code or another editor, ensure the following files are created:

- `home.html`
- `about_us.html`
- `events.html`
- `contact_us.html`

   ![Create Files](./img/6.createfile.png)

### 2. Add Content to Each Page

Add random content to each of these files:

- **`home.html`**:

   ![Random Content for Home](./img/10.randomcontenthome.png)

- **`about_us.html`**:

   ![Content for About Us](./img/7.writeforaboutus.png)

- **`events.html`**:

   ![Random Content for Events](./img/9.randomcontentforevent.png)

- **`contact_us.html`**:

   ![Random Content for Contact Us](./img/8.randomcontentforcontactus.png)

### 3. Stage, Commit, and Push Changes

Stage, commit, and push changes to the main branch to simulate the team’s existing codebase.

```bash
git add .
git commit -m "first commit: Add basic web pages"
git push origin main
```

![Staging](./img/11.staging.png)
![Committing](./img/12.commiting.png)
![Pushing](./img/13.push.png)

---

## Morgan's Work: Adding Book Reviews

### 1. Create a Branch for Morgan

```bash
git branch add-book-reviews
```

### 2. Switch to the `add-book-reviews` Branch

```bash
git checkout add-book-reviews
```

### 3. Add the `book_reviews.html` File

```bash
touch book_reviews.html
```

### 4. Add Content to `book_reviews.html`

Add random content to the file.

   ![Content for Book Reviews](./img/16.randomtextformorgan.png)

### 5. Stage, Commit, and Push Changes

```bash
git add .
git commit -m "Add Book Reviews section"
git push origin add-book-reviews
```

![Stage, Commit, Push for Book Reviews](./img/17.stagecommitpushbookreview.png)

### 6. Create a Pull Request for Morgan’s Work

   ![Create PR for Morgan](./img/18.createpr.png)

### 7. Merge Morgan’s Work to the Main Branch

   ![Merge Morgan’s Work](./img/19.mergemorgan.png)

---

## Jamie's Work: Updating Events Page

### 1. Create a Branch for Jamie

```bash
git branch update-events
```

### 2. Switch to the `update-events` Branch

```bash
git checkout update-events
```

   ![Create and Switch to Jamie's Branch](./img/20a.createbranchjamie.png)

### 3. Add a New File `updating_events`

   ![Create File for Jamie](./img/20b.createfilejamie.png)

### 4. Add Content to the New File

Add random content to the file.

   ![Content for Updating Events](./img/21.randontextJamie.png)

### 5. Stage, Commit, and Push Changes

```bash
git add .
git commit -m "update file"
git push origin update-events
```

   ![Stage, Commit for Jamie](./img/22.stagecommitjamie.png)
   ![Push for Jamie](./img/22b.gitpushjamie.png)

### 6. Create a Pull Request for Jamie’s Work

   ![Create PR for Jamie](./img/23.jamie'spr.png)

### 7. Merge Jamie’s Work to the Main Branch

   ![Merge Jamie’s Work](./img/24.jamie'smerge.png)

---

