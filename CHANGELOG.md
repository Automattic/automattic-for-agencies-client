# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 0.1.0-alpha - unreleased

This is an alpha version! The changes listed here are not final.

### Added
- Added connected state content and site disconnection flow.
- Added connection card
- Added details about sharing information with Automattic to the connection card.
- Added reconnection flow to the A4A client plugin.
- Add Woocommerce event remove_order_items to Jetpack Sync
- General: add first version of the plugin's readme and assets.
- General: add modal displayed when deactivating the plugin.
- Initial commit for the plugin’s infrastructure.
- Packages: add version tracking for identity-crisis package.

### Changed
- General: update WordPress version requirements to WordPress 6.4.
- General: use wp_admin_notice function introduced in WP 6.4 to display notices.
- Updated details about sharing data with WordPress.com
- Updated package dependencies.

### Removed
- Removed the Jetpack-branded header and footer from the plugin.

### Fixed
- Fix post-connection redirect URL.
