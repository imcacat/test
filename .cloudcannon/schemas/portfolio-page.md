---
title: "Portfolio Page"
fields:
  - {
      type: "string",
      label: "Title",
      comment: "Enter the title of the portfolio page."
    }
  - {
      type: "text",
      label: "Description",
      comment: "Provide a detailed description of the portfolio project.",
      multiline: true
    }
  - {
      type: "images",
      label: "Gallery Images",
      comment: "Upload multiple images to display in a gallery format.",
      multiple: true
    }
  - {
      type: "select",
      label: "Category",
      options: {
        values: ["Graphic Design", "Web Design", "Illustration", "Photography"],
        allow_empty: false
      },
      comment: "Select the category for this portfolio page."
    }
  - {
      type: "boolean",
      label: "Featured",
      comment: "Mark this page as featured on the homepage or portfolio listing."
    }
---
