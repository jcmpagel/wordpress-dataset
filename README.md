# The WordPress Plugin Dataset

## Overview
This repository presents a rich dataset representing a vast array of WordPress plugins as extracted from the official WordPress Plugin Repository. It is designed to offer an extensive perspective on the dynamics of plugin development, usage, and user feedback. Ideal for developers, academic researchers, or anyone with a keen interest in the evolution and trends within the WordPress plugin community.

### Highlights:
- **Extensive Plugin Records:** Features data on over 100,000 plugins.
- **Tag and Category Insights:** A detailed examination of plugin tags and categories, revealing trends in functionality, popularity, and user demand.

## Dataset Description
Sourced directly from the WordPress Plugin Repository, this dataset provides a comprehensive look into various facets of WordPress plugins, including:

- **slug**: A unique identifier for each plugin, usually a simplified version of the plugin name.
- **tag**: Tags associated with the plugin, indicating its features or categories.
- **version**: The current version of the plugin.
- **author_profile**: The URL to the profile of the plugin author on WordPress.org.
- **requires**: The minimum WordPress version required for the plugin to function properly.
- **tested**: The latest WordPress version that the plugin has been tested with.
- **requires_php**: The minimum PHP version required by the plugin.
- **rating**: The overall rating of the plugin.
- **num_ratings**: The number of ratings the plugin has received.
- **support_threads**: The number of support threads created for the plugin.
- **support_threads_resolved**: The number of support threads resolved.
- **active_installs**: The number of active installations of the plugin.
- **downloaded**: The number of times the plugin has been downloaded.
- **last_updated**: The date when the plugin was last updated.
- **added**: The date when the plugin was added to the repository.
- **homepage**: The URL to the homepage of the plugin.
- **donate_link**: The URL to a donation page for the plugin.
- **preview_link**: The URL to a preview of the plugin (this column has no non-null values in the sample provided).
- **rating_1** to **rating_5**: The number of ratings for each star level (1 to 5).

### File Structure
- `wordpress_sample.csv`: The core file of the dataset, containing detailed information on a wide range of plugins.
- `wordpress_sample.csv`: Represent all plugins which are banned from the offical repository for security or copyright issues, therefore there is not more data available.

## Usage
This dataset is openly available and is governed by [specify license, e.g., MIT, Creative Commons, etc.]. It is an essential resource for a diverse range of purposes, including:
- **Developers:** Gaining insights into market demands or drawing inspiration for plugin development.
- **Researchers:** Conducting comprehensive analyses on trends, user behavior, or the developmental trajectory of the WordPress plugin ecosystem.
- **Content Creators and Bloggers:** Crafting well-informed content, reports, or analyses centered on WordPress plugins.


## Acknowledgements
This dataset represents a comprehensive effort to scrape and analyze data from the official WordPress Plugin Repository.
