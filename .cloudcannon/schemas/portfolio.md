---
title: "Portfolio Item"
fields:
  - {
      type: "string",
      label: "Project Name",
      comment: "Enter the name of the project."
    }
  - {
      type: "text",
      label: "Project Description",
      comment: "Provide a detailed description of the project.",
      multiline: true
    }
  - {
      type: "images",
      label: "Project Images",
      comment: "Upload multiple images to showcase the project.",
      multiple: true
    }
  - {
      type: "url",
      label: "Project URL",
      comment: "Provide the URL to the live project if available."
    }
  - {
      type: "select",
      label: "Project Type",
      options: {
        values: ["Web Development", "Mobile App", "Graphic Design"],
        allow_empty: false
      },
      comment: "Select the type of project."
    }
  - {
      type: "boolean",
      label: "Featured",
      comment: "Mark this project as featured on the portfolio page."
    }
---
