### Plugin for WordPress integration with api.congress.gov

#### Description
This plugin displays votes, sponsored and cosponsored legislation for a selected senator in a paginated table format. The plugin retrieves data from the Congress API and senate.gov xml respositories and includes detailed links to Congress.gov for each bill.

#### Installation
1. Upload the zip file via the 'Plugins' menu in WordPress.
2. Activate the plugin.
3. Go to 'Settings' -> 'Legislation' to select a Senator.

#### Usage
1. Add the `[legislation]` shortcode to any post or page to display sponsored or co-sponsored legislation.
2. Add the `[votes]` shortcode to display the senator's voting record.
3. Use the dropdown to switch between sponsored and cosponsored legislation.
4. Pagination controls are available to navigate through the records.

#### Shortcodes
- `[legislation]`: Displays the legislation table for the selected senator.
- `[votes]`: Displays the senator's voting record.

#### Changelog
**Version 1.0.5**
- Replaced API calls with api.congress.gov endpoints and senate.gov xml repositories.


#### Frequently Asked Questions
**Q:** How do I configure the senator?
**A:** Go to 'Settings' -> 'Legislation' and select the senator from the dropdown.

**Q:** How do I use the shortcodes?
**A:** After configuring the senator, add `[legislation]` to any post or page where you want the legislation table to appear. Add `[votes]` to display the senator's voting record.
