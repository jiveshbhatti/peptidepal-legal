# Legal Documents for PeptidePal

This folder contains the Privacy Policy and Terms of Service for PeptidePal.

## Files
- `privacy-policy.html` - Privacy Policy
- `terms-of-service.html` - Terms of Service

## Deployment Options

### Option 1: GitHub Pages (Free & Quick)
1. Create a new repository called `peptidepal-legal` on GitHub
2. Upload these HTML files
3. Enable GitHub Pages in repository settings
4. Your URLs will be:
   - `https://[your-username].github.io/peptidepal-legal/privacy-policy.html`
   - `https://[your-username].github.io/peptidepal-legal/terms-of-service.html`

### Option 2: Netlify (Free with Custom Domain)
1. Create a Netlify account
2. Drag and drop this `legal` folder
3. Connect your peptidepal.app domain
4. URLs will be:
   - `https://peptidepal.app/privacy`
   - `https://peptidepal.app/terms`

### Option 3: Your Own Hosting
1. Upload files to your web server
2. Set up redirects:
   - `/privacy` → `/privacy-policy.html`
   - `/terms` → `/terms-of-service.html`

## Important Notes

1. **Review Content**: Please review both documents carefully and adjust:
   - Contact email (currently set to support@peptidepal.app)
   - Any specific details about your data practices
   - Jurisdiction if not US/California

2. **Update App References**: Once hosted, update these references in the app:
   - `src/screens/PaywallScreen.tsx` (lines 231, 243)
   - `src/screens/SettingsScreen.tsx` (lines 439, 449)

3. **App Store Connect**: Add these URLs to:
   - App Information → Privacy Policy URL
   - The "What's New" section should mention privacy policy

4. **Subscription Terms**: Apple requires clear subscription terms, which are included in the Terms of Service.

## Medical Disclaimer
The Terms of Service includes a prominent medical disclaimer, which is important given the nature of the app.

## Compliance
These documents cover:
- CCPA (California Consumer Privacy Act)
- Apple's App Store requirements
- Firebase data usage disclosure
- RevenueCat subscription handling
- Photo library access
- Notification permissions