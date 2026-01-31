📧 WORKING CONTACT FORM - Using Formspree (NO PHP NEEDED!)

✅ STEP 1: Sign up at Formspree (FREE)
   - Go to: https://formspree.io
   - Sign up with your Gmail: chahdjourhari7@gmail.com
   - Create a new form
   - Copy your form ID (e.g., abc123def)

✅ STEP 2: Replace your contact form HTML with this:

```html
<!-- CONTACT FORM WITH FORMSPREE -->
<form class="contact-form" id="contactForm" 
      action="https://formspree.io/f/YOUR_FORM_ID_HERE" 
      method="POST" 
      data-aos="fade-left">
    <div class="form-grid">
        <div class="form-group">
            <label for="name" class="form-label">Name</label>
            <input type="text" id="name" name="name" class="form-input" placeholder="Your Name" required>
            <span class="input-border"></span>
        </div>
        
        <div class="form-group">
            <label for="email" class="form-label">E-Mail</label>
            <input type="email" id="email" name="_replyto" class="form-input" placeholder="Your E-Mail" required>
            <span class="input-border"></span>
        </div>
        
        <div class="form-group">
            <label for="phone" class="form-label">Phone</label>
            <input type="tel" id="phone" name="phone" class="form-input" placeholder="Your Phone">
            <span class="input-border"></span>
        </div>
        
        <div class="form-group">
            <label for="company" class="form-label">Company</label>
            <input type="text" id="company" name="company" class="form-input" placeholder="Your Company">
            <span class="input-border"></span>
        </div>
        
        <div class="form-group full-width">
            <label for="message" class="form-label">Message</label>
            <textarea id="message" name="message" class="form-input form-textarea" placeholder="Your Message" rows="5" required></textarea>
            <span class="input-border"></span>
        </div>
        
        <!-- Formspree required fields -->
        <input type="hidden" name="_subject" value="New contact from your portfolio!">
        <input type="text" name="_gotcha" style="display:none" />
    </div>
    
    <button type="submit" class="submit-btn">
        <span class="btn-content">
            <span>Send Message</span>
            <i class="fas fa-paper-plane"></i>
        </span>
        <span class="btn-shine"></span>
    </button>
</form>
```

✅ STEP 3: Replace `YOUR_FORM_ID_HERE` with your actual Formspree form ID

✅ STEP 4: Test! Fill out the form and submit. You'll get an email immediately.

===============================================================

📨 ALTERNATIVE: Replace form action only (Keep your current HTML):

Just find your `<form class="contact-form">` tag and add/change these attributes:

Before:
```html
<form class="contact-form" id="contactForm" data-aos="fade-left">
```

After:
```html
<form class="contact-form" id="contactForm" 
      action="https://formspree.io/f/YOUR_FORM_ID_HERE" 
      method="POST" data-aos="fade-left">
```

And change your email input from:
```html
<input type="email" id="email" name="email">
```

To:
```html
<input type="email" id="email" name="_replyto">
```

===============================================================

🚨 IMPORTANT NOTE ABOUT YOUR PHP:

Your `send_email.php` requires XAMPP to be configured for email, which is complex on Windows.

Formspree is much easier:
- ✅ Free (50 per month)
- ✅ No coding needed  
- ✅ Works immediately
- ✅ Professional emails
- ✅ Spam protection
- ✅ Auto-redirect after submit
- ✅ No database needed
- ✅ No XAMPP configuration

===============================================================

🎯 RECOMMENDATION: Use Formspree. It's the easiest and most reliable solution for a portfolio contact form.

Sign up now: https://formspree.io 🚀
