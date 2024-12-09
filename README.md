# sjtu-irving-t-ho-scholarship.github.io

Theme: https://github.com/Vimux/Mainroad

### Update the website

> Make sure that you have [installed Hugo](https://gohugo.io/getting-started/quick-start/#prerequisites).

First, modify the content in the `content` folder. For example, to add new fellows, you should change the file
`content/post/fellows.md`; to add photo stories, you can add new files in the `content/photostories` folder. Photos should be put in the `static/img` folder.

To preview the website locally, run the following command 
```bash
hugo server -D
```
at the root of the repository and view it at http://localhost:1313/.

After you are satisfied with the changes, run the following command to update the website
```bash
hugo -D --destination docs
```

Finally, commit and push the changes to GitHub.

You may refer to [Mainroad](https://github.com/Vimux/Mainroad) if you encounter any problems with the theme, which is located in the `themes` folder in this repository.