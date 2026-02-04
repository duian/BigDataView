# Project Structure

```
BigDataView/
├── README.md              # Project documentation (Chinese)
├── view.html              # Main preview page with all templates
├── .gitignore
│
├── gif/                   # Preview GIFs/images for each template
│   └── 001.gif ... 118.gif
│
├── preview/               # Promotional images
│   └── wechat-code.png
│
└── web/                   # All dashboard templates
    ├── index.html         # Template listing page
    └── {NNN} {Template Name}/
        ├── index.html     # Main entry point
        ├── css/           # Stylesheets
        │   ├── index.css
        │   └── reset.css
        ├── js/            # JavaScript files
        │   ├── app.js
        │   └── [utility scripts]
        ├── images/        # Template-specific images
        └── fonts/         # Custom fonts (if any)
```

## Template Naming Convention
Templates are numbered sequentially: `{NNN} {Chinese Name}`
- Example: `001 政务服务大数据可视化监管平台`
- Numbers range from 001 to 118

## Template Categories
- Government/Public Services (政务)
- Healthcare/Medical (医疗)
- Logistics/Transportation (物流/交通)
- Finance/Banking (金融)
- IoT/Smart City (物联网/智慧城市)
- Agriculture (农业)
- E-commerce (电商)
- General/Universal templates (通用模板)

## Adding New Templates
1. Create folder: `web/{NNN} {Template Name}/`
2. Include: `index.html`, `css/`, `js/`, `images/`
3. Add preview GIF to `gif/` folder
4. Update `web/index.html` with new link
