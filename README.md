# HTML Forms and Accessibility - Group Assignment

## 📋 Project Overview
This is a collaborative group assignment where we create an accessible HTML registration form with proper validation and ARIA attributes.

## 👥 Group Roles & Responsibilities

### ✅ Role 1: Form Structure Lead (Completed)
**Responsible for:**
- Creating the `<form>` structure
- Adding labels and inputs for:
  - Full Name
  - Email Address
  - Password
  - Terms & Conditions checkbox
- Ensuring semantic HTML and proper label–input relationships

**Status:** ✅ **COMPLETED**

### ⏳ Role 2: Validation Lead (Pending)
**Responsible for:**
- Applying built-in HTML validation:
  - `required` on all fields
  - `type="email"` for email (already present)
  - `minlength` for password
  - `pattern` for password strength
- Testing browser validation behavior

**Status:** ⏳ **AWAITING TEAMMATE CONTRIBUTION**

### ⏳ Role 3: Accessibility (ARIA) Lead (Pending)
**Responsible for:**
- Adding appropriate ARIA attributes:
  - `aria-label`
  - `aria-describedby`
  - `aria-labelledby`
- Ensuring:
  - Password requirements are announced to screen readers
  - Checkbox has an accessible label
  - `<form>` includes `role="form"`
- Verifying accessibility with an accessibility checker

**Status:** ⏳ **AWAITING TEAMMATE CONTRIBUTION**

### ✅ Role 4: Integration & Review Lead (Completed)
**Responsible for:**
- Reviewing the full form for consistency
- Ensuring all roles' work is properly integrated
- Leading final testing and cleanup

**Status:** ✅ **IN PROGRESS** - Will finalize after all team contributions

---

## 🚀 How to View the Form

1. Navigate to the project directory:
   ```
   d:\HTML Forms and Accessibility
   ```

2. Open `index.html` in your web browser:
   - **Option 1:** Double-click `index.html`
   - **Option 2:** Right-click → Open with → Your preferred browser
   - **Option 3:** Drag and drop `index.html` into an open browser window

---

## 📝 Form Structure (Completed by Form Structure Lead)

### Current Implementation:

✅ **Semantic HTML Structure**
- Proper `<!DOCTYPE html>` declaration
- Language attribute: `lang="en"`
- Responsive viewport meta tag
- Clean, indented code structure

✅ **Form Fields with Proper Labels:**
1. **Full Name Field**
   - `<label for="fullName">` with matching input `id="fullName"`
   - Type: `text`
   - Placeholder provided

2. **Email Address Field**
   - `<label for="email">` with matching input `id="email"`
   - Type: `email` (base type set, validation pending)
   - Placeholder provided

3. **Password Field**
   - `<label for="password">` with matching input `id="password"`
   - Type: `password`
   - Placeholder provided
   - Password hint already included (`id="passwordRequirements"`)

4. **Terms & Conditions Checkbox**
   - `<label for="terms">` with matching input `id="terms"`
   - Type: `checkbox`
   - Clickable label with link to terms

5. **Submit Button**
   - Clear call-to-action: "Register"
   - Full-width, styled appropriately

---

## 🎨 Design Features

### Professional Styling Included:
- **Modern gradient background** (purple gradient)
- **Clean white form container** with shadow effects
- **Responsive design** (works on all screen sizes)
- **Focus states** for better user experience
- **Hover effects** on buttons
- **Consistent spacing** and typography
- **User-friendly interface** with clear visual hierarchy

---

## 🔍 What Teammates Need to Add

### For the Validation Lead:
Look for comments in `index.html` that say:
```html
<!-- VALIDATION LEAD: Add validation attributes here -->
```

**Specific tasks:**
1. Add `required` to all four inputs (fullName, email, password, terms)
2. Add `minlength="8"` to the password field
3. Add `pattern="^(?=.*[A-Z])(?=.*\d).{8,}$"` to the password field
4. Test that validation works in different browsers

### For the Accessibility (ARIA) Lead:
Look for comments in `index.html` that say:
```html
<!-- ACCESSIBILITY LEAD: Add ARIA attributes here -->
```

**Specific tasks:**
1. Add `role="form"` to the `<form>` element
2. Add `aria-describedby="passwordRequirements"` to the password input
3. Ensure the checkbox is properly labeled for screen readers
4. Test with a screen reader (NVDA, JAWS, or VoiceOver)
5. Run an accessibility checker (e.g., WAVE, axe DevTools)

---

## ✅ Testing Checklist (Integration & Review Lead)

Once all teammates complete their roles, test:

- [ ] **Empty form submission** - Should show validation errors
- [ ] **Invalid email** (e.g., `abc@`) - Should show email format error  
- [ ] **Weak password** (e.g., `pass123`) - Should fail pattern validation
- [ ] **Short password** (e.g., `Pass1`) - Should fail minlength validation
- [ ] **Unchecked terms checkbox** - Should prevent submission
- [ ] **Valid submission** - All fields filled correctly
- [ ] **Screen reader announcement** - Password requirements read aloud
- [ ] **Keyboard navigation** - Tab through all fields
- [ ] **Visual consistency** - All styling is uniform
- [ ] **Cross-browser testing** - Chrome, Firefox, Edge

---

## 📂 File Structure

```
HTML Forms and Accessibility/
├── index.html          ← Main form file
└── README.md          ← This documentation file
```

---

## 🎯 Assignment Requirements Met

### Step 1: Create the Basic Form ✅
- [x] Full Name (text input)
- [x] Email Address (email input)
- [x] Password (password input)
- [x] Terms and Conditions (checkbox)
- [x] Submit button

### Step 2: Add Built-in Validation ⏳
- [ ] Require all fields to be filled
- [ ] Enforce valid email format
- [ ] Password minimum length (8 characters)
- [ ] Password pattern (uppercase + number)

### Step 3: Enhance with ARIA ⏳
- [ ] ARIA attributes for context
- [ ] ARIA description for password requirements
- [ ] Accessible checkbox labeling
- [ ] `role="form"` on form element

### Step 4: Test the Form ⏳
- [ ] Empty field submission
- [ ] Invalid email
- [ ] Weak password
- [ ] ARIA descriptions with assistive tech

---

## 💡 Tips for Team Collaboration

1. **Communication:** Use comments in the code to mark your contributions
2. **Version Control:** Consider using Git to track who added what
3. **Testing:** Each person should test their own additions before integration
4. **Documentation:** Update this README as you make changes
5. **Final Review:** Schedule a team meeting to review the complete form together

---

## 🎓 Reflection Questions (To be answered as a group)

### Question 1: What is the difference between required validation and pattern validation?
*[Team to discuss and answer]*

### Question 2: Why is ARIA important even though browsers already show validation messages?
*[Team to discuss and answer]*

### Question 3: How does aria-describedby improve accessibility for users of screen readers?
*[Team to discuss and answer]*

---

## 📞 Need Help?

If you encounter issues:
1. Check the HTML comments for guidance
2. Review the assignment rubric
3. Test in multiple browsers
4. Use browser DevTools to inspect elements
5. Validate HTML at https://validator.w3.org/

---

**Created by:** Form Structure & Integration Lead  
**Date:** February 7, 2026  
**Status:** Base structure complete, awaiting team contributions
