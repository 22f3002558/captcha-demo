# Captcha Solver Webpage

This is a simple static web app that solves captchas by reading the image URL from the query parameter `?url` and displaying the solved text.

## Usage
1. Host the `index.html` file on a web server.
2. Access the webpage with a URL like `http://yourserver/index.html?url=http://example.com/captcha.jpg`.
3. The solved captcha text will be displayed in the `#solution` element.

## Requirements
- A backend service to process the captcha image and return the solved text.

## License
This project is licensed under the MIT License.