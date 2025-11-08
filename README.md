# Categories Page - WordPress Plugin

[![WordPress Plugin Version](https://img.shields.io/badge/version-1.3-blue.svg)](https://wordpress.org/plugins/categories-page/)
[![WordPress Tested](https://img.shields.io/badge/WordPress-6.8-green.svg)](https://wordpress.org/)
[![License](https://img.shields.io/badge/license-GPLv2%20or%20later-orange.svg)](https://www.gnu.org/licenses/gpl-2.0.html)

Display a sortable table listing of all categories registered on your WordPress website using a simple shortcode.

## 🌟 Features

- ✅ **Easy Implementation** - Simple shortcode `[get_categories]`
- ✅ **Sortable Table** - JavaScript-powered sortable columns
- ✅ **Pagination Support** - Handle large numbers of categories
- ✅ **Widget Support** - Tag cloud widget integration
- ✅ **Responsive Design** - Works on all devices
- ✅ **SEO Friendly** - Proper HTML markup
- ✅ **Multilingual Ready** - Translation support
- ✅ **Secure** - All output properly escaped
- ✅ **PHP 8.0+ Compatible** - No deprecated functions

## 📦 Installation

### From WordPress.org

1. Go to **Plugins → Add New**
2. Search for "Categories Page"
3. Click **Install Now** and then **Activate**

### Manual Installation

1. Download the plugin zip file
2. Extract the contents
3. Upload the `categories-page` folder to `/wp-content/plugins/`
4. Activate the plugin through the **Plugins** menu in WordPress

### From GitHub

```bash
cd wp-content/plugins/
git clone https://github.com/MervinPraison/categories-page.git
```

## 🚀 Usage

### Shortcode

Display categories table in any post or page:

```
[get_categories]
```

With pagination (20 categories per page):

```
[get_categories pagesize="20"]
```

### PHP Function

Use in your theme template:

```php
<?php if ( function_exists('get_featured_img') ) get_featured_img(); ?>
```

### Widget Configuration

The plugin integrates with the Tag Cloud widget to add custom links and captions.

## 🔧 Configuration

No complex configuration needed! Simply:

1. Add the shortcode to any page/post
2. Categories will be displayed in a sortable table
3. Click column headers to sort

## 📋 Requirements

- **WordPress:** 3.0 or higher
- **PHP:** 5.6 or higher (7.4+ recommended)
- **MySQL:** 5.0 or higher

## 🔒 Security Features

### Version 1.3 Security Fixes

- ✅ Fixed deprecated `create_function()` usage (PHP 8.0+ compatibility)
- ✅ Added proper output escaping to prevent XSS
- ✅ Fixed SQL injection vulnerability with `wpdb->prepare()`
- ✅ Sanitized `$_SERVER['REQUEST_URI']` input
- ✅ Added version numbers to enqueued scripts/styles
- ✅ Added translators comments for i18n strings

## 📝 Changelog

### Version 1.3 (2025-01-08)

**Security Fixes:**
- Fixed deprecated `create_function()` usage (PHP 8.0+ compatibility)
- Added proper escaping to all output
- Fixed SQL injection vulnerability with `wpdb->prepare()`
- Sanitized `$_SERVER['REQUEST_URI']` input

**Improvements:**
- Added version numbers to enqueued scripts and styles
- Added translators comments for i18n strings
- Updated license to GPLv2 or later
- WordPress 6.8 compatibility tested
- Proper text domain usage throughout

### Version 1.2
- Global `$post` fix

### Version 1.0
- Initial release

## 🎨 Customization

### CSS Classes

The plugin uses the following CSS classes for styling:

- `.tags_table` - Main table
- `.tags_table_column_tag` - Category name column
- `.tags_table_column_count` - Post count column
- `.categories-page-pagination` - Pagination container

### Example Custom CSS

```css
.tags_table {
    border-collapse: collapse;
    width: 100%;
}

.tags_table th {
    background-color: #f5f5f5;
    cursor: pointer;
}

.tags_table td {
    padding: 10px;
    border-bottom: 1px solid #ddd;
}
```

## 🌐 Translations

The plugin is translation-ready. Translation files should be placed in:

```
/wp-content/plugins/categories-page/lang/
```

**Available Translations:**
- Czech (cs_CZ) - Included

To contribute a translation, use the `.pot` file included in the `lang` folder.

## 🐛 Bug Reports & Feature Requests

Found a bug or have a feature request?

- **GitHub Issues:** [Report here](https://github.com/MervinPraison/categories-page/issues)
- **WordPress.org Support:** [Support Forum](https://wordpress.org/support/plugin/categories-page/)

## 👨‍💻 Development

### Repository Structure

```
categories-page/
├── categories-page.php    # Main plugin file
├── readme.txt            # WordPress.org readme
├── README.md             # This file
├── css/                  # Stylesheets
│   ├── admin.css
│   ├── admin.min.css
│   ├── tags-page.css
│   └── tags-page.min.css
├── js/                   # JavaScript files
│   ├── admin.js
│   ├── admin.min.js
│   ├── webtoolkit.sortabletable.js
│   └── webtoolkit.sortabletable.min.js
└── lang/                 # Translation files
    ├── categories-page.pot
    ├── categories-page-cs_CZ.po
    └── categories-page-cs_CZ.mo
```

### Contributing

Contributions are welcome! Please:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This plugin is licensed under the GPLv2 or later.

```
This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.
```

## 👤 Author

**Mervin Praison**
- Website: [mer.vin](https://mer.vin)
- GitHub: [@MervinPraison](https://github.com/MervinPraison)
- WordPress.org: [mervinpraison](https://profiles.wordpress.org/mervinpraison/)

## 🔗 Links

- **WordPress.org:** https://wordpress.org/plugins/categories-page/
- **GitHub Repository:** https://github.com/MervinPraison/categories-page
- **Support Forum:** https://wordpress.org/support/plugin/categories-page/
- **Author Website:** https://mer.vin

## ⭐ Support

If you find this plugin useful, please consider:

- ⭐ [Leaving a review](https://wordpress.org/support/plugin/categories-page/reviews/)
- 🐛 [Reporting bugs](https://github.com/MervinPraison/categories-page/issues)
- 💡 [Suggesting features](https://github.com/MervinPraison/categories-page/issues)
- 🌐 [Contributing translations](https://translate.wordpress.org/projects/wp-plugins/categories-page/)

---

## 📅 Plugin History

**Original Release Date:** November 19, 2015  
**First Published:** WordPress.org Plugin Directory  
**Total Years Active:** 9+ years

---

**Made with ❤️ for the WordPress community**
