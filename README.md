# mr.gSEO

mr.gSEO is a dynamic SEO (prompt) toolkit for GPT verions. With the current version 0.4, the tool aids in the creation of SEO optimized blog posts by considering a variety of factors such as depth of content, blogging style, communication style, tone, reasoning framework and much more.

## Features 

### Base Config
The base configuration features of mr.gSEO include:

- **Depth Levels:** Defines the depth of the information in the content being created, ranging from 1 (suitable for speed reading) to 10 (pioneering thought).

- **Blogging Styles:** Provides a variety of blogging styles that cater to different reader categories, such as beginners, researchers, tech enthusiasts, opinion leaders, etc.

- **Communication Styles:** Offers a choice of communication styles, including storytelling, professional & formal, humorous and fun, etc.

- **Tone Styles:** Gives options for different tones to match the blog's purpose, such as feminine, encouraging, neutral, business, humorous, etc.

- **Reasoning Frameworks:** Includes different reasoning frameworks like problem solution, cause effect, comparison contrast, descriptive, narrative, etc.


### Commands
mr.gSEO supports various commands like "/test" for testing the written text, "/config" for prompting the user through the configuration process, "/outline" for creating a blog post outline, and "/start" for initiating the blog writing process, among others.


### General Rules
The tool operates under a set of general rules, such as following the writer's specified blogging style, creating a blog post outline according to the author's preferences, obeying the writer's commands, and more.


### Meta Rules and SEO Rules
These sets of rules guide the tool to create the meta description and content that are SEO-optimized.


### Writer's Preferences
The writer's preferences section allows the tool to cater the content to the writer's specific needs and writing style.


### Formats
The tool follows specific formats for base configuration, blog configurations, self-evaluation, and planning. 

## Getting Started

The JSON configuration file for initializing the tool is given with the key `init`. The command for initializing mr.gSEO is 

```
As an mr.gSEO, greet + 🔥 + version + author + execute format and options <configuration> + ask for writer's preferences
```
## Todo: 
- [ ] Add /analyze: This command performs a deep analysis of the content. It checks the consistency, coherence, grammar, punctuation, etc.
- [ ] Add /summary: This command is used to create a concise and informative summary of the blog post.
- [ ] Add /export: This command exports your completed blog post. It can export in various formats such as .txt, .doc, .pdf, etc. (With plugin)
- [ ] Create a minimalist version. 
- [ ] To be simplified current version.
- [ ] Add automatic Keyword Research: A feature that could help users find the most relevant keywords for their blog post. It could provide data like search volume, competition level, and keyword difficulty.
- [ ] Add Readability Score: An added feature that evaluates the readability of the generated blog post, providing a score based on established metrics like the Flesch-Kincaid Reading Ease formula.
- [ ] Add Image SEO: A feature to optimize images by providing ALT text suggestions and ensuring they have appropriate titles.
- [ ] Add Sentiment Analysis: A feature that evaluates the sentiment of the blog post. It could provide insight on the emotional tone of the content, which can be useful for tailoring content to the desired audience.
- [ ] Add Internal Linking Suggestions: A feature that suggests potential internal links that could be added to the blog post to improve SEO.
- [ ] Add Social Media Integration: A feature that allows users to directly share their posts on social media platforms. This could increase the visibility and reach of their content.
- [ ] Topic Clustering: A feature that suggests related topics for creating clusters of blog posts. This is a great way to boost the authority of the blog on specific topics.
- [ ] Content Gap Analysis: A feature to identify the topics that haven't been covered in the blog but are popular in the industry. This can guide the user on what to write next.


