# JT Showcase Pro

**JT Showcase Pro** is a modern Joomla module for turning articles into polished showcase sections for portfolios, featured content, products, and case studies.

It works with **Joomla Articles**, **Article Images**, **Tags**, and **Custom Fields**, giving you a flexible way to build stylish content blocks without extra complexity.

## Features

- Responsive showcase layouts
- Joomla article-based content source
- Custom field mapping support
- Subtitle, meta, and badge fields
- Primary and secondary CTA buttons
- Tag filter support
- Article intro image support
- Flexible image ratio options
- Portfolio, product, and case study ready
- Joomla 6 compatible

## Requirements

- Joomla 6.x
- PHP 8.1 or higher

## Installation

1. Download the latest **JT Showcase Pro** package.
2. In Joomla Administrator, go to **System → Install → Extensions**.
3. Upload the ZIP package and install it.
4. After installation, go to **Extensions → Modules**.
5. Open **JT Showcase Pro** and configure the module.

## How JT Showcase Pro Works

JT Showcase Pro displays **Joomla articles** from a selected category.

Each showcase item can use:
- the article title
- intro text
- article image
- tags
- mapped custom field values

This makes it easy to manage showcase content using Joomla’s native article system.

## Quick Start

### 1. Create an article category

Create a category for your showcase content, for example:

- Portfolio
- Case Studies
- Products
- Featured Content

Go to:

**Content → Categories → New**

Example category name:

**Portfolio**

### 2. Create your custom fields

Go to:

**Content → Fields**

Create article fields for the extra showcase data you want to display.

Recommended fields:

- Subtitle
- Meta
- Badge
- Primary CTA Text
- Primary CTA URL
- Secondary CTA Text
- Secondary CTA URL

Recommended field names:

- `subtitle`
- `meta`
- `badge`
- `cta-text`
- `cta-url`
- `secondary-cta-text`
- `secondary-cta-url`

> Important:  
> Use the **exact Joomla field name** in the module mapping settings.  
> Joomla may automatically generate field names with hyphens (`-`) instead of underscores (`_`).  
> Always copy the field name exactly as created in **Articles → Fields**.

### 3. Create your articles

Go to:

**Content → Articles → New**

For each showcase item:

- assign the article to your showcase category
- add an article title
- add intro text
- upload an intro image
- assign optional tags
- fill in your custom field values

Example use cases:

- portfolio project
- product highlight
- featured service
- case study
- campaign item

### 4. Configure the module

Go to:

**Extensions → Modules → JT Showcase Pro**

In the **Module** tab, configure the main settings:

- **Article category**  
  Select the category that contains your showcase articles.

- **Limit by tags**  
  Optionally limit output to specific tags.

- **Article count**  
  Choose how many articles to display.

- **Layout variant**  
  Select the preferred layout style.

- **Image source**  
  Choose the article image source.

- **Image ratio**  
  Set the preferred image ratio.

- **Excerpt length**  
  Control the intro text length.

- **Featured filter**  
  Filter featured or all articles.

- **Order by**  
  Choose article ordering logic.

- **Order direction**  
  Ascending or descending.

- **Show tag filters**  
  Enable or disable frontend tag filters.

- **Link article titles**  
  Enable title links.

- **Title and image link target**  
  Define how titles and images should behave when clicked.

### 5. Map your custom fields

Open the **Custom field mapping** tab.

Enter your field names exactly as created in Joomla.

Example mapping:

- **Subtitle field name** → `subtitle`
- **Meta field name** → `meta`
- **Badge field name** → `badge`
- **Primary button text field name** → `cta-text`
- **Primary button URL field name** → `cta-url`
- **Secondary button text field name** → `secondary-cta-text`
- **Secondary button URL field name** → `secondary-cta-url`

You can also set:

- **Fallback primary button label**
- **Open CTA links in new window**

## Recommended Setup Example

### Category
`Portfolio`

### Custom fields
- `subtitle`
- `meta`
- `badge`
- `cta-text`
- `cta-url`
- `secondary-cta-text`
- `secondary-cta-url`

### Example article content

**Title:**  
Modern Storefront Experience

**Intro Text:**  
A complete ecommerce redesign focused on speed, clarity, and a seamless mobile shopping journey.

**Fields:**  
- `subtitle` → Premium ecommerce redesign for a growing lifestyle brand
- `meta` → Ecommerce · 2026
- `badge` → Featured
- `cta-text` → View Project
- `cta-url` → `#`
- `secondary-cta-text` → Live Preview
- `secondary-cta-url` → `#`

## Tag Filters

JT Showcase Pro can display tag-based filters on the frontend.

To use this feature:

1. Assign Joomla tags to your articles
2. Enable **Show tag filters** in the module settings

This is useful for filtering:
- Web Design
- Ecommerce
- Branding
- UI/UX
- Development
- Corporate

## Link Behavior

You can control how titles and images behave.

Typical setup options include:

- linking to the Joomla article page
- linking to the primary CTA URL when available

For showcase-style pages, using the primary CTA URL often gives a cleaner user experience.

## Best Use Cases

JT Showcase Pro is ideal for:

- portfolios
- case studies
- featured projects
- product highlights
- homepage showcase sections
- campaign blocks
- service presentations

## Troubleshooting

### Custom field values are not displayed
Make sure the field names in the module match the Joomla field names exactly.

Example:

If Joomla created:
- `cta-text`

do not enter:
- `cta_text`

The names must match exactly.

### CTA buttons are not showing
Check that:
- the CTA text field is filled
- the CTA URL field is filled
- the field names are mapped correctly

### Images are not showing
Make sure:
- the article has an intro image or the selected image source is available
- the correct image source is selected in the module settings

### Tag filters are not appearing
Check that:
- articles have tags assigned
- **Show tag filters** is enabled in the module settings

## FAQ

### Does this module use Joomla articles?
Yes. JT Showcase Pro uses Joomla articles as the content source.

### Do I need custom fields?
No. Custom fields are optional, but recommended for subtitle, meta, badge, and CTA button data.

### Can I use it for portfolios?
Yes. It is well suited for portfolios, case studies, featured projects, and product-style showcases.

### Can I use tag filters?
Yes. The module supports tag-based filtering when enabled.

### Does it support Joomla 6?
Yes. JT Showcase Pro is built for Joomla 6.

## Support

For updates, package releases, and documentation, please use this repository and the official JoomTheme website.

## License

GNU General Public License version 2 or later.
