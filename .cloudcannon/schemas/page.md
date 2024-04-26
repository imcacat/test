---
title: "Page"
fields:
  - {
      type: "string",
      label: "Title",
      comment: "Enter the page title."
    }
  - {
      type: "text",
      label: "Content",
      comment: "Main content of the page.",
      multiline: true
    }
  - {
      type: "image",
      label: "Feature Image",
      comment: "Upload an image that represents this page."
    }
  - {
      type: "select",
      label: "Layout",
      options: {
        values: ["default", "custom"],
        default: "default"
      },
      comment: "Select the layout for this page."
    }
  - {
      type: "boolean",
      label: "Published",
      comment: "Toggle whether this page is live."
    }
---