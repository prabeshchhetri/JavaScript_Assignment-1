# Copilot Code Review

## Security

### Finding
The website is mostly static and does not collect or store user data.

### Accept / Reject Reasoning
Accepted. Since there is no database, login, or form processing, the risk of injection or authentication issues is low.

## Accessibility

### Finding
The website uses readable headings, navigation links, and Bootstrap layout.

### Accept / Reject Reasoning
Accepted with minor recommendation. Colour contrast and link text should be checked manually.

## Performance

### Finding
The website uses one CSS file and Bootstrap CDN.

### Accept / Reject Reasoning
Accepted. The site is lightweight and should load quickly.

## Recommendations

- Add alt text if images are added.
- Keep project images compressed.
- Use clear navigation text.