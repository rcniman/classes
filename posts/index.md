## Welcome to Rising Roots!

Well, specifically my classes there. For 2023-4, I'm teaching two classes:
- [History of Popular Music](History of Popular Music/History of Popular Music)
- [Puzzlemasters](Puzzlemasters)



## Getting started
### I don't need this

Steps to run it on your local machine:
1. Clone this [Github repo](https://github.com/TuanManhCao/digital-garden)
2. Install [yarn](https://classic.yarnpkg.com/lang/en/docs/install/#mac-stable) package manager 
3. Copy all of your **markdown** file (`.md` only) and folder to `/posts/` **except** `/posts/index.md` file
4. Go to root folder of your project, run `yarn && yarn run dev`
5. Open this link in your browser http://localhost:3000/ 

If you prefer video content have a look at my 📺 [walk through video](https://youtu.be/7_SmWA-_Wx8) 

### Publish to the internet

Setup environment (with Netlify)
1. Create your Github account and clone [my repository](https://github.com/TuanManhCao/digital-garden)
2. Create Netlify account and follow [this instruction](https://www.netlify.com/blog/2020/11/30/how-to-deploy-next.js-sites-to-netlify/) 


Your normal workflow for publishing content, after initial setup is:
1. Simply writing your content in Obisidian (or your favourite Markdown editor)
2. Commit your changes and Push it to your Github repo


If you prefer video content, watch my 📺 [walk through video](https://youtu.be/n8QDO6l64aw) here 

These are just some basic features for MindStone v1, many more are coming (if I find enough of interest and this will probably a premium/paid option):
- 🎯 Obsidian, Notion, VSCode Plugin 
- 🎯 Page Preview (like Obsidian Core plugin)
- 🎯 Andy Sliding pane
- 🎯 Full text search with `Cmd + K`
- 🎯 Infinite canvas for browsing through notes and connections

### Some know issues
This an early version of MindStone, which mean there are bugs and issues. Below are some known issues, that I plan to work on:
- Image link in wiki link style is not supported yet. `![[Image_link.png]]` will not work yet.  see work around below
- Graphview does not load when clicking on side-bar or click node on graphview, browser reload will refresh it state
- Graph view layout and interaction is still very rough. More UI/UX improvements are needed.
- Transclusion is not working yet.

[[]]