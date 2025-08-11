Switchback Starter Pack Landing Page
Landing page for COGS Switchback Starter Pack - 24-hour business transformation packages.
Quick Setup

Update CONFIG (line ~650 in index.html):

javascriptconst CONFIG = {
  promoName: "Shoulder Season Sale!",
  discountCopy: "Save $500 on all packages",
  deadlineISO: "2025-09-30T23:59:59-04:00",
  formWebhook: "YOUR_WEBHOOK_URL"  // Add your Zapier webhook
};

Deploy to Vercel:

Go to vercel.com
Drag and drop index.html
Done!



Zapier Setup
The form sends this data to your webhook:

Name, Business, Email, Phone
Industry, Website, Message
Selected Package (starter/professional/premium)

Add these Zapier filters to prevent spam:

Only continue if email contains "@"
Only continue if honeypot field is empty

Updating Content

Packages/Pricing: Lines 400-500
Testimonials: Lines 800-850
FAQs: Lines 900-1100
"Spots left" numbers: Search for "Only X spots"

Testing

 Form opens when clicking package buttons
 Test form submission → Check Zapier caught it
 Mobile: Logo carousel works
 All FAQs open/close

Support
Issues: hello@chathamoaks.co
Live URL: [your-site].vercel.app
