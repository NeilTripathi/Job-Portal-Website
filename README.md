# Job-Portal-Website
This repository contains Java project which helps users for applying to jobs.

Recruiter should be able to:

1. Post new jobs.
2. View our jobs.
3. View list of candidates that have applied for a job.
4. Edit profile and upload photo.

Candidate should be able to:

1. Search for jobs.
2. Applyfor a job.
3. View list of applied jobs.
4. Edit profile and upload photo and resume.

Every user should be able to register and login/logout.

Java Classes:

HomeController /Service/Repository - Shows home page
JobLocationController /Service/Repository - Managing job locations
JobPostActvityController /Service/Repository - Managing job posts and searching job posts
JobSeekerApplyController /Service/Repository - Apply for jobs
JobSeekerProfileController /Service/Repository - Managing job seeker profile
JobSeekerSaveController /Service/Repository - Managing jobs that job seeker has applied for
RecruiterProfileController /Service/Repository - Managing recruiter profile
UsersController /Service/Repository - Login/logout/regiseter

Database Entities:

JobCompany - A job company: name, logo, etc
JobPostActivity - A job post: title, description etc
JobSeekerApply - Tracks the job seekers who have applied for a job
JobSeekerProfile - Info about job seeker: name, city, age etc
JobSeekerSave - Tracks the jobs a job seeker has applied to
RecruiterProfile  - Info about recruiter: name, city, state, company etc
Skills - Info about a skill: name, experiece level, years of experience
Users: Info about a user: email, password etc
Users Type: Recruiter or job seeker
