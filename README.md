This project is a static website built using Umbraco CMS (v16.3.1) with Razor Views and the Block List Editor for content management.
The purpose of the project was to recreate a website based on a provided design file.


🧩 Functionality & Structure

The website follows the design file in terms of pages, sections, and content structure.

The Block List Editor and Element Types are used to build pages in a modular way.

Posters are handled as child pages under the relevant parent pages.

Forms (e.g. “Request a call back”) are implemented visually according to the design, but are not functional.

Navigation is dynamic and generated automatically from the Umbraco content tree.

Global elements such as logo, contact information, and social links are hardcoded (no Site Settings are used).

No pagination or sliders are implemented.

The search function in the header is visual only and not functional.

🛠️ Technical Overview
Technology	Usage
Umbraco CMS 16.3.1	Backend and content management
ASP.NET Core / Razor (.cshtml)	Dynamic content rendering
HTML5 / CSS3	Structure and styling
Font Awesome	Icons
Visual Studio 2022	Development environment
GitHub	Version control
