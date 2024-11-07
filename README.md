# Capstone Project: Enhancing a Community Library Website

## Background Scenario

You are part of a development team tasked with enhancing the website for the Greenwood Community Library. The goal is to make the site more engaging and informative for visitors. The current website includes basic sections: Home, About Us, Events, and Contact Us. Your team decides to add a Book Reviews section and update the Events page with upcoming community events.

Two team members, Morgan and Jamie, will work on separate sections:

Morgan will add the Book Reviews section.
Jamie will update the Events page with new community events.


## Objectives

* Practice cloning a repository and working with branches in Git.

* Gain experience in staging, committing, and pushing changes.

* Create pull requests and merge them after resolving potential conflicts.


 ## Setup

 1. Create a Repository on GitHub:

 ![](./img/1.createRepo.png)

 * Name it greenwood-library-website

 * Initialize it with a README.md file

![](./img/2.reponame-readme-createrepo.png)


2. Copy the Repository to your local machine

![](./img/3.copyrepo.png)


* Clone the repository to your local machine by running the following command:

 git clone https://github.com/Joy-it-code/greenwood-library-website.git
    

 ![](./img/4.gitclone.png)

 
 
 ## Tasks


 1. **In the main branch, using Visual Studio Code editor ensure there are files for each of the web pages.**

   * home.html

   * about_us.html

   * events.html

   * contact_us.html

  
 ![](./img/6.createfile.png)


2. **Add any random content into each of the files:**

* Random content into home.html

![](./img/10.randomcontenthome.png)

* Random content into about_us.html

![](./img/7.writeforaboutus.png)

* Random content for events.html

![](./img/9.randomcontentforevent.png)

* Random content for contact_us.html

![](./img/8.randomcontentforcontactus.png)


3. Stage, commit, and push the changes directly to the main branch: (This is a simulation of the team's existing code base for the website).

   git add .
   git commit -m "first commit: Add basic web pages"
   git push origin main


![](./img/11.staging.png)

![](./img/12.commiting.png)

![](./img/13.push.png)

## **Morgan's Work: Adding Book Reviews**

1. **Create a branch for Morgan**

git branch add-book-reviews

2. **Switch to the new branch named add-book-reviews**
git checkout add-book-reviews

3. **Add a new file book_reviews.html to represent the Book Reviews section:**

touch book_reviews.html


4. **Add a random content into the file.**

![](./img/16.randomtextformorgan.png)

5. **Stage, Commit, and Push Changes**

git add .
git commit -m "Add Book Reviews section"
git push origin add-book-reviews


![](./img/17.stagecommitpushbookreview.png)

6. **Raise a PR for Morgan's work.**

![](./img/18.createpr.png)

7. **Merge Morgan's work to the main branch**

![](./img/19.mergemorgan.png)


## **Jamie's Work: Updating Events Page**

1. **Create a branch for Jamie:**

git branch update-events

2. **switch to new branch**

git checkout update-events

![](./img/20a.createbranchjamie.png)

3. **Add a new file updating_events**

![](./img/20b.createfilejamie.png)

4. **Add a random content into the file.**

![](./img/21.randontextJamie.png)

5. **Stage, Commit, and Push Changes**

git add .
git commit -m "Update Events page with new community events"
git push origin update-events

![](./img/22.stagecommitjamie.png)
![](./img/22b.gitpushjamie.png)


6.  **Raise a Pull Request for Jamie's work.**

![](./img/23.jamie'spr.png)

7. **Merge Jamie's work to the main branch**
  
![](./img/24.jamie'smerge.png)

