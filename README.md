# Laxus

Gatsby starter for creating a blog

## 🚀 Installing and running the project

1.  **Dependencies install**

```shell
  npm install
```

2.  **Start project on development mode**

```shell
  npm start
```

3.  **Access your page**

```
  http://localhost:8000/
```

## 📝 Como criar um post

1.  **How to create a post**

- The post file should be at `/posts`
- The name format should be `year-month-day-post-name.md`

2.  **Insert the basic post informations**

- Inside the file, create a information structure like this:

```markdown

---
title: <post_title>
subtitle: <optional_subtitle>
description: <post_description>
date: <year-month-day hour:minute:second>
author: <author_name>
category: <front-end|back-end|what_ever>
category: ['js', 'react', 'gatsby', 'redux']
series: how to do x
---
```

3.  **Write your post**

- Let's write!

### Inserting images inside the post

1.  **Where to put the images**

- Put the images in the following folder  `/static/assets/uploads`;
- The file name shoud be `file_name.extension`

2.  **How to import**

```markdown
  ![Gatsby Logo](/assets/uploads/light.jpeg)
```

## 📝 Schedule a post

1.  **In the description of the PR, put the date that the post should be merged following the example below:**

```
/schedule 2020-09-02
```