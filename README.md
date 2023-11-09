# Joomla to WordPress Migrator

This WordPress plugin provides a seamless migration tool for transferring your content from a Joomla-powered website to WordPress. The plugin is designed to handle the migration of pages, including images, videos, and other embedded media, with minimal hassle.

## Features

- **Automatic Content Transfer**: Migrate articles, categories, pages, and media from Joomla to WordPress.
- **Media Handling**: Transfer images and other media items embedded within your content.
- **SEO Preservation**: Maintain your SEO efforts with redirects and careful handling of meta-information.
- **User Import**: Bring over your Joomla user accounts to WordPress.
- **Category Conversion**: Converts Joomla categories into WordPress categories or tags.
- **Batch Processing**: Process large quantities of content in batches for a more manageable migration.

## Requirements

- WordPress 5.0 or higher
- PHP 7.2 or higher
- Joomla 3.x installation database access

## Installation

1. Upload the `joomla-to-wp-migrator` folder to the `/wp-content/plugins/` directory.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Go to `Tools` > `Joomla Migrator` in your WordPress admin to configure the plugin.

## Usage

### Pre-Migration Steps

- Ensure that your Joomla and WordPress installations are backed up.
- Verify that you have access to your Joomla database information.

### Migration Process

1. Enter your Joomla database information in the plugin settings.
2. Choose the content you wish to migrate (e.g., posts, pages, media).
3. Map Joomla user accounts to WordPress user roles.
4. Start the migration process. The plugin will provide a real-time log of the migration.
5. Once the migration is complete, verify the content on your WordPress site.
6. Utilize the provided redirect tools to update any URLs if necessary.

## Post-Migration

After migration, you may need to:

- Check internal links to ensure they point to the correct WordPress URLs.
- Review your website's design and make adjustments as needed.
- Set up your menu structure in WordPress.

## Troubleshooting

If you encounter issues during the migration, please check the following:

- Confirm that your Joomla and WordPress sites are both operational and accessible.
- Verify that the Joomla database credentials you provided are correct.
- Check the PHP error logs for any relevant errors.

For further assistance, create an issue in the plugin's support forum on the WordPress Plugin Directory page.

## Disclaimer

This plugin is not affiliated with or endorsed by the Joomla! Project or Open Source Matters. The Joomla! name and logo are used under a limited license granted by Open Source Matters, the trademark holder in the United States and other countries.
