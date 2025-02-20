# Purpose

This repo was an experiment I conducted attempting to convert rough work experience details into a detailed context I could leverage to produce an updated resume and online profile.

# Structure

 - originals: converted to markdown, raw, rough, original files I used to create the context.
 - gpt-output: prompts used (rough but effective), and cleaned, condensed output of resume, summaries, and work experience.
 - root: final resume in markdown and stylesheet to support github action leveraging pandoc and wkhtmltopdf to rapidly generate new versions of resumes.

# Process

1. I started leveraging the above originals and prompts to clean/convert my work experience notes into a model context and output cleaned files.
2. I then selectively moved the appropriate work experience in/out of the final resume in the root of the project.
3. I also moved select summaries to LinkedIn and other online profiles to ensure consistency.
4. As I make changes to the root resume I was able to rapidly produce job matched resume versions.
5. Version control would also let me rapidly restore previous versions of my resume to prevent drift from one job to the next (restore to root after producing specific).
6. I also leveraged [SkillSyncer](https://skillsyncer.com/) to review my resume against job descriptions to make continuous improvements. Those changes I would then integrate back into the "root" resume to output a new version and re-evaluate. 
7. I would leverage the job description and context model to make a shell of a cover letter. Prompts not included but self explanatory.
8. Last but not least I would then leverage the above to create a thank you after a successful interview.

# Tips

 - When you are busy at a job, work to at least keep a rough list of your contributions.
 - It is good to have a rich set of work experience you can choose to move in/out of your resume.
 - I would pay for whichever LLM you want to use to have a larger context model that is maintained over time.
 - LinkedIn Premium is also great to get you to the right jobs that you are already highly qualified for. Leveraging this material also improved the results I was provided in the job search.
 - Don't forget to network. Nothing is more powerful than the network effect during a search.

If you have questions [contact me](mailto:bdmurray+github@gmail.com)
