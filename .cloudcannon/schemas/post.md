---
title: "Post"
fields:
  - {
      type: "string",
      label: "Title",
      comment: "Enter the post title."
    }
  - {
      type: "text",
      label: "Content",
      comment: "Main content of the post.",
      multiline: true
    }
  - {
      type: "image",
      label: "Feature Image",
      comment: "Upload an image that will be featured at the top of the post."
    }
  - {
      type: "select",
      label: "Category",
      options: {
        values: ["News", "Tips", "Reviews"],
        allow_empty: false
      },
      comment: "Select the category for this post."
    }
  - {
      type: "tags",
      label: "Tags",
      comment: "Add tags to help categorize this post."
    }
  - {
      type: "boolean",
      label: "Published",
      comment: "Toggle whether this post is visible to the public."
    }
---
