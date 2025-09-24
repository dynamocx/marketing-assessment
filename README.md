# Marketing Growth Readiness Assessment

A 2-minute digital marketing intake assistant that can be turned into a chatbot for your website.

## Features

- **Fast Assessment**: 6 quick questions, one at a time
- **Multiple Selections**: Users can select multiple marketing channels, challenges, and metrics
- **Growth Readiness Snapshot**: Comprehensive summary with scoring and recommendations
- **Lead Capture**: Collects name, email, phone, and company information
- **GoHighLevel Integration**: Automatically creates contacts in your CRM
- **Export Options**: Download PDF, JSON, or copy summary

## Setup

1. Update the GoHighLevel API credentials in `index.html`
2. Deploy to your website or use GitHub Pages

## GoHighLevel Configuration

Update these values in `index.html`:

```javascript
const GHL_CONFIG = {
    apiToken: 'YOUR_GHL_API_TOKEN_HERE',
    locationId: 'YOUR_LOCATION_ID_HERE',
    pipelineId: 'YOUR_PIPELINE_ID_HERE' // Optional
};
```

## Questions Covered

1. Primary business goal (6 months)
2. Marketing budget range
3. Current marketing channels (multiple selection)
4. Biggest marketing challenges (multiple selection)
5. Success measurement methods (multiple selection)
6. Target customer acquisition cost (CAC)

## Customization

- Modify questions in the `questions` array
- Update styling in the CSS section
- Add/remove custom fields for GoHighLevel integration
- Customize recommendations logic

