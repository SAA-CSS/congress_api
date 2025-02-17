### Plugin for WordPress integration with api.congress.gov

#### Description
This plugin displays votes, sponsored and cosponsored legislation for a selected senator and legislation and nominations data for a selected committee. The plugin retrieves data from the Congress API and senate.gov xml respositories and includes detailed links to Congress.gov for each bill.

#### Installation
1. Upload the zip file via the 'Plugins' menu in WordPress.
2. Activate the plugin.
3. Go to 'Settings' -> 'Legislation' to select a senator or specify a committee.

#### Usage
1. Add the shortcodes to any post or page to display data for a senator or committee, or to invoke the congress.gov search box.

#### Shortcodes
- `[legislation]`: Displays the legislation table for the selected senator.
- `[votes]`: Displays the senator's voting record.
- `[congress_search_box]`: Displays a form for querying congress.gov.
- `[committee_nominations]`: Displays the committee's nominations.
- `[committee_legislation]`: Displays the committee's legislation.

#### Changelog
**Version 1.0.5**
- Replaced API calls with api.congress.gov endpoints and senate.gov xml repositories.
**Version 1.0.7**
- Added committee nominations and legislation.
**Version 1.0.7**
- Added congress.gov search box shortcode: [congress_search_box]. Defaults to cosponsored legislation for new member show have no sponsored legislation. Repaired a bug related to joint resolutions.

#### Frequently Asked Questions
**Q:** How do I configure the senator or committee?
**A:** Go to 'Settings' -> 'Legislation' and select the senator from the dropdown or specify a committee code.

**Q:** How do I use the shortcodes?
**A:** After configuring the senator, add `[legislation]` to any post or page where you want the legislation table to appear. Add `[votes]` to display the senator's voting record. Use [committee_nominations] and [committee_legislation] to display a committee's data.
