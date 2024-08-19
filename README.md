# Tableau Embedding Responsively by Switch Device Attribute

#### This project explores the responsive embedding of Tableau dashboards, specifically focusing on "fixed-size" dashboards. The goal is to ensure that the dashboard adjusts according to the device attribute.

**Note**: Special thanks to [@alexeski](https://github.com/alexeski/tableau-embed-viz-responsive-apiv3/blob/main/index.html). Without his work, I would never have known about `viz.workbook.activeSheet._workbookImpl._activeSheetImpl._sheetInfoImpl._sheetSize.maxSize.height`.

## What It Looks Like - <a href="https://bamboooofish.github.io/Tableau-Embedding-Responsively-by-Switch-Device-Attribute/" target="_blank">Explore here</a>
![tableau](https://github.com/user-attachments/assets/a70bd8d9-e13c-4b56-a02e-e9fe9fff6897)

**Tested on Google Blogger:**

- **Desktop**:
  
  ![desktop](https://github.com/user-attachments/assets/9cf98f96-0b50-443d-9273-1e398ee3afbf)


- **Phone**:
  
  ![phone](https://github.com/user-attachments/assets/7ded2657-7284-493e-8971-37749c097982)


## Use it on Your Dashboard

Replace the `src` URL and `mediaWidth` width in the HTML to apply the same effect on your dashboard.
```html
const src = 'https://public.tableau.com/views/_17212102503700/sheet0?:language=zh-TW&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link';
const mediaWidth = 768;
```
