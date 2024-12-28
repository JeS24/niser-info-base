## NISER InfoBase ℹ️

This repository stores information about the various academic and administrative processes at the National Institute of Science Education and Research (NISER), Bhubaneswar, India. The posts are written by student volunteers of NISER.

The same is hosted at [TBD]().

> [!TIP]
> Suggest a new post in the [Issues](https://github.com/JeS24/niser-info-base/issues/new) section.

> [!NOTE]
> For people looking to add new posts or to edit the site, please refer to [`AstroPaper.README.md`](./AstroPaper.README.md) for the setup and configuration of this website.
> See [`noc-visa-conf-phd.md`](https://github.com/JeS24/niser-info-base/edit/main/src/content/blog/noc-visa-conf-phd.md) in edit mode for an example post.


### ToDo
- [x] Basic setup.
- [x] Edit About.
- [x] Add a dummy post template.
- [x] Make "Suggest Changes" link out to this repo's GitHub Issues.
- [ ] Add a post template.
- [ ] Update GitHub Templates for adding new posts.
  - [ ] Issue templates
  - [ ] PR templates
- [ ] Edit "How to add new posts?" below.
- [ ] Host this somewhere.
- [ ] Add support for multiple authors.
- [ ] Copy over features from https://github.com/JeS24/smlab-talks/:
  - [ ] Base URL support
  - [ ] Support for searching multiple fields
- [ ] Edit Themes & Styles for light and (especially) dark themes.
- [ ] Remove unnecessary socials.
- [ ] Add an Edit Timeline component to each post.
- [ ] Categories (separate from Tags)
  - [ ] Add Categories to posts.
  - [ ] Add a Categories page.


### 📚 How to add new posts? [⌛ DONOTUSE - WIP - Dec 28, 2024]

1. Fork this repository.
2. Clone the forked repository.
3. `cd` into the repository.
4. Copy the `./src/content/blog/YYYY-MM-DD--FirstName--ShortTalkTitle.md.template` file to a new file with the appropriate filename and `.md` extension.
5. Fill in the details in the new file. Follow the `TODO:` tags in the template.
6. Delete the `TODO:` tags once you have filled in the details.
7. For the frontmatter, ensure that there is no `:` in the title, author, or other tags. If there are any, replace them with ` - `.
8. Add your slides to the `./public/assets/slides/` folder. The slides should be named `YYYY-MM-DD--FirstName--ShortTalkTitle.pdf` (same as the post filename with a `.pdf` extension).
9. Push the changes to your forked repository.
10. Create a pull request to the main repository.
11. Once the pull request is merged, the website will be updated automatically. 🥳

### ✨ Feedback & Suggestions

For queries, suggestions, feedback, or issues, please [create an issue](https://github.com/JeS24/niser-info-base/issues/new).

### 📜 License

Content is released under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/), Copyright © NISER Coding Club, National Institute of Science Education and Research, Bhubaneswar, India

Template licensed under the MIT License, Copyright © 2024 [Sat Naing](https://satnaing.dev)

---
Thanks [Sat Naing](https://satnaing.dev) 👨🏻‍💻 and [contributors](https://github.com/satnaing/astro-paper/graphs/contributors) for the template. This repo adds some extra features, such as support for a `base` URL, fuzzy search extended to authors, and more.
