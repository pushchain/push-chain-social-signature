# Push Chain Email Signature

A professional HTML email signature template for the Push Chain team. This signature includes social media links, a customizable profile image, and a modern design that works across all major email clients.

## Features

- **Responsive Design**: Works seamlessly across all major email clients (Gmail, Outlook, Apple Mail, etc.)
- **Animated Logo**: Eye-catching animated Push Chain logo
- **Social Media Integration**: Direct links to X (Twitter) and Discord
- **Calendar Booking**: Integrated Calendly link for easy meeting scheduling
- **Customizable**: Easy to personalize with your own details
- **Professional Layout**: Clean, modern design with proper spacing and typography

## Preview

The signature includes:
- Animated Push Chain logo (100x100px, rounded corners)
- Name and title
- Push Chain branding with link
- Social media icons (X, Discord)
- Schedule meeting button (Calendly integration)

## Usage

### Quick Setup

1. Open `signaturev4.html` in a text editor
2. Customize the following fields:
   - **Name**: Replace `Harsh Rajat` with your name (line 65)
   - **Title**: Replace `Co-Founder` with your title (line 69)
   - **Social Links**: Update X and Discord URLs (lines 101, 118)
   - **Calendly Link**: Replace with your Calendly URL (line 135)

3. Copy the HTML signature to your email client

### Installation by Email Client

#### Gmail
1. Open the HTML file in a browser
2. Select all content (Cmd/Ctrl + A)
3. Copy (Cmd/Ctrl + C)
4. Go to Gmail Settings → See all settings → General → Signature
5. Create new signature and paste
6. Save changes

#### Outlook (Mac/Windows)
1. Open the HTML file in a browser
2. Select all content and copy
3. Go to Outlook → Preferences → Signatures
4. Create new signature and paste
5. Save

#### Apple Mail
1. Open the HTML file in a browser
2. Select all content and copy
3. Go to Mail → Preferences → Signatures
4. Create new signature and paste
5. Drag to reorder if needed

## Customization

### Changing Personal Information

Edit the following sections in `signaturev4.html`:

```html
<!-- Name (line 65) -->
<span style="...">Your Name</span>

<!-- Title (line 69) -->
<span style="...">Your Title | </span>

<!-- X/Twitter Link (line 101) -->
<a href="https://x.com/your-handle" ...>

<!-- Discord Link (line 118) -->
<a href="https://discord.com/invite/your-server" ...>

<!-- Calendly Link (line 135) -->
<a href="https://calendly.com/your-username/" ...>
```

### Changing Colors

The signature uses the Push Chain brand color `#cf59e2` (purple). To modify:

```html
<!-- Push Chain link color (line 74) -->
color: #cf59e2;
```

### Assets

All images are hosted on GitHub and referenced via CDN:
- `pc.gif` - Animated Push Chain logo
- `x.png` - X (Twitter) icon
- `discord.png` - Discord icon
- `schedule.png` - Schedule meeting button

To use custom images, replace the `src` URLs with your own hosted images.

## File Structure

```
push-chain-social-signature/
├── signaturev4.html    # Main signature template
├── pc.gif              # Animated logo (standard resolution)
├── pchighres.gif       # Animated logo (high resolution)
├── x.png               # X/Twitter icon
├── discord.png         # Discord icon
├── schedule.png        # Schedule meeting button
├── website.png         # Website icon (optional)
└── README.md           # This file
```

## Technical Details

- **Format**: HTML 4.0 Transitional (maximum email client compatibility)
- **Font**: Verdana, sans-serif fallback
- **Table-based Layout**: Ensures consistent rendering across email clients
- **Inline Styles**: All styles are inline for email client compatibility
- **Image Hosting**: GitHub raw content URLs for reliable delivery

## Browser Compatibility

The signature is tested and works with:
- Gmail (Web, iOS, Android)
- Outlook (Windows, Mac, Web)
- Apple Mail (macOS, iOS)
- Yahoo Mail
- ProtonMail
- Thunderbird

## Contributing

To contribute improvements to the signature template:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test across multiple email clients
5. Submit a pull request

## License

This signature template is maintained by the Push Chain team for internal and community use.

## Support

For questions or issues:
- Visit [push.org](https://push.org)
- Join our [Discord](https://discord.com/invite/pushchain)
- Follow us on [X](https://x.com/pushchain)

---

**Push Chain** - Building the future of decentralized communication
