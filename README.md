# Mini System

Mini System is a customized application built for ERPNext, specifically designed to streamline and minimize ERPNext operations and doctypes for small businesses. It aims to reduce complexity while maintaining the essential functionality required for day-to-day business operations.

## Features

- **Optimized Doctypes:** Simplified versions of ERPNext doctypes tailored for small-scale businesses.
- **Streamlined Operations:** Removes unnecessary overhead for quicker and easier workflows.
- **User-Friendly Interface:** Focuses on ease of use, catering to small business owners with limited ERP experience.
- **Custom Integrations:** Allows for additional custom fields and property settings as per small business requirements.

## Installation

1. Navigate to your `frappe-bench` directory.
2. Get the Mini System app from your repository:
   ```bash
   bench get-app mini_system https://github.com/ahmedemamhatem/mini_system.git
   ```
3. Install the app on your site:
   ```bash
   bench --site [site-name] install-app mini_system
   ```

## Usage

- Once installed, Mini System will appear as an app in the ERPNext dashboard.
- Access the app to start using the customized doctypes and simplified workflows.
- Refer to the app's documentation or reach out for support if needed.

## Configuration

### Default Setup
- The application automatically applies configurations to optimize small business operations.
- You can customize further using the Property Setter feature included in the app.

### Workspace Visibility
- During installation or migration, all workspaces except "Home" and "Users" are set to hidden for a cleaner interface.

## Support

For support or inquiries, contact the app developer:

- **Developer Name:** Ahmed Emam
- **Email:** ahmedemamhatem@gmail.com

## License

This app is licensed under the [MIT License](https://opensource.org/licenses/MIT).
