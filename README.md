# Project

I am using Windsurf to write. My focus is on philosophy and AI.

The folder is at writing/

This is the project structure on disk:

writing/raw
- a folder where I paste raw materials, or past notes
- this is organized by sources, or just a dump of text

writing/synthesis
- the working folder where we collect new edits, and where we write new texts
- this is organized by topics
- add a list of hashtags to each file at the top

How you should work?
- use tags to organize sections in a file
- use file names and tags to navigate around
- apply the same kind of analysis you do for code repositories to navigate the texts

## Content Ingestion Process

1. Raw Materials (`raw/`)
   - New content is added to the `raw/` directory
   - Each file contains unprocessed notes, sources, or ideas
   - Files can be organized by source or simply added as text dumps

2. Content Mapping (`MAP.md`)
   - Each file in `raw/` is analyzed and summarized in `MAP.md`
   - Summaries capture key themes, arguments, and insights
   - Each entry includes relevant tags for cross-referencing
   - Files are linked using relative paths for easy navigation

3. Synthesis (`synthesis/`)
   - New content is created here based on themes identified in `MAP.md`
   - Files are organized by topic with hashtags at the top
   - Content draws from and references the raw materials
   - Focus on developing coherent arguments and insights
