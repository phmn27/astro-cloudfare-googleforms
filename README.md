
# Custom Astro Form Template with Cloudfare Turnstile and Google Forms

This project provides a customizable form template built using [Astro](https://astro.build/). The form is designed to collect user input and submit it to a specified endpoint, such as Google Forms. It also integrates with Cloudflare Turnstile to add a security challenge to prevent spam.

## Features

- **Responsive Design**: The form is styled with Tailwind CSS classes to be fully responsive and visually appealing.
- **Customizable Fields**: Easily replace placeholders with your own data and adapt the form to different use cases.
- **Google Forms Integration**: Send form submissions directly to Google Forms using custom action URLs.
- **Cloudflare Turnstile Security**: Protect your form from spam submissions using Cloudflare's Turnstile CAPTCHA.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) installed on your machine
- [Astro](https://astro.build/) installed globally or in your project

### Installation

1. **Clone this repository**:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the development server**:
   ```bash
   npm run dev
   ```

### Customization

1. **Update the Form Action URL**: 
   Replace `YOUR_GOOGLE_FORM_ACTION_URL` in the `<form>` tag with your Google Form's action URL. This URL can be found by inspecting your Google Form.

2. **Update Field Names**: 
   Replace `entry.YOUR_ENTRY_ID_FOR_*` with your specific Google Form entry IDs. Each form input should correspond to an entry ID generated by Google Forms.

3. **Configure Cloudflare Turnstile**: 
   Replace `YOUR_TURNSTILE_SITE_KEY` with your own Cloudflare Turnstile site key. For more information on setting up Turnstile, refer to the [Cloudflare documentation](https://developers.cloudflare.com/turnstile/get-started/).

4. **Modify Field Labels and Options**: 
   Adjust the labels, placeholders, and select options to suit your needs.

### Deployment

To deploy your Astro project, follow the official Astro deployment guide [here](https://docs.astro.build/en/guides/deploy/).

## Acknowledgments

- **Astro Turnstile Template**: This project was inspired by and uses elements from the [Astro Turnstile Template](https://github.com/SapphicMoe/astro-turnstile-template). Special thanks to SapphicMoe for providing an excellent starting point for integrating Cloudflare Turnstile with Astro.

- **Google Forms Integration**: Guidance on using Google Forms as a backend for form submissions was provided by this [article](https://pqvst.com/2021/12/28/custom-google-forms/). Thank you to the author for the detailed instructions.

## License

This project is open-source and available under the [MIT License](LICENSE).

---

Thank you for using this template! If you have any questions or suggestions, feel free to open an issue or submit a pull request.


### Notes:
- Make sure to replace placeholder text such as `your-username/your-repo-name` and `LICENSE` with actual links or your project's details.
- Ensure you include a `LICENSE` file if your project is open source.
- Add any additional customization instructions specific to your project as needed.